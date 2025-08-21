# Name

gui_for_fast_document_processing

***


# Description

Allows you to enter the data necessary to fill out the document into the graphical interface and create a document based on this data.

***


# Installation

## For normal startup

```
git clone https://github.com/limaximy/gui_for_fast_document_processing.git
cd gui_for_fast_document_processing

launch.bat
```

## To edit the project

```
git clone https://github.com/limaximy/gui_for_fast_document_processing.git
cd gui_for_fast_document_processing

python -m venv venv  # creating a virtual environment
source venv/bin/activate  # running venv on Linux / macOS
venv\Scripts\activate  # running venv on Windows
pip install -r requirements.txt  # install required dependencies
```

***


# Usage

To launch, you need to run `launch.bat`. There is already an interpreter inside the project, so you can run this project on a computer without Python installed.

To generate a document, you need to create a folder `_sample_docx` in the project and place there the templates of FL and legal arrests with the names of the files `ФЛ (ИП)_Принимаем арест_ФССП.docx` and `ЮЛ_Принимаем арест_ ФССП.docx`. 

***