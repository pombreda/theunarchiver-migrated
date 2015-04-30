# theunarchiver
Mac, Linux and Windows universal unarchiver.  CLI everywhere  and MAC Gui. Objective-C, GPL-licensed. Originally from code.google.com/p/theunarchiver

The Unarchiver is an Objective-C application for uncompressing archive files.

    Supports many formats such as Zip, Tar, Gzip, Bzip2, 7-Zip, Rar, LhA, StuffIt, several old Amiga file and disk archives, CAB, LZX, stuff I don't even know what it is. Read the wiki page for a more thorough listing of formats.
    Copies the Finder file-copying/moving/deleting interface for its interface.
    Uses the character set autodetection code from Mozilla to auto-detect the encoding of the filenames in the archives.
    Supports split archives for certain formats, like RAR.
    Version 2.0 uses an archive-handling library built largely from scratch in Objective-C, which makes adding support for new formats and algorithms very easy.
    Uses libxad (http://sourceforge.net/projects/libxad/) for older and more obscure formats. This is an old Amiga library for handling unpacking of archives. 
