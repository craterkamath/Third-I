# Third-I
Simple implementation of file system on Linux using FUSE. 

## Usage

* To download the code and start the file system
```
$ git clone https://github.com/yashasbharadwaj111/Third-I-v2.0
$ cd Third-I-v2.0
```
* To run TIFS
```
$ make
```

* Now the file system is mounted at ```Third-I-v2.0/mountPoint/``` you can go into the directory and check for some of the FS functions. 

* No graceful method (yet) is used to unmount the FS at mountPoint
thus , do the following to unmount the FS. Thus,  use
``` $ make stop``` to unmount TIFS.
``` $ make format``` to unmount and format TIFS.

## License

This project is made available under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
