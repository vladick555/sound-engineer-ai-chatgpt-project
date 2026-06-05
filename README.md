# Sound Engineer AI — ChatGPT Project Pack

**Sound Engineer AI** — готовый набор инструкций и источников для ChatGPT Project. Он превращает обычный чат в практического ассистента по сведению, мастерингу, DAW, плагинам и анализу скриншотов.

Проект сделан не как отдельное приложение и не как Python-код. Пользователю достаточно создать Project в ChatGPT, вставить главный instruction-файл и загрузить файлы из папки `chatgpt_sources` в Sources.

## Что умеет

- Помогает настраивать плагины по скриншотам: EQ, compressor, limiter, clipper, autotune, reverb, delay, saturation, stereo tools.
- Даёт цепочки обработки под вокал, биты, 808, мастер, send effects и vocal bus.
- Учитывает DAW пользователя: Logic Pro, Ableton Live, FL Studio.
- Учитывает список плагинов пользователя, чтобы не советовать то, чего у него нет.
- Помогает разбирать WAV/AIFF/MP3, если пользователь загрузил аудио в ChatGPT.
- Объясняет настройки человеческим языком: что крутить, почему, какие ошибки избегать.
- Использует список официальных источников, но не распространяет чужие мануалы.

## Как использовать

1. Создай новый Project в ChatGPT.
2. Открой файл:
   `chatgpt_sources/00_PROJECT_INSTRUCTIONS_PASTE_IN_CHATGPT.md`
3. Скопируй его содержимое в поле **Project Instructions / Инструкции проекта**.
4. Загрузи остальные файлы из папки `chatgpt_sources` в **Sources / Источники**.
5. Перед использованием отредактируй `02_USER_PLUGIN_PROFILE_TEMPLATE.md` под свои плагины и загрузи эту версию в Sources.
6. Напиши первое сообщение из файла `13_USER_ONBOARDING_FIRST_MESSAGE.md`.

Подробная инструкция лежит здесь:

- `docs/HOW_TO_INSTALL_IN_CHATGPT_PROJECT_RU.md`
- `docs/WHAT_TO_UPLOAD_TO_SOURCES_RU.md`
- `docs/HOW_TO_UPLOAD_TO_GITHUB_RU.md`

## Важно

Этот репозиторий **не содержит копии чужих мануалов** Logic Pro, Ableton Live, FL Studio, Waves, FabFilter, iZotope и других компаний. Вместо этого проект содержит индекс официальных ссылок и собственные практические правила работы.

## Кому подходит

- артистам
- битмейкерам
- продюсерам
- начинающим звукорежиссёрам
- людям, которые хотят понимать свои плагины, а не просто крутить пресеты

## Рекомендуемое название Project в ChatGPT

```text
Sound Engineer AI
```

## Лицензия

MIT License. См. файл `LICENSE`.
