Cuis-Solitaire
==========

Solitaire:  Klondike & FreeCell Solitaire Games

Tested with Cuis 4.2 revision 1766


You can load this package via FileList selection or do the following in a Workspace, both available via the World>Open menu 

    | slash |
    slash := FileDirectory slash.
     CodePackageFile installPackageStream:
        (FileStream concreteStream readOnlyFileNamed:
            '..', slash, 'Cuis-Solitaire', slash, 'Morphic-Games-Solitaire.pck.st'
        ).

Then execute

    Klondike newGame.
    FreeCell newGame.

Or use the World Menu to invoke:  New Morph > Games-Solitaire > FreeCell
