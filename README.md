<div align="center">
<h1>MRPODS🐙 </h1>

<p>Machine-Readable Printed Optical Data Sheets</p>
</div>

---
Back up digital files to paper.
Rewrite and continuation of Oleh Yuschuk's [PaperBack](https://ollydbg.de/Paperbak/) in modern C++.

Screenshots
-------------
![Screenshot 1](https://raw.githubusercontent.com/artem-r-d/mrpods/main/screenshot-1.png)


Science Paper
-------------
https://arxiv.org/abs/2312.10275

Current Compatibility
-------------
|       | x86  | x64  |
|-------|------|------|
| Debug | Ready     | Needs x64 TWAIN fix     |
| Release | Ready | Needs x64 TWAIN fix     |

TODO: 
* Fix or remove AES
* Add application icon

Project Goals
-------------
The goal of this project is to make the PaperBack project compatible with Visual Studio and modern C++ standards so that it may be compiled without the Borland compiler. This will allow for easier development of additional features such as native x64 support, improved UI, and more.

Compilation
-------------
1. Clone or download repository zip.
2. Install Visual Studio 2022 (Community Edition without logging in is fine)
3. Install the following Visual Studio components: Desktop development with C++, C++ MFC for latest v143 build tools (x86 & x64)
4. Open mrpods.sln solution
5. Build / build + run

Changelog
---------
Version 1.10 - Initial release. Based off PaperBack v1.10. AES functionality is commented out at the moment, and there is no graceful handling of existing AES documents from PaperBack.

Similar Tools (Not Recommended)
-------------
The following tools are either failed attempts to rewrite PaperBack or do not contain all of the features and functionality that the original software provides - a rough 17 years.
* https://github.com/intra2net/paperbackup
* https://github.com/za3k/qr-backup
* https://github.com/piql/boxing
* https://github.com/jabcode/jabcode
* https://github.com/colindean/optar
* https://www.jabberwocky.com/software/paperkey/
* https://github.com/makocodeproject/makocode
* https://github.com/avarner9/paperbak
* https://github.com/colorsafe/colorsafe/issues/17
* https://github.com/fdobrovolny/python-paperbak

Bzib2
-------------
The bzip library https://sourceware.org/bzip2/downloads.html
git://sourceware.org/git/bzip2.git
nmake -f makefile.msc

Copyright
-------------
MRPODS  
built off PaperBack v1.10  

Copyright © 2023 Artem Doll (rewrite)  
Copyright © 2007 Oleh Yuschuk (creator)  
Copyright © 2013 Michael Mohr (AES fix)  
  
Reed-Solomon ECC:  
Copyright © 2002 Phil Karn (GPL)  
  
Bzip2 data compression  
Copyright © 1996-2010 Julian R. Seward (see sources)  
  
AES and SHA code  
Copyright © 1998-2010, Brian Gladman (3-clause BSD)  
  
----- THIS SOFTWARE IS FREE -----  
Released under GNU Public License (GPL 3+)  
Full sources available  
at: https://github.com/artem-r-d/mrpods  
Read the paper: https://arxiv.org/abs/2312.10275  
