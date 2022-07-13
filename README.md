[![CI](https://github.com/DanielShtrasser/brain_games/actions/workflows/main.yml/badge.svg)](https://github.com/DanielShtrasser/brain_games/actions/workflows/main.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/1fa488478d98d75fa719/maintainability)](https://codeclimate.com/github/DanielShtrasser/File_comparer/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/1fa488478d98d75fa719/test_coverage)](https://codeclimate.com/github/DanielShtrasser/File_comparer/test_coverage)

##
В рамках этого учебного проекта я написал программу для сравнения файлов. На вход программа принимает два разных файла в форматах json, ini, yml и на выходе формирует дифф этих двух файлов. Дифф может быть представлен в трех видах - дерево, плоский формат и в формате json. Я поработал с git, npm, eslint, babel, makefile, lodash, [Code Climate](https://codeclimate.com/), [Travis](https://travis-ci.org/), тестировал свою программу с помощью jest.

## Setup

```sh
$ make install
```

## Run tests

```sh
$ make test
```
Examples of using:

An example of the gendiff utility with flat files (json format)<br>
[![asciicast](https://asciinema.org/a/KUlTJWyVVhvLVug0d8jSgZm8F.svg)](https://asciinema.org/a/KUlTJWyVVhvLVug0d8jSgZm8F)

An example of the gendiff utility with flat files (yml format)<br>
[![asciicast](https://asciinema.org/a/gGSlUN50vwwnsEC20FdT0ccK1.svg)](https://asciinema.org/a/gGSlUN50vwwnsEC20FdT0ccK1)

An example of the gendiff utility with flat files (ini format)<br>
[![asciicast](https://asciinema.org/a/78h39QaGw6ISchhiXcoSJM3Ku.svg)](https://asciinema.org/a/78h39QaGw6ISchhiXcoSJM3Ku)

An example of the gendiff utility working with recursive files (formatter 'stylish')<br>
[![asciicast](https://asciinema.org/a/AeyIhi5myDWaFmfjFM6FleTBm.svg)](https://asciinema.org/a/AeyIhi5myDWaFmfjFM6FleTBm)

An example of the gendiff utility working with recursive files (formatter 'plain')<br>
[![asciicast](https://asciinema.org/a/QSBRL5RpLxsUmhtF6LStn6W0f.svg)](https://asciinema.org/a/QSBRL5RpLxsUmhtF6LStn6W0f)

An example of the gendiff utility working with recursive files (formatter 'json')<br>
[![asciicast](https://asciinema.org/a/1vMFJfXy5xvVfzIGqHXKeQ5wc.svg)](https://asciinema.org/a/1vMFJfXy5xvVfzIGqHXKeQ5wc)


#### Reference to the educational repository
https://github.com/DaniilStr/frontend-project-lvl2
