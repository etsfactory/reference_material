1. Generate wheels for your distribution: 
```bash
pip wheel .
```
this will result in some like `TA_Lib-0.4.10-cp35-cp35m-linux_x86_64.whl`

2. Install auditwheel (https://pypi.python.org/pypi/auditwheel):
```bash
sudo apt-get install auditwheel
```

3. Install `patchelf`:
```batch
wget http://nixos.org/releases/patchelf/patchelf-0.9/patchelf-0.9.tar.bz2
tar xf patchelf-0.9.tar.bz2
cd patchelf-0.9/
./configure --prefix="$HOME/.local"
make install
strip ~/.local/bin/patchelf
gzip -9 ~/.local/share/man/man1/patchelf.1
PATH = $HOME/.local/bin:$PATH
```

4. Make sure auditwheel can find the linked libraries:
```bash
auditwheel show TA_Lib-0.4.10-cp35-cp35m-linux_x86_64.whl
```

5. It so, patch the wheel file and get a manylinux wheel!:
```bash
auditwheel repair TA_Lib-0.4.10-cp35-cp35m-linux_x86_64.whl
```
