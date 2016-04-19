S3 Bucket Browser that doesn't suck
====================================

Author
-------
Artem Nagornyi

License
--------
GPL v3

Summary
---------
This S3 browser displays the list of files and virtual folders in your Amazon S3 bucket.

This code is based on the original implementation by Nolan Lawson (https://github.com/nolanlawson/pretty-s3-index-html) with my own multiple fixes and enhancements. Also I completely redesigned the implementation of virtual folders.

Usage
-------
Just place the index.html file in the root of your bucket and give it all the necessary permissions.

Then you can open the index using the URL in the following format: http://yourbucketname.s3.amazonaws.com/index.html