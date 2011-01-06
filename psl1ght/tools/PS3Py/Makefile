
all: pkgcrypt.so

pkgcrypt.so: crypt.c setup.py
	@`./find-python2` setup.py build_ext
	@cp build/lib.*/pkgcrypt.* .

clean:
	rm -rf build pkgcrypt.*
