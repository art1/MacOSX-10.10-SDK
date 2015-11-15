# MacOSX-10.10-SDK



Easier Workaround: just change the target in your Qt App .pro file
===

copy to /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs.

Solves the Qt Creator Warning:
"warning: no such sysroot directory: '/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.10.sdk'
error: 'TargetConditionals.h' file not found"
