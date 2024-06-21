<!--
**********************************************************************
BCC compiler
Copyright (C) 2020 - 2024 Ben Daws

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
**********************************************************************

NOTE!!! This file is designed to be read with a Markdown renderer.
-->

# B programming language
B is my own hobby project programming language I wrote in [V](https://vlang.io). Currently it does not do much, but the code is very readable. The current release is v1.0.0-beta.

To invoke BCC, run:
```bash
bcc --version # Reads version info
```

Run a B file (identified by the `.b` file extension:)
```bash
bcc file.b executable # BCC makes you name the executable yourself. it's a you problem i guess lol
```

## Build
> You will need the [V](https://vlang.io) compiler. If it is not installed, the makefile will install it for you.