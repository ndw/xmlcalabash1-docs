# XML Calabash pegdown Step

This repository contains an [XML Calabash](http://github.com/ndw/xmlcalabash1)
1.1 extension steps that supports the
[pegdown](https://github.com/sirthias/pegdown) MarkDown to HTML
translator.

This step should work with either Saxon 9.5 or Saxon 9.6.

## Installation

For standalone installation, get the most recent release from the project
[releases](http://github.com/ndw/xmlcalabash1-pegdown/releases) page.
The release distributed there includes
relevant dependencies. Unpack it somewhere on your system and add the
included, top-level `jar` file to your class path.

If you're using Maven, you can also get it from there. Note, however,
that the Maven distribution includes a POM file that identifies other
dependencies that must also be downloaded. You'll need them too, which
happens naturally if you're including the Maven dependency in some
other Maven project. If you just grab the `jar` from Maven and don't
get the other dependencies, you're likely to find that the step
doesn't work because of some missing dependencies.
