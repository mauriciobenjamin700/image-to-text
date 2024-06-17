# Convertendo Imagens com Texto em Apenas Texto

Um script básico para converter imagens com texto em apenas texto


## Passo 1: Instalar Tesseract

### No Windows
1. Baixe o instalador do Tesseract em [GitHub](https://github.com/UB-Mannheim/tesseract/wiki).
2. Instale o Tesseract e adicione o diretório `tesseract.exe` ao PATH do sistema.

### No macOS
```sh
brew install tesseract
```

### No Linux (Ubuntu)
```sh
sudo apt-get update
sudo apt-get install tesseract-ocr
```

## Passo 2: Instalar as Bibliotecas Python Necessárias

Você precisa instalar as bibliotecas `pytesseract` e `Pillow` para realizar a leitura de imagens e usar o Tesseract.

```sh
pip install pytesseract Pillow
```
