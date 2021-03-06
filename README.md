This package is a fork of the package [`tomi:upload-server`](https://atmospherejs.com/tomi/upload-server).

Differences:
* some additional event handlers code has been put in a Fiber

It follows the description of the forked package.

--------

This is a server interface package for the [Meteor Uploads](https://github.com/tomitrescak/meteor-uploads)

For the full documentation and instructions on use go to [https://github.com/tomitrescak/meteor-uploads](https://github.com/tomitrescak/meteor-uploads).

####Version Info

* 1.3.X - Documentation is maintained [here]((https://github.com/tomitrescak/meteor-uploads)): 
* 1.2.4 - Removed bug that was not detecting safe file names
* 1.2.0 - Improved serving of files. Now with correct headers. Replaced static middleware.
* 1.1.1 - Removed bug when getFileName was not specified
* 1.1.0 - Auto creation of directories, fileInfo is now passed instead of fileName
* 1.0.1 - Possibility to add data into DBon server
* 1.0.0 - Initial Version with hot code reload
