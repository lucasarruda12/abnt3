# About the app part

Adds this option to the list of avaliable input formats for external (bluetooth, OTG) keyboards.

# About the abnt3 part

My attempt at adding `ABNT2`like functionalities to the standard us layout.  

## Changes

- `Accent` codes are now `combining accent` codes.
> Where Accent ∈ {grave, circumflex, tilde}
> So you can use `~a` to input `ã`, but need `~<space>` to input just the `~`.

## Additions

- `<RIGHT ALT> + vowel` should input the acute accented version of that vowel
> `RALT a` inputs `à`
> [WARNING] And only that! you'll have to modify the code if you {need, like, want} the `RIGHT ALT` key.

# BUILDING

I use Android Studio. You can check out the original repository for better instructions.