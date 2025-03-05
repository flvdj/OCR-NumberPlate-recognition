# Detectare și Recunoaștere a Plăcuțelor de Înmatriculare dintr-un Video în Timp Real

## Descriere
Acest proiect Python implementează un sistem de detectare și recunoaștere a plăcuțelor de înmatriculare dintr-un videoclip în timp real. Folosind tehnici de procesare a imaginilor și recunoaștere optică a caracterelor (OCR), programul izolează plăcuța de restul obiectelor din imagine și extrage numărul de înmatriculare conform unui șablon impus.

## Tehnologii utilizate
- **Python** - Limbaj principal de programare.
- **OpenCV (cv2)** - Bibliotecă pentru procesarea imaginilor și detecția obiectelor.
- **Tesseract-OCR** - Tehnologie OCR pentru recunoașterea textului de pe plăcuțe.
- **Tkinter** - Interfață grafică pentru selectarea fișierelor video și a documentelor Excel.
- **Pandas** - Manipularea și exportarea datelor detectate în fișiere Excel.
- **BeamNG.drive** - Simulator auto folosit pentru generarea scenariilor de testare.

## Funcționalități implementate
1. **Interfață grafică simplă** pentru selectarea fișierului video și a locației de salvare a rezultatelor.
2. **Detectarea plăcuțelor de înmatriculare** folosind clasificatori Haar Cascade.
3. **Recunoașterea caracterelor** cu ajutorul Tesseract-OCR.
4. **Filtrare pentru a evita duplicatele**, asigurând afișarea unică a fiecărui număr detectat.
5. **Exportarea datelor** într-un fișier Excel pentru analiză ulterioară.
6. **Posibilitatea de oprire prematură a programului** prin apăsarea tastei „q”.

## Instalare și utilizare
1. **Clonați repository-ul** în local:
   ```bash
   git clone https://github.com/username/repository.git
   ```
2. **Instalați dependințele necesare**:
   ```bash
   pip install opencv-python pandas pytesseract tkinter
   ```
3. **Descărcați și configurați Tesseract-OCR**:
   - Descărcați de la: [Tesseract-OCR](https://sourceforge.net/projects/tesseract-ocr.mirror/)
   - Configurați calea către executabil în codul Python.
4. **Rulați scriptul principal**:
   ```bash
   python main.py
   ```
5. **Selectați fișierul video** și **locația de salvare a datelor** prin interfața grafică.

## Capturi de ecran
*(Includeți imagini cu interfața utilizatorului și exemple de plăcuțe detectate.)*

## Autori
- **Studenți:** Marinescu Silviu-Andrei, Baroiu Silvian, Nistor Flaviu-Cristian
- **Grupa:** 422B

## Licență
Acest proiect a fost realizat în cadrul Universității Naționale de Știință și Tehnologie Politehnica din București, Facultatea de Electronică, Telecomunicații și Tehnologia Informației, 2023.

