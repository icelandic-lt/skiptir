# skiptir

![Version](https://img.shields.io/badge/Version-1.0-darkviolet)
![Python](https://img.shields.io/badge/Python-3.7+-blue?logo=python&logoColor=white)
![CI Status](https://img.shields.io/badge/CI-[unavailable]-red)
![Docker](https://img.shields.io/badge/Docker-[unavailable]-red)

Command-line tool for Icelandic hyphenation.

## Overview
- **Language:** Python
- **Language Version/Dialect:** 
  - Python: 3.7+
- **Category:** [Support Tools](https://github.com/icelandic-lt/icelandic-lt/blob/main/doc/st.md)
- **Domain:** Generic
- **Status:** Stable
- **Origins:** [https://github.com/krunars/skiptir](https://github.com/krunars/skiptir)

## Description

This tool hyphenates Icelandic text.

Usage:

``` shell
./skiptir.py [--mode MODE] [--hyphen HYPHEN]
```

The tool reads text from standard input and prints the
hyphenated result to standard output.

MODE is `pattern` by default, which means using Pyphen
with the latest Icelandic hyphenation patterns.
Other modes are not supported yet.

HYPHEN refers to a custom hyphenation character, e.g. · or -.
By default, the program uses the soft hyphen character (U+00AD).

## License

The project is dual-licensed under the Apache License 2.0 and CC-BY 4.0. See
[LICENSE.md](./LICENSE.md).

## Acknowledgments

This project was funded by the Language Technology Programme for Icelandic
2019-2023. The programme, which is managed and coordinated by
[Almannarómur](https://almannaromur.is/), was funded by the Icelandic Ministry
of Education, Science and Culture.
