# Что загружать в ChatGPT Sources

## Загружать обязательно

Файлы из папки `chatgpt_sources`:

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

## Не обязательно загружать в Sources

```text
README.md
LICENSE
CONTRIBUTING.md
CHANGELOG.md
docs/
examples/
github_assets/
```

Эти файлы нужны для GitHub и объяснения проекта, но не обязательны для работы ChatGPT Project.

## Что вставлять в Project Instructions

```text
00_PROJECT_INSTRUCTIONS_PASTE_IN_CHATGPT.md
```

Его лучше не просто загружать, а именно вставить в инструкции проекта.

## Что пользователь должен редактировать

```text
02_USER_PLUGIN_PROFILE_TEMPLATE.md
```

Этот файл надо заполнить под конкретного пользователя.

Например:

```text
Primary DAW:
- Logic Pro

EQ:
- FabFilter Pro-Q 4
- Logic Channel EQ

Compression:
- Waves CLA-76
- Logic Compressor

Mastering:
- iZotope Ozone 12
- FabFilter Pro-L 2
```

## Минимальный набор файлов

Если есть лимит по количеству файлов, загрузи только:

```text
01_SOUND_ENGINEER_ROLE.md
02_USER_PLUGIN_PROFILE_TEMPLATE.md
03_OFFICIAL_MANUAL_SOURCES.md
04_SCREENSHOT_ANALYSIS_RULES.md
05_AUDIO_FILE_ANALYSIS_RULES.md
06_VOCAL_CHAIN_SYSTEM.md
07_MASTERING_CHAIN_SYSTEM.md
09_PLUGIN_STARTING_SETTINGS.md
10_RESPONSE_TEMPLATES.md
```

## Лучший вариант

Загружать все файлы из `chatgpt_sources`, кроме `00`, а `00` вставить в инструкции.
