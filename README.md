Wiki:  [Home](https://github.com/openlilylib/LO-ly/wiki#ooolilypond) | [Download](https://github.com/openlilylib/LO-ly/wiki/Downloads#downloads) | [Installation](https://github.com/openlilylib/LO-ly/wiki/Installation#installation) | [Tutorial](https://github.com/openlilylib/LO-ly/wiki/Tutorial#tutorial) | [Advanced features](https://github.com/openlilylib/LO-ly/wiki/Advanced-features#advanced-features) | [Reference](https://github.com/openlilylib/LO-ly/wiki/Editor-(main-window-reference)#editor-main-window-reference) | [Configuration](https://github.com/openlilylib/LO-ly/wiki/Config#configuration-dialogue)

# OOoLilyPond

| *ANNOUNCEMENT* | 
| :---: |
| **OOoLilyPond has moved to a new repository:** |
| **https://github.com/OOoLilyPond** |
| **All past/present/future development can be found at the new location. The page you are viewing right here contains all development up to V. 1.0.1, but it will no longer be maintained.** |

OOoLilyPond (OLy) is a LibreOffice/OpenOffice extension to include LilyPond music fragments in text documents.

![editor object](https://raw.githubusercontent.com/KlausBlum/OLy-resources/master/images/editor-object-02.gif)

## Installation

* Being a [LibreOffice]/[OpenOffice] extension, you need a version of LibreOffice / OpenOffice installed on your computer, first.  
* Second, the music engraving software [LilyPond] must be installed on your system.  
* Then just download the latest OLy release from the [download] page.  
* The extension can be installed either by opening it with LibreOffice or by following these steps in the menu:

*Extras > Extension Manager… > Add…*

and then choosing the downloaded extension file (.oxt).

Your toolbars in Writer, Impress and Draw should now have a new "OLy" button which launches the extension.

**You can find a detailed documentation [here in the wiki](https://github.com/openlilylib/LO-ly/wiki/Installation#installation).**

## Usage

[LilyPond] is a powerful musical typesetting software that compiles given source code into graphical output, just like LaTeX does with mathematical formulas. 

OOoLilyPond enables you to enter LilyPond code from within your Office document.  
  Both the resulting image and its source code will be embedded within the document.  
  No need to keep any additional files other than the Writer/Draw/Impress document itself.

To create a new OLy object, just click the "OLy" button and an editor window will open. Enter some LilyPond code and click the "LilyPond" button. After successful compiling, the editor window will close and the resulting image will be visible in your document. 

To edit an existing object, select it first and then click the "OLy" button. In the editor window you will have access to your code again.

If you want to get to know LilyPond, a good place to start is the [introduction] into LilyPond.

### Compatibility 

OOoLilyPond (OLy) works with recent versions of LibreOffice and OpenOffice. Older versions should work as well. It has even been tested with OpenOffice 2.4 without issues. 

Update: Some partial incompatibilities have occured in LibreOffice 6.1.0 to 6.1.4 - see [Issue 22].

Any content (LilyPond code, templates, OLy configuration files) created with/for older OLy versions (OLy 0.3.x, OLy 0.4.x, OLy 0.5.x) will work with OLy 1.0.x, but not necessarily vice versa.


[LibreOffice]: http://libreoffice.org/
[OpenOffice]: http://www.openoffice.org/
[LilyPond]: http://lilypond.org
[download]: https://github.com/openlilylib/LO-ly/wiki/Downloads#downloads
[introduction]: http://lilypond.org/introduction.html
[Introduction into OOoLilyPond]: http://lilypondblog.org/2017/04/ooolilypond-creating-musical-snippets-in-libreoffice-documents/
[Scores of Beauty]: http://lilypondblog.org/
[Issue 22]: https://github.com/openlilylib/LO-ly/issues/22#issuecomment-462500338

### Contributors

[Urs Liska](https://github.com/uliska) (infrastructure, GitHub repo)  
[Joram Berger](https://github.com/joram-berger) (infrastructure, feature ideas, improvements, translation)  
[Hannes E. Schäuble](https://github.com/edgar79) (improvements and fixes)  
[Ipsilon Fede](https://github.com/yfede) (feature ideas)  
[tapanis](https://github.com/tapanis) (error reports)  
Valentin Villenave (translation)  
Olivier Miakinen (translation)  
Fernando Villagran (translation)

### Authors

Copyright © 2005 Geoffroy Piroux  
Copyright © 2009 Samuel Hartmann  
Copyright © 2017 Klaus Blum (current maintainer)

<a id="envelope">![a](https://raw.githubusercontent.com/KlausBlum/OLy-resources/master/images/score-a.png)</a>![b](https://raw.githubusercontent.com/KlausBlum/OLy-resources/master/images/score-b.png)![c](https://raw.githubusercontent.com/KlausBlum/OLy-resources/master/images/score-c.png)![d](https://raw.githubusercontent.com/KlausBlum/OLy-resources/master/images/score-d.png)![e](https://raw.githubusercontent.com/KlausBlum/OLy-resources/master/images/score-e.png)![f](https://raw.githubusercontent.com/KlausBlum/OLy-resources/master/images/score-f.png)

## License

This program is free software. It is licensed under the [GPL3].

[GPL3]: https://www.gnu.org/licenses/gpl.html "GPL3"
