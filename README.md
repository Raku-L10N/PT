[![Actions Status](https://github.com/Raku-L10N/PT/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/PT/actions) [![Actions Status](https://github.com/Raku-L10N/PT/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/PT/actions) [![Actions Status](https://github.com/Raku-L10N/PT/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/PT/actions)

NAME
====

L10N::PT - Portuguese localization of Raku

SYNOPSIS
========

    $ porku -e 'diga "Olá Mundo"'
    Olá Mundo

```raku
use L10N::PT;
diga "Olá Mundo";
```

DESCRIPTION
===========

The `L10N::PT` distribution contains the logic to provide a Portuguese localization of the Raku Programming Language. It installs a `porku` executable that will automatically activate the Portuguese localization. And it allows one to use the Portuguese localization in selected programs with a `use L10N::PT` statement.

AUTHORS
=======

Fernando Corrêa de Oliveira

COPYRIGHT AND LICENSE
=====================

Copyright 2023, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

