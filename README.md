Cuis-Ia-En
==========

Solitaire &lt;-> Klondike & FreeCell Solitaire Games



To load the package

    | slash |
    slash := FileDirectory slash.
     CodePackageFile installPackageStream:
        (FileStream concreteStream readOnlyFileNamed: 
            '..', slash, 'Cuis-Solitaire', slash, 'Morphic-Games-Solitaire.pck.st'
        )

Then execute

    Klondike newGame.
    FreeCell newGame.
