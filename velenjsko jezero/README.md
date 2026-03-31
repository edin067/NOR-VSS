 # Velenjsko Jezero VR - Uputstvo za pokretanje

Ovaj projekat koristi **A-Frame** za virtuelnu stvarnost. Zbog sigurnosnih ograničenja veb pregledača (CORS), projekat **neće raditi** ako se `index.html` samo otvori direktno iz foldera. Mora se pokrenuti preko lokalnog servera.

## Kako pokrenuti projekat:

### Opcija 1: Koristeći Node.js (Preporučeno)
Ako imate instaliran Node.js, uradite sledeće u terminalu unutar ovog foldera:
```bash
npm start
```
Zatim otvorite: [http://localhost:3001](http://localhost:3001)

### Opcija 2: Koristeći Python
Ako imate Python, pokrenite sledeću komandu:
```bash
# Za Python 3
python -m http.server 3001
```
Zatim otvorite: [http://localhost:3001](http://localhost:3001)

### Opcija 3: VS Code "Live Server"
Ako koristite VS Code, možete instalirati ekstenziju **Live Server** i kliknuti na dugme **"Go Live"** u donjem desnom uglu.

---
**Napomena:** Projekat je optimizovan za rad na portu **3001**.
