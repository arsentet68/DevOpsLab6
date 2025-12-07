# ФИТ-2024 НМ. Полынский Арсений. DevOps. ЛР6
# Часть1
## Создаём структуру (папки и файлы)

<img width="351" height="191" alt="image" src="https://github.com/user-attachments/assets/a58e1207-d8a2-45c9-b857-d7ddee4185b5" />


## Файлы
- tasks/main.yml - основоной плейбук с задачами
- handler/main.yml - handler для перезапуска nginx
- site.conf.j2 - шаблон конфига сайта
- index.conf.j2 - шаблон страницы сайта

## Проверка

<img width="648" height="240" alt="image" src="https://github.com/user-attachments/assets/68f44f9d-4185-43df-8815-a993a493e660" />

# Часть2

## Создаём репозиторий, проверяем связь с гитом и клонируем

После создания нового репозитория, скопируем его

```
git clone https://github.com/arsentet68/DevOpsLab6.git
```

## Создаём два файла скриптов в папке github/workflows и проверяем их работу
- devops_course_pipeline.yml - "тестовый" сценарий
<img width="563" height="504" alt="image" src="https://github.com/user-attachments/assets/db55a9cf-57ab-4baf-abc5-c78330c62e51" />
Проверим работу сценария в Github Actions
<img width="1674" height="555" alt="image" src="https://github.com/user-attachments/assets/99b233d5-a053-40cd-8170-3137671cec70" />

- lint.yml - "боевой" сценарий
<img width="531" height="377" alt="image" src="https://github.com/user-attachments/assets/ae40deb9-2e3d-4597-8a56-2854d59c7c70" />

Проверим работу сценария в Github Actions
<img width="1322" height="574" alt="image" src="https://github.com/user-attachments/assets/6950adc2-1c5f-4bbb-b073-a9f8368eb2d0" />


