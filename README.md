
## Task 1


```bash
  python wiki_extractor.py --keyword= "Topic name" --num_urls= 100
  --output= "output.json"
```

## Task 2

#### Install Poppler on Windows
Go to - https://github.com/oschwartz10612/poppler-windows/releases/

Specifying poppler path in code
```bash
pages = convert_from_path(filepath, poppler_path=r"actualpoppler_path")
```

#### Install Tesseract on Windows 
Go to - https://github.com/UB-Mannheim/tesseract/wiki

Specifying Tesseract path in code before call image_to_string function
```bash
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'

```

#### Install other Languages in Tesseract 
Go to - https://github.com/tesseract-ocr/tessdata/ 

Download the .traineddata file and place it in
C:\\Program Files\\Tesseract-OCR\\tessdata

For more info visit on - https://ocrmypdf.readthedocs.io/en/latest/languages.html

Specifying language in pytesseract

```bash
text = pytesseract.image_to_string(file,lang='mar')
```

#### Install these librabries
```bash
  pip install pytesseract
  pip install pdf2image
  pip install openpyxl # for excel files
  pip install python-poppler
```
    
