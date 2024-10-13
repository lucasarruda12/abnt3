# abnt3

My attempt at adding `ABNT2`like functionalities to external android keyboards built to the standard us layout.  

## Changes

- {grave, circumflex, tilde} codes are now `combining` codes
    - So you can use `~a` to input `ã`, but need `~<space>` to input just the `~`.

## Additions

- `<RIGHT ALT> + vowel` should input the acute accented version of that vowel
    - `RALT a` inputs `à`
> [WARNING] And only that! you'll have to modify the code if you {need, like, want} the `RIGHT ALT` key.
