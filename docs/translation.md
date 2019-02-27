
Source :~ <http://compendiumld.open.ac.uk/documentation/translation/>

# CompendiumLD in other languages

The user interface and documentation of CompendiumLD is currently available in English only. However, it is possible create a versions in other languages. If you would be interested in creating a version of CompendiumLD in another language you can try it out by translating the file menu and please [contact Andrew Brasher](mailto:a.j.brasher@open.ac.uk) to discuss your plans with respect to translating CompendiumLD.

### To create a version of CompendiumLD in another language

The work can be broken down into [(1) translation work](#translationWork) and [(2) technical work](#technicalWork).

#### <a name="translationWork" ></a>(1) Translation work

There are 4 different sets of resources that can be translated.

1.  <a name="translationWorkUI" ></a>the text used in the CompendiumLD user interface
    The text used for the `File menu` in English is stored in a file named '[menus_en.properties](Languages/en/menus_en.properties.txt)'. To create a version in another language, this file needs to be translated. Everything to the right of an equals sign (=) would need to be translated into the new language, for example the line
    `UIMenuFile.exportLdXMLTip=Export selected nodes as learning design zip file`
    could become
    `UIMenuFile.exportLdXMLTip=Exportar los nodos seleccionados a un fichero de diseño de aprendizaje ZIP`
    in a Spanish version of the file.
    To complete the translation, translations of 12 other files would need to be completed, e.g.: [dialogs_en.properties](Languages/en/dialogs_en.properties.txt), [edits_en.properties](Languages/en/edits_en.properties.txt), [general_en.properties](Languages/en/general_en.properties.txt).
    The translated files would then be stored in a folder using the appropriate two letter code given in [ISO 639.2][] (e.g. es for Spanish, de for German).

    The [Compendium Exchange](http://compendium.open.ac.uk/moodle/) site enables you to [browse](http://compendium.open.ac.uk/moodle/blocks/compendium_languages/browsemaps.php?context=44&id=4) and [share](http://compendium.open.ac.uk/moodle/blocks/compendium_languages/sharemaps.php?context=44&id=4) language files necessary for realising the user interface of Compendium 2.0 beta in other languages. Although the interface of CompendiumLD differs from that of Compendium, you can get a rough idea of the scale of the translation work required by [downloading the interface files for Compendium 2.0](http://compendium.open.ac.uk/moodle/blocks/compendium_languages/browsemaps.php?context=44&id=4). I estimate that there are about 1900 strings (phrases) that need to be translated for the CompendiumLD interface.

2.  the help system (i.e. the help available via CompendiumLD's help menu)
3.  the installer files e.g. readme and licence files
4.  Other documentation e.g. the CompendiumLD [web site](http://compendiumld.open.ac.uk/), and guides and slide shows listed in the [documentation section](http://compendiumld.open.ac.uk/documentation.html).

#### <a name="technicalWork" ></a>(2) Technical work

The programming required to enable the `File menu` to be delivered in different languages has been completed, so you can try this out by following [the instructions in the translation work section](#translationWorkUI). Further programming work is required to make the other user interface components available for translation in the same way that the file menu is. I have outlined the work required below in case any one wants to do it by editing the [source code](../../about.html#sourceCode), or by negotiating a partnership with us to get the necessary work done.

##### (a) Externalize all Strings in the code

CompendiumLD is a Java application. All the text that appears in the user interface is stored as a "String" that the Java code presents to the user. To create versions in different languages, all the Strings within the code need to be stored in text files external to the code, and a set of files will be needed for each language. I have begun the process of externalising the Strings into a set of text files containing the English text necessary to render the user interface, i.e so far I have externalised all the Strings for CompendiumLD menus. However, most of the remaining text remains embedded within the code. I would need to complete the process, i.e externalise all the remaining Strings into text files. I have externalised about 300 Strings (for the menus), and I think there are about 1600 remaining to be done.

##### (b) The help system

Currently all the help available via the help menu has not been edited to include help about features of CompendiumLD, it is just the help for the standard version of Compendium. We do plan to edit this help to make it specific to CompendiumLD  but that has not happened yet. If you wanted the help system delivered in another language it would require some coding to make sure the application presented the other language help to the user. Of course, the version of the help in the other language would also have to be created.

[archive]: https://web.archive.org/web/20170521175325/http://compendiumld.open.ac.uk/documentation/translation/
[ISO 639.2]: https://www.loc.gov/standards/iso639-2/php/English_list.php
  "ISO 639.2: Codes for the Representation of Names of Languages"

---
