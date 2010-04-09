BBsharp
=======

BBsharp is a library for converting BBCode to HTML. It is written in C#.

It will parse BBCode into a DOM tree, where it will then be able to be exported into a range of formats. At the moment, we're focusing on HTML.

### FAQ
* **Hey, what's that funny character at the start of all the files?**
> That's the Byte Order Mark (BOM) which is an artifact of the Unicode encoding used to save BBsharp source files. It doesn't seem to be handled correctly by Git (and many other Linux tools, I hear.) It's not my fault, but I am looking into ways of resolving the issue. Please let me know if it causes any troubles compiling.

* **Where can I find a prebuilt assembly?**
> For stability's sake, I don't ever commit the cutting edge debug build. I do commit and push the release build though, you can find it in `bin/Release/`. Please note that the release build may not always be up to date with the currently committed code. A release is only committed once it is stable.