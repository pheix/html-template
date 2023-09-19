# A simple almost-port of CPAN's HTML::Template to Raku

This is the fork from: https://github.com/masak/html-template

## License information

Module `HTML::Template` is free and opensource software, so you can redistribute it and/or modify it under the terms of the [The Artistic License 2.0](https://opensource.org/licenses/Artistic-2.0).

## TODO

Nested IF statements don't seem to work:

```xml
<TMPL_IF a>
  <TMPL_IF b>
  </TMPL_IF>
</TMPL_IF>
```

It seems that in `<TMPL_VAR name>` *name* is case sensitive.

## Authors

Originally taken from `AUTHORS` file:

Here is a list of people and their CPAN id.  These people have either submitted patches or suggestions, or their bug reports or comments have inspired the appropriate patches.  Corrections, additions, deletions welcome:

```
Ilya Belikin (aka Ihrd)                      Илья Беликин   <forihrd@gmail.com>
Moritz Lenz                      (MORITZ)
Lyle <http://groups.google.com/group/november-wiki/browse_thread/thread/c046d7892a60eaa5>
Carl Masak                       (MASAK)     Carl Mäsak     <cmasak@gmail.com>
Johan Viklund                    (VIKLUND)                  <johan.viklund@gmail.com>
pheix <https://gitlab.com/pheix>
```
