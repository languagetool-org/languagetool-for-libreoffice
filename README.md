# LanguageTool

**A proofreading add-on for English, Spanish, German, French, Portuguese, Dutch, Ukrainian
and [more languages](https://dev.languagetool.org/languages)**

Version 6.5-SNAPSHOT (2024-xx-yy)  
Copyright (C) 2005-2024 the LanguageTool community and Daniel Naber (www.danielnaber.de)  
https://languagetool.org


## Requirements

* Java 8 or later
* For LibreOffice/OpenOffice.org integration:
    * LibreOffice 4.2.4 (or later) or
    * Apache OpenOffice 4.1.2 (or later)


## Usage

### LibreOffice/OpenOffice

To integrate LanguageTool into LibreOffice or OpenOffice.org, you can use two methods:

* Double-click `LanguageTool-6.4.oxt`. The extension should
   start installing. Follow the on-screen instructions.

* If the above method doesn't work, call `Tools > Extension
   Manager > Add...` in LibreOffice/OpenOffice.org and browse for the
   `LanguageTool-6.4.oxt` file.

Close and restart LibreOffice/OpenOffice.org Writer. Type text with
an error, e.g. "Feel tree to do so." - make sure the text language
is set to English for this example.

You should see a blue underline under the word "tree" after about a second.
Opening the context menu with the right mouse button on that word
offers you a short description of the error and a correction ("free").

**NOTE:** If you run into trouble, you might want to try using the 
embedded support for LanguageTool that was added in LibreOffice 7.4:
https://forum.languagetool.org/t/new-libreoffice-7-4-languagetool-remote-grammar-checker/8187/2

If you are using LibreOffice and you want to check English or Russian texts:
Use `Options -> Language Settings -> Writing Aids -> Edit...` in the
`Tools` menu to disable LightProof and enable LanguageTool for English.

Note that there will also be a new menu item "LanguageTool"
under the `Tools` menu.
If the native spelling and grammar dialog doesn't check grammar,
make sure that the check box `Check Grammar` is checked in it
(if the window closes because of no mistakes in the document,
simply make any spelling mistake to make it open for a longer
time, and check the box). Check also if LanguageTool is visible
under `Grammar` in `Tools > Options > Language Settings > Spelling`
for your language. Note: you can disable the grammar check without
uninstalling LanguageTool simply by clearing the check box next to
LanguageTool in the same dialog.
  
Please see https://www.languagetool.org/issues/ if you experience problems.

## License

Unless otherwise noted, this software is distributed under
the LGPL, see file [COPYING.txt](https://github.com/languagetool-org/languagetool/blob/master/languagetool-standalone/COPYING.txt)

See https://github.com/languagetool-org/languagetool/blob/master/languagetool-standalone/README.md#license
for detailed license information.
