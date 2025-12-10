# SV Basic Manual - Resurrected
A classic monospaced font by Johan Winge ([Alatius](https://github.com/alatius)), modernized for programming.
_All credits & rights belong to the [original author](https://github.com/alatius)._

![Showcase](https://github.com/twosixfoursix/sv-basic-manual-resurrected/blob/main/images/sv_basic_manual_showcase_v1001.png)

> ## Origins
>
> _I was reading an old visual basic manual some time ago. I couldn't take my eyes off the beautiful monospaced font they were using for the code excerpts. So I put it through some font recognition app and somehow found the source._
>
> _The talented author of the font, [Johan Winge](https://github.com/alatius) seems to have worked on the font quite some time ago! You can still view [his webpage courtesy of WayBack Machine](https://web.archive.org/web/20120130174357/http://home.student.uu.se/j/jowi4905/fonts/svbasicmanual.html)._
>
> _There were a couple of glyphs missing - I was able to manipulate pieces of existing glyphs to create new ones._
>
> _I hope you enjoy the font as much as I do._

> [!NOTE]
> If you wish to request specific glyphs, please submit an `Issue` and ensure you include the __Unicode code point__ (Although more information would be preferred including some images, styles & a string representation of the raw byte sequence in hexadecimal __Little Endian Form__).

> [!WARNING]
>__All credits & rights belong to the original author.__
>
>__AS SUCH, if you use this font for any purpose, you must send him a link to a free copy of your work to his [email](johan.winge@telia.com) (`johan.winge@telia.com`) as he had stated on his webpage.__

### Modifications:

<pre>
┌───────────────────────────────────────────────────────────────────────┐
│ Newly Added Glyphs                                                    │
├────────┬────────┬────────┬────────┬────────┬────────┬────────┬────────┤
│ .nodef │      { │      } │      • │        │        │        │        │
└────────┴────────┴────────┴────────┴────────┴────────┴────────┴────────┘
</pre>

<pre>
┌───────────────────────────────────────────────────────────────────────┐
│ Newly Added Ligatures                                                 │
├────────┬────────┬────────┬────────┬────────┬────────┬────────┬────────┤
│     == │     != │     <= │     >= │     -> │     <- │     => │    === │
├────────┼────────┼────────┼────────┼────────┼────────┼────────┼────────┤
│    !== │     >> │     << │    >>= │    <<= │        │        │        │
└────────┴────────┴────────┴────────┴────────┴────────┴────────┴────────┘
</pre>

<pre>
┌───────────────────────────────────────────────────────────────────────┐
│ Aligned & Adjusted                                                    │
├────────┬────────┬────────┬────────┬────────┬────────┬────────┬────────┤
│      = │      + │      - │      @ │      : │      | │      [ │      ] │
├────────┼────────┼────────┼────────┼────────┼────────┼────────┼────────┤
│      _ │      ; │        │        │        │        │        │        │
└────────┴────────┴────────┴────────┴────────┴────────┴────────┴────────┘
</pre>

<pre>
┌───────────────────────────────────────────────────────────────────────┐
│ General                                                               │
├───────────────────────────────────────────────────────────────────────┤
│ • Fixed base glyph visible area: horizontal & vertical alignment.     │
├───────────────────────────────────────────────────────────────────────┤
│ • All variations on '=' were made to look different from the          │
│   base '=' glyph due to potential mixups on things '==' & optics      │
│   for things like '==='.                                              │
└───────────────────────────────────────────────────────────────────────┘
</pre>

<pre>
┌───────────────────────────────────────────────────────────────────────┐
│ Removed (Unused, Unknown)                                             │
├────────┬────────┬────────┬────────┬────────┬────────┬────────┬────────┤
│ smallA │ smallI │ smallO │        │        │        │        │        │
└────────┴────────┴────────┴────────┴────────┴────────┴────────┴────────┘
</pre>

<pre>
┌───────────────────────────────────────────────────────────────────────┐
│ Issues                                                                │
├───────────────────────────────────────────────────────────────────────┤
│ • Some characters within unicode section 'Latin-1 Supplement' seem    │
│   to be to be messed up for some reason. I am unable to fix them      │
│   because I am unfamiliar with these languages & do not know how      │
│   OpenType renders these - as a combination of single glyphs & mark   │
│   glyph, or as single glyph?                                          │
├───────────────────────────────────────────────────────────────────────┤
│ • Glyphs within unicode section 'Combining Diacritical Marks' might   │
│   need to be aligned with relation to glyphs that are not.            │
└───────────────────────────────────────────────────────────────────────┘
</pre>
