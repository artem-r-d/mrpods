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
| Release | Not Ready | Needs x64 TWAIN fix     |

TODO: 
* Reimplement or remove AES functionality
* Fix an overwrite existing files bug
* Clean up x86 Release

Project Goals
-------------
The goal of this project is to make the PaperBack project compatible with Visual Studio and modern C++ standards so that it may be compiled without the Borland compiler. This will allow for easier development of additional features such as native x64 support, improved UI, and more.

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
