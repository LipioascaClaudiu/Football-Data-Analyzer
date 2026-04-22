#Football Data Analyzer & Predictor
**Status:** *Work in Progress - Proiect de Licenta*

# Descriere
O platforma web completa pentru monitorizarea, analiza și predictia performantelor echipelor de fotbal. Aplicatia extrage date în timp real, antrenează modele de Machine Learning pe statistici istorice si ofera o interfată web interactivă pentru simularea meciurilor și vizualizarea rezultatelor.

# Tehnologii folosite
 *Backend & Logica ML:** Python, Flask, Scikit-learn, Pandas
 *Colectare date (Scraping):** BeautifulSoup / Selenium
 *Baza de date:** SQLite (`fotbal_app.db`)
 *Frontend:** HTML5, CSS3 (Integrare cu template-uri Flask)

# Functionalitati principale
   *Actualizare automata: ** Scripturi dedicate pentru extragerea si procesarea rezultatelor live.
   *Modul de Predictie:** Utilizarea Machine Learning pentru a genera predictii asupra scorurilor și rezultatelor finale.
   *Simulator de Meciuri:** Functionalitate interactiva ce permite compararea a două echipe.
   *Gestiunea Fazelor Eliminatorii:** Automatizarea extragerii datelor pentru fazele de tip knockout.

# Cum se ruleaza proiectul
1. Clonează acest repository: `git clone https://github.com/LipioascaClaudiu/Football-Data-Analyzer.git`
2. Asigura-te că ai Python instalat și instalează librariile necesare (Flask, Pandas, Scikit-learn etc.).
3. Porneste serverul ruland fisierul principal: `python app.py` (sau `main.py`).
4. Deschide browserul și acceseaza adresa afisata în terminal (de obicei `http://127.0.0.1:5000`).
