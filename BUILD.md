### 1. If building from git (not needed for release tarballs):
Generate build system files (requires autoconf from autotools).
```bash
./autogen.sh
```

### 2. Generate makefiles
```bash
./configure
```
> Run ./configure --help to see configuration options.

### 3. Build executables
```
make
```

### 4. Install executables and manual pages (optional)
```bash
make install
```
> If you are on a system directory, don't forget to add ``sudo``.
