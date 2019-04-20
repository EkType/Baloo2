![Baloo 2](https://raw.githubusercontent.com/EkType/Baloo2/master/Promotion/Baloo_header.png "Baloo 2")

A perfect blend of pointy paws in a coat of fur, Baloo is an affable display typeface by Ek Type. This heavy spurless design has already garnered praise for its distinctive jovial nature and its multi script design. 

The all new Baloo 2 now comes in 5 distinct weights ranging from the light footed Regular to the affable ExtraBold. The lighter weights retain Baloo's characteristic bounce, but they do so slightly, infusing life into each word. This allows Baloo 2 to freely fraternise with texts of all Sizes and temperaments – be it short bursts or copious reams, demanding headlines or whispering bylines. Carefree yet confident, sprightly yet versatile, the renewed family of Baloo promises to bring warmth to every project.

Baloo 2 is an extension of the [Baloo Project](https://github.com/EkType/Baloo). The Devanagari and Latin script font from the earlier project has now been extended to five weights. 

Baloo 2 (Latin+Devanagari) is designed by Sarang Kulkarni and Maithili Shingre. Font engineering and type design assistance by Noopur Datye and Girish Dalvi.


### License

Baloo 2 is licensed under the SIL Open Font License v1.1 (<http://scripts.sil.org/OFL>). 
To view the copyright and specific terms and conditions please refer to [OFL.txt](https://github.com/girish-dalvi/Baloo/blob/master/OFL.txt)

### Downloading font binaries (TTF files)

Find binary releases on <https://github.com/EkType/Baloo2/releases>

### How do I install the font on my computer?

First download the font binaries (TTF files) from the [Github Releases page](https://github.com/EkType/Baloo2/releases), then follow these instructions:

- [Windows](http://windows.microsoft.com/en-us/windows-vista/install-or-uninstall-fonts)
- [GNU/Linux](http://lmgtfy.com/?q=how+to+install+fonts+in+linux)
- [Mac OS X](http://support.apple.com/kb/HT2509)


### Getting Involved

Would you like to contribute to the development of this font? Here is how **you** can help:

1. Tell us about any bugs you find, or enhancements you would like to see

2. Contribute directly to the fonts. In this repository we provide the complete set of source files that we use ourselves to develop the fonts. If you with to contribute directly, please see below how we build the fonts and follow our build process so that we can easily include your contribution, and follow the Github pull request process to send your contribution. 

### Bug Reports

Send us bug reports, feature enhancements or glyph requests, using the [Github Issue Tracker](https://github.com/EkType/Baloo2/issues). 

Here are a few tips:

- Bugs must be isolated and reproducible problems that we can fix. This means telling us step by step how we can produce the bug.

- Share as much information as possible. Include your operating system and its version, what application(s) you found the problem with and their version, etc. 

## Building the font from source
   
This requires the following programs:

- **[Fontlab Studio](http://www.fontlab.com/font-editor/fontlab-studio/):** `.vfb` design files are used by this font editor, for Windows and Mac from the Fontlab company with a proprietary license and requiring a license fee from each user. 

- **[AFDKO](http://www.adobe.com/devnet/opentype/afdko.html):** A set of command line tools for generating OpenType fonts from Adobe

The build process used by Ek Type is as follows:

1. Make changes in FontLab `.vfb` file

2. Generate the `.ttf` file

3. Make changes in AFDKO feature files. 

4. Type the following commands in the Command prompt window. Make sure that the AFDKO directory is included in your path.

Use `maketof -h` to view the options available to you; choose the options you want as per your needs. To generate the release version of the font we generally use

    makeotf -f Baloo.ttf -o Baloo-Regular.ttf -r -S -rev

### Branches and Pull Requests

To learn more about Pull Requests, see Github's great article on [using pull requests](https://help.github.com/articles/using-pull-requests) and play the [interactive learning game](http://try.github.com) that takes around 15 minutes to complete.

- `master` is the latest, stable, tested version 

- Add your name to the contributors file

- Explain in the pull request how you have tested your contribution
