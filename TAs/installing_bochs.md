# How to install bochs
by david og simon

- Go to an empty directory, or /tmp
- Download the source code

	$ wget https://sourceforge.net/projects/bochs/files/bochs/2.6.9/bochs-2.6.9.tar.gz/download -O bochs.tar.gz

- Untar the downloaded archive

	$ tar -xzvf bochs.tar.gz

- Move into the bochs directory
	$ cd bochs-2.6.9

- Run the configuration script

	$ ./configure --enable-gdb-stub --enable-usb --prefix=/usr/

- Enter substitute 

	$ make
