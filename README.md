# 🎮 Echo Hunt

Un joc horror/exploration realizat în **Python + Pygame**, bazat pe un sistem de **sonar** și raycasting pseudo-3D.  
Jucătorul este orbit și trebuie să navigheze prin întuneric folosind unde sonore pentru a descoperi mediul, cheia și ieșirea.

---

# 📌 Descriere

**Echo Hunt** este un joc first-person inspirat de stilul clasic raycasting (Wolfenstein 3D), unde vizibilitatea nu este permanentă.

Lumea este complet întunecată, iar jucătorul poate „vedea” doar atunci când trimite un puls sonar care luminează temporar pereții și obiectele din jur.

## 🎯 Scopul jocului
1. Găsește cheia ascunsă pe hartă.
2. Descoperă ieșirea.
3. Supraviețuiește întunericului.

---

# 🧠 Funcționalități principale

## 🌌 Sistem Sonar
- Pulsurile sonar luminează temporar mediul.
- Vizibilitatea dispare gradual.
- Cooldown între utilizări.

## 🧱 Raycasting 3D
- Render pseudo-3D realizat manual.
- Pereți și obiecte proiectate folosind raze.

## 🗺️ Hartă interactivă
Elemente disponibile:
- Pereți
- Coloane
- Copaci
- Tufișuri
- Cheie
- Ieșire

## 🧭 Busolă inteligentă
- Indică direcția către cheie.
- Funcționează doar când sonarul este activ.

## 🌡️ Sistem „Hot / Cold”
După obținerea cheii:
- jocul indică apropierea față de ieșire.

## 🔊 Sunete și efecte
- Sonar
- Ridicare cheie
- Deschidere ușă
- Victorie / înfrângere

## 🖱️ Control cu mouse + tastatură
- Mișcare fluidă
- Rotire cu mouse-ul
- Strafing

---

# 🕹️ Controale

| Tastă | Acțiune |
|---|---|
| W / S | Mers înainte / înapoi |
| A / D | Mișcare laterală |
| Mouse | Rotire cameră |
| SPACE | Activează sonarul |
| ENTER | Start joc |
| R | Restart |
| ESC | Ieșire |

---

# ⚙️ Cerințe

- Python 3.x
- Pygame

## Instalare

```bash
pip install pygame
