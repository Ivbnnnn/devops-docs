# devops-docs

Учебный репозиторий практической работы №9.
Используются Pylint, MkDocs, GitHub Actions и GitHub Pages.

## Структура проекта

- `docs/` — исходники документации;
- `src/status.py` — Python-модуль для статического анализа;
- `mkdocs.yml` — конфигурация сайта;
- `.github/workflows/quality.yml` — проверка изменений;
- `.github/workflows/pages.yml` — публикация документации.

Каталог `site/` создаётся при сборке и исключён из Git.