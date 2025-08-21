# Название

gui_for_fast_document_processing

***


# Описание

Позволяет вводить данные, необходимые для заполнения документа, в графический интерфейс и создавать документ на основе этих данных.

***


# Установка

## Для обычного запуска

```
git clone https://github.com/limaximy/gui_for_fast_document_processing.git
cd gui_for_fast_document_processing

launch.bat
```

## Для редактирования проекта

```
git clone https://github.com/limaximy/gui_for_fast_document_processing.git
cd gui_for_fast_document_processing

python -m venv venv  # создание виртуального окружения
source venv/bin/activate  # запуск venv на Linux / macOS
venv\Scripts\activate  # запуск venv на Windows
pip install -r requirements.txt  # установка требуемых зависимостей

cd files_python
python main.py
```

***


# Использование

Для запуска требуется запустить `launch.bat`. Внутри проекта уже есть интерпретатор, поэтому можно запустить этот проект на компьютере без установленного Python.

Чтобы сгенерировать документ, в проекте нужно создать папку `_sample_docx` и поместить туда шаблоны ФЛ и ЮЛ арестов с названиями файлов `ФЛ (ИП)_Принимаем арест_ФССП.docx` и `ЮЛ_Принимаем арест_ ФССП.docx`. 

***
