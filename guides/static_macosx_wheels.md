1. Generate wheels for your distribution: 
```bash
pip wheel .
```
this will result in some like `TA_Lib-0.4.10-cp36-cp36m-macosx_10_7_x86_64.whl`

2. Install `delocate` (https://pypi.org/project/delocate/):
```bash
pip install delocate
```

3. Make sure `delocate` can find the linked libraries:
```bash
delocate-listdeps TA_Lib-0.4.10-cp36-cp36m-macosx_10_7_x86_64.whl
```

4. It so, patch the wheel file and get a statically-linked wheel!:
```bash
delocate-wheel TA_Lib-0.4.10-cp36-cp36m-macosx_10_7_x86_64.whl
```
