# sample-cli

Пример реадми, который должен быть.
Здесь должен быть текст о том, что делает проект и кому он нужен.

## Содержание

- [Быстрый старт](#быстрый-старт)
- [Установка](#установка)
- [Использование](#использование)
- [Разработка](#разработка)
- [Лицензия](#лицензия)

## Быстрый старт


```bash
git clone git@github.com:example/sample-cli.git
cd sample-cli
python -m sample_cli --help
```

## Установка

Зависимости: Напиши зависимости.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Использование

Простейший сценарий:

```bash
python -m sample_cli greet --name "Git Bootcamp"
# → Hello, Git Bootcamp!
```

<details>
<summary>Расширенный сценарий (со сворачиваемым блоком)</summary>

```bash
python -m sample_cli greet --name "Git" --shout
# → HELLO, GIT!
```

Внутри `<details>` можно прятать редко нужные подробности, чтобы основной README оставался коротким.

</details>

## Разработка

- Запуск тестов: `pytest`
- Стиль: `ruff check .`
- Перед PR — см. [CONTRIBUTING.md](CONTRIBUTING.md).

## Лицензия

MIT — см. [LICENSE](LICENSE).
