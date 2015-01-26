# JustBeamIt Command Line Utility

The JustBeamIt command line utility is a small Python script that takes advantage of the [http://justbeamit.com](http://justbeamit.com) API.

### **Dependencies**

  1. [requests](http://docs.python-requests.org/en/latest/)
  2. [requests toolbelt](https://github.com/sigmavirus24/requests-toolbelt)
  3. [progressbar2](https://github.com/WoLpH/python-progressbar)

### **Install**

To install, just run the `install.sh` script, which will install the required Python modules as well as create the `beam` command:

    $ ./install.sh

Note that this requires you to have [pip](https://pip.pypa.io/en/latest/index.html) installed. If you don't have [pip](https://pip.pypa.io/en/latest/index.html), you can manually install the 3 dependencies, and then run the following command:

    $ sudo cp beam /usr/bin

Tested with Python 2.7.9.

### **Usage**

You can pass in 1 or more paths to the file(s) you want to transfer as arguments to `beam`. The paths must point to existing files, and directories are not supported.

single file transfers:

    $ beam /path/to/file

multiple file transfers:

    $ beam /path/to/file1 /path/to/file2 /path/to/file3 ...

### **Contact Us**

Feel free to email us `team@justbeamit.com` for any questions, comments, thoughts, etc...