# Как установить Sound Engineer AI в ChatGPT Project

## Коротко

1. Создай Project в ChatGPT.
2. Назови его `Sound Engineer AI`.
3. Вставь содержимое файла `00_PROJECT_INSTRUCTIONS_PASTE_IN_CHATGPT.md` в Project Instructions.
4. Загрузи файлы из папки `chatgpt_sources` в Sources.
5. Отредактируй `02_USER_PLUGIN_PROFILE_TEMPLATE.md` под свои плагины.
6. Начни чат внутри проекта.

## Подробно

### Шаг 1. Создай Project

В ChatGPT создай новый проект:

```text
Sound Engineer AI
```

### Шаг 2. Вставь инструкции

Открой файл:

```text
chatgpt_sources/00_PROJECT_INSTRUCTIONS_PASTE_IN_CHATGPT.md
```

Скопируй весь текст и вставь его в поле инструкций проекта.

Это важнее, чем просто загрузить этот файл в источники. Инструкции проекта сильнее влияют на поведение ассистента.

### Шаг 3. Загрузи Sources

Загрузи в Sources файлы из папки:

```text
chatgpt_sources/
```

Рекомендуемый минимум:

```text
01_SOUND_ENGINEER_ROLE.md
02_USER_PLUGIN_PROFILE_TEMPLATE.md
03_OFFICIAL_MANUAL_SOURCES.md
04_SCREENSHOT_ANALYSIS_RULES.md
05_AUDIO_FILE_ANALYSIS_RULES.md
06_VOCAL_CHAIN_SYSTEM.md
07_MASTERING_CHAIN_SYSTEM.md
08_DAW_WORKFLOW_RULES.md
09_PLUGIN_STARTING_SETTINGS.md
10_RESPONSE_TEMPLATES.md
11_TROUBLESHOOTING_DECISION_TREE.md
12_COPYRIGHT_AND_SAFETY_RULES.md
13_USER_ONBOARDING_FIRST_MESSAGE.md
```

### Шаг 4. Настрой профиль пользователя

Перед загрузкой лучше сделать копию:

```text
02_USER_PLUGIN_PROFILE_TEMPLATE.md
```

И заполнить её под себя:

- DAW
- плагины
- микрофон
- наушники
- мониторы
- жанр
- цели звука
- частые проблемы

### Шаг 5. Первое сообщение

Открой:

```text
13_USER_ONBOARDING_FIRST_MESSAGE.md
```

Скопируй сообщение и отправь его в первый чат внутри проекта.

## Важная правда

Если просто загрузить файлы в Sources, проект уже будет полезен. Но лучший вариант — обязательно вставить `00_PROJECT_INSTRUCTIONS_PASTE_IN_CHATGPT.md` именно в Project Instructions.

## Что можно делать после установки

- присылать скрины плагинов
- присылать WAV/MP3
- спрашивать по Logic/Ableton/FL Studio
- собирать вокальные цепочки
- разбирать мастер
- подбирать настройки под свои плагины
