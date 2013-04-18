Cuis-Solitaire
==========

Solitaire:  Klondike & FreeCell Solitaire Games

Tested with Cuis 1686


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

Or use the World Menu to invoke:  New Morph > Games-Solitaire
