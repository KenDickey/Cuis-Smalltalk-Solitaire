Cuis-Ia-En
==========

Solitaire &lt;-> Klondike & FreeCell Solitaire Games



To load the package

    | slash |
    slash := FileDirectory slash.
    CodeFileBrowser installPackage:
        (FileStream concreteStream readOnlyFileNamed: 
            '..', slash, 'Cuis-Solitaire', slash, 'Morphic-Games-Solitaire.pck.st'
        )

Then execute

    Klondike newGame.
or
    FreeCell newGame.
