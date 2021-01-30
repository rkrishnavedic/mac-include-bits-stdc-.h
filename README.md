How to include bits/stdc++.h in macOS?

Reference: https://gcc.gnu.org/onlinedocs/gcc-4.8.0/libstdc++/api/a01541_source.html

Here stdc++.h file is adapted from above reference.

Now, for the bits/stdc++.h to work in macOS, go with following steps:

1. open /Applications/ and right click on XCode and press "Show Package Contents"
2. and go to the directory = /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/include/
3. Here create a directory named "bits" (excluding double qoutes)
4. And, copy the stdc++.h file inside that /bits/
5. Now, you are good to go!
