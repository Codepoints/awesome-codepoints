# Awesome Codepoints [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a curated list of characters in Unicode, that have interesting (and maybe not widely known) features or are awesome in some other way.

## Table of contents

1. [Standalone codepoints](#standalone-codepoints)
2. [Codepoints that affect others](#codepoints-that-affect-others)
3. [Record holders and extremes](#record-holders-and-extremes)
4. [For funsies](#for-funsies)

## Standalone codepoints

* U+1680 OGHAM SPACE MARK - a space that looks like a dash. Great to bring programmers close to madness: `1 +  2 === 3`
* U+037E GREEK QUESTION MARK - a look-alike to the semicolon. Also a fun way to annoy developers.
* U+D800 to U+DFFF - surrogate codepoints. They are only reserved to ease UTF-16 encoding.
* U+2E2E REVERSED QUESTION MARK - the “irony mark” to express irony/sarcasm.
* U+FFFD REPLACEMENT CHARACTER - when a character cannot be displayed (e.g., decoding an erroneous UTF-8 sequency), this codepoint steps into the breach.

## Codepoints that affect others

* U+FE0E VARIATION SELECTOR-15 - force colorful emoji
* U+FE0F VARIATION SELECTOR-16 - force black-_&_-white emoji
* U+00A0 NO-BREAK SPACE - force adjacent characters to stick together
* U+2060 WORD JOINER - the same as U+00A0, but completely invisible. Good for writing `@font-face` on Twitter
* U+200D ZERO WIDTH JOINER - force adjacent characters to be joined together (e.g., arabic characters or supported emoji). Apple uses this to compose some emoji like different families.
* U+200B ZERO WIDTH SPACE - the inverse to U+00A0: create no space, but allow word breaking.
* U+00AD SOFT HYPHEN - (in HTML: &amp;shy;) like ZERO WIDTH SPACE, but show a hyphen if (and only if) a break occurs
* U+202D and U+202E - change the text direction. Relevant XKCD:
    
    [![](http://imgs.xkcd.com/comics/rtl.png )](https://xkcd.com/1137/)

## Record holders and extremes

* U+0000 &lt;control> - first codepoint
* U+EFFFF (_non-character_) - last (currently defined) codepoint. U+10FFFF is the ultimately last one, but it is a private use character, that is guaranteed to be never defined by Unicode.
* U+1F402 OX - shortest name
* U+FBFB ARABIC LIGATURE UIGHUR KIRGHIZ YEH WITH HAMZA ABOVE WITH ALEF MAKSURA INITIAL FORM - longest name: 82 characters
* U+FDFA ARABIC LIGATURE SALLALLAHOU ALAYHE WASALLAM - longest decomposition form: 18 characters

## For funsies

* U+1D455 is missing. It would be an italic small “h”. It was not encoded, because it would be identical to the Planck constant ℎ (U+210E).
* U+1F918 SIGN OF THE HORNS - Rock on!
* U+F8FF PRIVATE USE CODEPOINT - this private use codepoint is rendered as Apple logo on many Apple devices.
* U+1DD2 COMBINING US ABOVE - most romantic codepoint
