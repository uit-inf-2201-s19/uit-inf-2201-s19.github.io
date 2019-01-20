# How to install bochs

- Go to an empty directory, or /tmp
- Download the source code

`$ wget https://sourceforge.net/projects/bochs/files/bochs/2.6.9/bochs-2.6.9.tar.gz/download -O bochs.tar.gz`

- Untar the downloaded archive

`$ tar -xzvf bochs.tar.gz`

- Move into the bochs directory

`$ cd bochs-2.6.9`

- Run the configuration script

`$ ./configure --enable-gdb-stub --enable-usb --prefix=/usr/`

- Make

`$ make` *(duh)*

- Enter substitute user

`$ su`

- Make install

`$ make install` *(duh²)*

- Exit the su session

`$ exit`

- Now bochs is installed, and you can delete the folder and the archive that was downloaded.
