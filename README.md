# Simple Python Project

Dieses Repository enthält einfache Python-Funktionen und Tests, um Git, CI/CD und Code-Qualitäts-Checks mit `ruff` zu demonstrieren.

## Funktionen:
- `add_numbers(a, b)`: Addiert zwei Zahlen.
- `is_even(n)`: Überprüft, ob eine Zahl gerade ist.

## Einrichtung
1. Klone das Repository:
git clone https://github.com/sp111jessica/Homework-assignment-1..git

2. Installiere Abhängigkeiten:
pip install -r requirements.txt

3. Führe den Linter aus:
ruff main.py

4. Starte die Tests:
python -m unittest test_main.py

## Automatische Tests
GitHub Actions führt Tests bei jedem Push automatisch aus.
