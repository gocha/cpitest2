cpitest2
========

Simple experimental ripper tool, which can find and extract hidden files stored in an archive.

cpitest2 has the following features.

- Simple: Drag and drop is all you need to do
- Supported Formats: BMP, JPEG, GIF, PNG, MAG, MIDI, RIFF (WAVE, AVI, Animated Cursor, etc.), FORM (AIFF), Ogg (Vorbis, Video, Speex)
    - It is plugin-based. You can add more if you have programming skills!

How to use
------------------------

Drop file(s) to cpitest2.exe icon. It will automatically scan all input files. Found files will be saved into a directory named like "input_file.bin.files".

### Caution

- At the file scan process, whole of file will be loaded at a time. Large file can consume all available memory space and slow your machine down fatally.
- Disk capacity will not be checked before the file extraction. If you do not have enough disk space, the extraction will fail on the way.

cpitest2 is programmed in [HSP](http://hsp.tv/) and C. It is experimental program and it has been abandoned for a long time. I will probably no longer update this tool.

Related tools
------------------------

There are some similar ripper tools. Here I introduce a few of them.

- [ExtractData](http://atelibet.s11.xrea.com/side_yuu/tool/) - GUI. General formats and a lot of eroge formats are supported. Released under the GPL.
- [Crass](http://galcrass.blog124.fc2blog.us/) - CUI/GUI. Similar to ExtractData.
- [X-Ripper](http://www.zeus-software.com/downloads/xripper) - GUI. Popular general formats are supported. Sometimes it may fail with an unknown error.
- [DataCutter](http://www.geocities.jp/iooiau/datacutter.html) - GUI. Popular general formats are supported. Released under the GPL.
- [Neko57](http://www.vector.co.jp/soft/win95/hardware/se254476.html) - This is a debugger tool for Windows executables, not a ripper tool. It has a pattern-search function, and it seems to have presets for some generic formats.

For game-specific formats, you may want to search a appropriate Susie plugin.

Thanks to
------------------------

- Ishizuka: For creating Super Getter, a very *cute* ripper tool. It motivated me a lot, and he kindly replies to my question: "how can I make such a tool?" Thank you very much.
- Onitama: For [Hot Soup Processor](http://hsp.tv/), that gave me a chance to learn programming. (I do not like HSP's language specification today, though)
- HSP users, freeware authors: For contributing various useful resources.

And you users! I find a comment that mentions cpitest2 once in a blue moon. It makes me happy. Thank you for using my tool.
