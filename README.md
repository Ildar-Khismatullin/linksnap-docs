# LinkSnap API

>Вымышленный сайт для создания коротких ссылок

Документация API для сервиса сокращения ссылок. **Учебный проект**

---

## Оглавление :clipboard:

 - [О проекте](#о-проекте)
 - [Что внутри](#что-внутри)
 - [Технологии](#технологии)
 - [Методы API](#методы-api)
 - [Ресурсы](#ресурсы)

---

## О проекте

Проект направлен на обучение и ознакомление с работой технического писателя, а также получение минимального опыта в данной сфере

В проекте рассмотрены:
 - Составление OpenAPI-спецификации для REST API
 - Оформление README-документации в Markdown
 - Оформление UserGuide-документации в Markdown

## Что внутри

|Файл|Назначение|Статус|
|---|---|---|
|[openapi.yaml](./openapi.yaml)|Спецификация API|:white_check_mark: Добавлен базовый эндпоинт|
|[USER_GUIDE.md](./USER_GUIDE.md)|Инструкция пользователя|:recycle: В процессе|
|[README.md](./README.md)|Документация проекта|:recycle: В процессе|
|[RELEASE_NOTES.md](./)|История изменений|:clock10: Запланировано|

## Технологии

- **VS Code** - среда разработки
- **OpenAPI 3.0** - спецификация API
- **YAML** - формат описания
- **OpenAPI (Swagger UI) Editor** - визуализация и тестирование
- **Markdown** - оформление документации
- **Git / GitHub** - контроль версий

## Методы API

| Метод | Путь | Описание |
|-------|------|----------|
| POST | `/shorten` | Создать короткую ссылку |

## Ресурсы

- [Курс по документированию REST API](https://github.com/docops-hq/learnapidoc-ru?tab=readme-ov-file) - вольный перевод курса Documenting APIs: A guide for technical writers
- [OpenAPI Specification v3.0.3](https://spec.openapis.org/oas/v3.0.3.html) - спецификация OpenAPI v3.0.3
- [OpenAPI и Swagger Editor - своё описание REST API с нуля](https://www.youtube.com/watch?v=hPzorok-gI4&list=PL4MpKy3QjNp8IsepABrb_c6D867DFO6aR&index=4) - пример создания OpenAPI-спецификации
- [Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908) - список Markdown-маркеров эмоджи для GitHub
- [Мираполис: вход в личный кабинет Апрель](https://eduela.ru/spr/mirapolis-vhod-v-lichnyy-kabinet-aprel#toc-3) - инструкция от Mirapolis по входу в личный кабинет аптеки "Апрель" 