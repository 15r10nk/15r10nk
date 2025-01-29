## About me 👋

I'm a software developer. My goal with my opensource work is to help other people to develop better software faster.

My main projects are:

### [inline-snapshot](https://github.com/15r10nk/inline-snapshot) ![GitHub Repo stars](https://img.shields.io/github/stars/15r10nk/inline-snapshot?style=flat) [![PyPI - Downloads](https://img.shields.io/pypi/dw/inline-snapshot)](https://pypacktrends.com/?packages=inline-snapshot&time_range=2years)

Allows you to write
```python
def test_addition()
    assert 5+5==snapshot()
```
and to change the snapshot to  `snapshot(10)` when you run `pytest --inline-snapshot=create`

### [pysource-minimize](https://github.com/15r10nk/pysource-minimize) ![GitHub Repo stars](https://img.shields.io/github/stars/15r10nk/pysource-minimize?style=flat) [![PyPI - Downloads](https://img.shields.io/pypi/dw/pysource-minimize)](https://pypacktrends.com/?packages=pysource-minimize&time_range=2years)


Helps you to find bugs by minimizing python source files to the minimal amount of code which is necessary to reproduce the bug


### [pysource-codegen](https://github.com/15r10nk/pysource-codegen) ![GitHub Repo stars](https://img.shields.io/github/stars/15r10nk/pysource-codegen?style=flat) [![PyPI - Downloads](https://img.shields.io/pypi/dw/pysource-codegen)](https://pypacktrends.com/?packages=pysource-codegen&time_range=2years)


Generates random python code, which is useful to test linter, formatter or other tools which work with python code.

### [codecrumbs](https://github.com/15r10nk/codecrumbs) ![GitHub Repo stars](https://img.shields.io/github/stars/15r10nk/codecrumbs?style=flat) [![PyPI - Downloads](https://img.shields.io/pypi/dw/codecrumbs)](https://pypacktrends.com/?packages=codecrumbs&time_range=2years)


Codecrumbs can be used to refactor code across space 🚀 and time ⏰.
The idea is to annotate your python code with decorators which describe deprecations.
These refactoring can then be applied by some one else in some other project which uses your library.

### [lazy-imports-lite](https://github.com/15r10nk/lazy-imports-lite) ![GitHub Repo stars](https://img.shields.io/github/stars/15r10nk/lazy-imports-lite?style=flat) [![PyPI - Downloads](https://img.shields.io/pypi/dw/lazy-imports-lite)](https://pypacktrends.com/?packages=lazy-imports-lite&time_range=2years)


lazy-imports-lite allows you to use [PEP 690](https://peps.python.org/pep-0690/) like lazy-imports enabled per package/library.
The implementation is based on AST rewriting and can be used for python 3.8+.

## Sponsors ❤️

[Sponsoring](https://github.com/sponsors/15r10nk) allows me to invest more time in my open source projects.

### Goal *10 Sponsors*

#### [canonical-imports](https://github.com/15r10nk/canonical-imports) ![GitHub Repo stars](https://img.shields.io/github/stars/15r10nk/canonical-imports?style=flat)

Managing imports is difficult when the project grows in size.
Functions and classes gets moved or renamed.
`canonical-imports` follows your imports and finds out where the things you are importing are actually defined. It can change your imports which makes your code cleaner and maybe even faster.

### Goal *200$*

#### [inline-snapshot-pandas](https://github.com/15r10nk/inline-snapshot-pandas) ![GitHub Repo stars](https://img.shields.io/github/stars/15r10nk/inline-snapshot-pandas?style=flat)

[pandas](https://pandas.pydata.org) integration for [inline-snapshot](https://github.com/15r10nk/inline-snapshot).

``` python
def test_assert_equal():
    df = DataFrame({"col0": [1, 2]})

    assert_frame_equal(df, snapshot(DataFrame([{"col0": 1}, {"col0": 2}])))
```

## Stars

I'm also collecting stars ✨, and your support by starring my projects would be awesome 🤩

[![Star History Chart](https://api.star-history.com/svg?repos=15r10nk/inline-snapshot,15r10nk/pysource-codegen,15r10nk/pysource-minimize,15r10nk/codecrumbs,15r10nk/first-shell,15r10nk/lazy-imports-lite&type=Date)](https://star-history.com/#15r10nk/inline-snapshot&15r10nk/pysource-codegen&15r10nk/pysource-minimize&15r10nk/codecrumbs&15r10nk/first-shell&15r10nk/lazy-imports-lite&Date)

<!--
**15r10nk/15r10nk** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
