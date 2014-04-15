# Typomatic &mdash; a Sass &amp; Compass based typographic kit
> Typomatic is an all-purpose, pre-cooked Sass typographic kit for your daily needs.

Typomatic uses Compass Vertical Rhythm module and Sass Maps to give a flexible solution for handling type scale on a project. 

## Mixins
### type-scale
The scale is defined in the *$type-scale* Sass Map type sizes defined in the *config.scss* file. 

Mixin arguments:

    $scale

The scale argument takes a value from the list of sizes (small, base, medium...) defined in the *$type-scale* map.

    $map
    
The map argument takes a map defined in the *$type-scale* map, usefull if you have two different typefaces with different styles. 


### type-weight
The weights are defined in the *$type-weight* Sass Map type sizes defined in the *config.scss* file. 

Arguments:

    $weight
    
The weight argument takes a value from the list of weights (light, regular, bold...) defined in the *$type-weight* map.