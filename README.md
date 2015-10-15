# Awesome Codepoints [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a curated list of characters in Unicode, that have interesting (and
maybe not widely known) features or are awesome in some other way.

## Table of contents

1. [Standalone codepoints](#standalone-codepoints)
2. [Codepoints that affect others](#codepoints-that-affect-others)
3. [Record holders and extremes](#record-holders-and-extremes)
4. [For funsies](#for-funsies)

## Standalone codepoints

* [U+D800](https://codepoints.net/U+D800) to
    [U+DFFF](https://codepoints.net/U+DFFF) - surrogate codepoints. They are
    only reserved to ease [UTF-16
    encoding](https://en.wikipedia.org/wiki/UTF-16).
* [U+2E2E](https://codepoints.net/U+2E2E) REVERSED QUESTION MARK - the “irony
    mark” to express irony/sarcasm. A useful character&#x2E2E;
* [U+FFFD](https://codepoints.net/U+FFFD) REPLACEMENT CHARACTER - when a
    character cannot be displayed (e.g., decoding an erroneous UTF-8 sequency),
    this codepoint steps into the breach.
* [U+1D455](https://codepoints.net/U+1D455) is missing. It would be an italic
    small “h”. It was not encoded, because it would be identical to the Planck
    constant ℎ ([U+210E](https://codepoints.net/U+210E)).
* The codepoints of the Unicode blocks [Box
    Drawing](https://codepoints.net/box_drawing) (U+2500 to U+257F) and [Block
    Elements](https://codepoints.net/block_elements) (U+2580 to U+259F) cover
    most of your monospace command-line visualization needs.

        ╭───────╮
        │Unicode│
        │rules! │
        ╰┬─────┬╯

## Codepoints that affect others

* [U+FE0E](https://codepoints.net/U+FE0E) VARIATION SELECTOR-15 - force
    colorful emoji
* [U+FE0F](https://codepoints.net/U+FE0F) VARIATION SELECTOR-16 - force
    black-_&_-white emoji
* [U+00A0](https://codepoints.net/U+00A0) NO-BREAK SPACE - force adjacent
    characters to stick together. Well known as `&nbsp;` in HTML.
* [U+2060](https://codepoints.net/U+2060) WORD JOINER - the same as
    U+00A0, but completely invisible. Good for writing `@font-face` on Twitter
* [U+200D](https://codepoints.net/U+200D) ZERO WIDTH JOINER - force adjacent
    characters to be joined together (e.g., arabic characters or supported
    emoji). Apple uses this to compose some emoji like different families.
* [U+200B](https://codepoints.net/U+200B) ZERO WIDTH SPACE - the inverse to
    U+00A0: create no space, but allow word breaking.
* [U+00AD](https://codepoints.net/U+00AD) SOFT HYPHEN - (in HTML: &amp;shy;)
    like ZERO WIDTH SPACE, but show a hyphen if (and only if) a break occurs
* [U+202D](https://codepoints.net/U+202D) and
    [U+202E](https://codepoints.net/U+202E) - change the text direction.
    Relevant XKCD:

    [![](http://imgs.xkcd.com/comics/rtl.png )](https://xkcd.com/1137/)
* Diacritics and combining marks: There is a [host of
    characters](https://codepoints.net/search?gc=Mn), that add
    to the characters before. Those are called Combining Marks. Unicode
    provides a [handy FAQ](http://unicode.org/faq/char_combmark.html) on the
    details, but in a nutshell: If you add one after a character, it is placed
    on top of that previous one. So, `a + ̊˚ = å`. This _may_ lead to all kinds
    of funny problems, because for some combinations there are pre-composed
    characters. Our little `å` here might also be encoded as U+00E5. You might
    note, that while this has a length of one character, the combination of a
    and combining ring has a length of two characters.

    Of course, one can also do fun things with those characters like
    [this answer](http://stackoverflow.com/a/1732454/113195) on StackOverflow.

## Record holders and extremes

* [U+0000](https://codepoints.net/U+0000) &lt;control> - first codepoint
* [U+EFFFF](https://codepoints.net/U+EFFFF) (_non-character_) - last (currently
    defined) codepoint. [U+10FFFF](https://codepoints.net/U+10FFFF) is the
    ultimately last one, but it is a private use character, that is guaranteed
    to be never defined by Unicode.
* [U+1F402](https://codepoints.net/U+1F402) OX - shortest name
* [U+FBFB](https://codepoints.net/U+FBFB) ARABIC LIGATURE UIGHUR KIRGHIZ YEH
    WITH HAMZA ABOVE WITH ALEF MAKSURA INITIAL FORM - longest name: 82
    characters
* [U+FDFA](https://codepoints.net/U+FDFA) ARABIC LIGATURE SALLALLAHOU ALAYHE
    WASALLAM - longest decomposition form: 18 characters

## For funsies

* [U+1680](https://codepoints.net/U+1680) OGHAM SPACE MARK - a space that looks
    like a dash. Great to bring programmers close to madness: `1 +  2 === 3`
* [U+037E](https://codepoints.net/U+037E) GREEK QUESTION MARK - a look-alike to
    the semicolon. Also a fun way to annoy developers.
* [U+1F918](https://codepoints.net/U+1F918) SIGN OF THE HORNS - Rock on!
    &#x1F918;
* [U+1F596](https://codepoints.net/U+1F596) RAISED HAND WITH PART BETWEEN
    MIDDLE AND RING FINGERS - the Vulcan salute. Live long and prosper!
    &#x1F596;
* [U+F8FF](https://codepoints.net/U+F8FF) PRIVATE USE CODEPOINT - this private
    use codepoint is rendered as Apple logo on many Apple devices.
* [U+1DD2](https://codepoints.net/U+1DD2) COMBINING US ABOVE - most romantic
    codepoint
* [U+1F574](https://codepoints.net/U+1F574) MAN IN BUSINESS SUIT LEVITATING -
    A rather curious character, that only made it into Unicode for its
    appearance in the Webdings font (for reasons of backwards compatibility).
