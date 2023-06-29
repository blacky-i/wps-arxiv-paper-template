# Репозиторий с шаблоном для препринта статьи

Основан на - https://github.com/kourgeorge/arxiv-style

Для уменьшения веса папки нужно создать на Яндекс.Диске публичную папку, заливать туда pdf статьи, дать полный доступ нескольким авторам и закачивать их туда.
Чтобы скачать на локальный компьютер, нужно поправить строчку `public_key = "https://disk.yandex.ru/d/__put_identifier_here__"`, указав идентификатор папки и можно использовать следующую команду в bash(Linux) или PowerShell(Windows):
```
python download_papers_from_yadisk.py
```

или скачивать самостоятельно по публичной ссылке и положить все статьи в папку `papers`.

`arxiv_template.dotx` - шаблонный файл со стилями и инструкциями как оформлять статью для WPS Office\MS Word.

---

# English

---

# Repository with a template for ArXiv preprint

Based on - https://github.com/kourgeorge/arxiv-style

To reduce the weight of the folder, you need to create a public folder on Yandex.Disk, give full access to several authors and upload citation articles there.
To download papers to the local computer, you need to correct the line `public_key =" https://disk.yandex.ru/d/__put_identifier_here__ "`, indicating the folder identifier and you can use the next command in Bash (Linux) or PowerShell (Windows):
```
python download_papers_from_yadisk.py
```

Or download via browser with public link and extract all articles to `papers` folder.

`arxiv_template.dotx` - a template file with styles and instructions How to write an article for WPS Office \ MS Word.