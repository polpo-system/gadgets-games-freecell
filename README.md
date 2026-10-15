# gadgets-games-freecell

Freecell for the gadgets of [polpo](https://github.com/polpo-system/polpo): every card is open, and four free cells hold one card each.

```
portia.Install gadgets-games-freecell
```

## Playing

    Desktops.OpenDoc (Freecell.NewDoc)    a new game

Drag cards with the mouse; the menu has Undo and New.

`tools/Freecell.Tool` has these commands to click.

## What is here

    src/Freecell.Mod      the game
    tools/Freecell.Tool
    test/FreecellTest.Mod

Freecell is by Patrick Saladin, from ETH Native Oberon 2.3.6. The source was converted from an Oberon text to plain text; the first commit has it
unchanged. It compiles unchanged with all five of polpo's compilers (x86, ARM, ARMv7, RISC-V,
MIPS). The cards come from gadgets-games-cards, the icon of its documents from gadgets-icons2.

## Tests

    FreecellTest.Run      2 checks: a game document made and loaded; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
