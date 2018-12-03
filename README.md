# Third-I
Simple implementation of file system on Linux using FUSE. 

## Usage

* To run TIFS
```
$ make
```

* Now the file system is mounted at ```/mountPoint/``` you can go into the directory and check for some of the FS functions. 

* No graceful method (yet) is used to unmount the FS at mountPoint
thus , do the following to unmount the FS. Thus,  use
``` $ make stop``` to unmount TIFS.
``` $ make format``` to unmount and format TIFS.

## License

This project is made available under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
