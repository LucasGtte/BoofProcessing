# Boof Processing

Boof Processing is a wrapper around [BoofCV](http://boofcv.org) for the [Processing](https://processing.org/) environment.
It provides an  easier to use API and special functions for Processing.

# Requirements

To build the library you need the Java JDK, Gradle, and Processing 3 installed.  Gradle will automatically download all the library
requirements, except for Processing.  You will need to download Processing 3.x and copy over the 'core.jar' file and
place it in 'BoofProcessing/core.jar'.

The 'core.jar' file can be found in your Processing installation at process-XXX/core/library/core.jar, where XXX is
installed version of processing.  Unfortunately there is no officially supported version of Processing on Maven
central so it cannot be automatically installed.  Which is why you have to do this manual hackery.

To run the examples you will need to install the Video library.  This is done through the usual means.  In your sketchbook
select Sketch->"Import Library..." then search for "Video" and install it.

# Building

Once you have 'core.jar' you can then run the Gradle build script. It should work with zero issues because it downloads
all the dependencies.  From the commandline you can run the Gradle script by typing

```bash
cd BoofProcessing
gradle processingZip
```

Then after a little bit boofcv_processing.zip should appear in the BoofProcessing directory.  This can then be opened 
inside your "~/sketchbook/libraries" directory.

# Comments/Questions

Use the BoofCV forum to ask questions about this library.

[Message Board](http://groups.google.com/group/boofcv)

# Help Boof Processing!

Boof Processing is in a maintenance mode right now.  Bugs will be fixed and rarely new features will be added.  It
currently only supports a few of the features in BoofCV and to reach its full potential really needs someone who can
give it more attention and is more familiar with Processing.

So if you think you want to quickly add a new feature or fix a bug just fork the code and do it!  Just let me know
when you think the code is ready to be merged back in.

# Author

Peter Abeles is the author of this library.  E-mail address is peter.abeles@gmail.com
