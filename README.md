# Tic-Tac-Toe

O implementare clasică a jocului X și 0 (Tic-Tac-Toe), dezvoltată în C# folosind Windows Forms. Proiectul propune o abordare curată, generând grila de joc dinamic direct din cod, oferind astfel o interfață simplă și fluidă.

## Funcționalități
* **Generare dinamică:** Tabla de joc (3x3) este construită programatic la inițializarea ferestrei, evitând aglomerarea designer-ului vizual.
* **Validarea mutărilor:** Previne suprascrierea unei celule deja ocupate.
* **Sistem de ture:** Alternează automat între jucătorul X (albastru) și jucătorul O (roșu).
* **Detecție final de joc:** Algoritm integrat care verifică instantaneu condițiile de victorie pe linii, coloane și diagonale, recunoscând totodată și situațiile de remiză.
* **Resetare automată:** Odată ce un meci se încheie, tabla este curățată instantaneu și pregătită pentru o nouă rundă.

## Tehnologii utilizate
* **Limbaj:** C#
* **Framework:** .NET Framework 4.6.1
* **Mediu de dezvoltare:** Visual Studio

## Structura proiectului
Aplicația este structurată sub forma unui proiect standard Windows Forms (`WindowsFormsApp4`), logica principală și instanțierea interfeței regăsindu-se în fișierul `Form1.cs`.

## Cum se rulează
1. Clonează acest repository local:
   ```bash
   git clone [https://github.com/radu-stefanescu/Tic-Tac-Toe.git](https://github.com/radu-stefanescu/Tic-Tac-Toe.git)
