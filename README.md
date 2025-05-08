# khajiit-has-houses
_"Travelers of Skyrim, welcome. Khajiit offers fine homes in every hold. Safe, clean, and free of skeevers... mostly."_

🐾 Khajiit Has Houses is a Python-based hotel (or house) reservation system inspired by the world of Skyrim. Built using Object-Oriented Programming and the Flet library for a modern graphical interface, this project simulates a house rental service run by enterprising Khajiit across the province.

## 📌 Features

- Manage guests (hóspedes)
- Manage Skyrim houses (quartos)
- Create, view, and cancel reservations
- Track house availability
- Skyrim map & lore-based UI elements *(coming soon)*

## 🧱 Project Structure

### Main Classes

- `Hospede`: Stores client data
- `Casa`: Represents a house (name, city, price, type, availability)
- `Reserva`: Reservation contract (house, guest, dates)
- `GuildaCorretores`: Manages reservations and availability

### Technologies

- **Language**: Python
- **GUI**: Flet
- **Architecture**: OOP
- **Persistence**: In-memory (for now)

## 🎮 Skyrim Houses Included

| House             | Town       | Type     | Price per day    |
|-------------------|------------|----------|------------------|
| Breezehome        | Whiterun   | Padrão   | 100              |
| Hjerim            | Windhelm   | Luxo     | 250              |
| Proudspire Manor  | Solitude   | Luxo     | 300              |
| Vlindrel Hall     | Markarth   | Rústico  | 180              |
| Honeyside         | Riften     | Padrão   | 150              |
| Severin Manor     | Raven Rock | Especial | 0 (quest house)  |

## 🔮 Future Plans

- 📍 Interactive map of Skyrim with clickable locations
- 🧙 Lore-based tooltips for houses
- ☁️ Save/load system (JSON or database)
- 🎨 Themed UI with Elder Scrolls visuals

---

## 📅 Development Time Tracker

| Day | Date       | Task Summary                             | Time Spent | Done |
|-----|------------|-------------------------------------------|------------|------|
| 1   | 2025-05-08 | Project planning, repo setup, README prep | `~2h`      | ✅   |
| 2   | YYYY-MM-DD | Class creation & structure                | `--`       | ⬜    |
| 3   | YYYY-MM-DD | Sample data, house list, testing logic    | `--`       | ⬜    |
| 4   | YYYY-MM-DD | Basic UI: house list + buttons            | `--`       | ⬜    |
| 5   | YYYY-MM-DD | Client management screen                  | `--`       | ⬜    |
| 6   | YYYY-MM-DD | Reservation system + date handling        | `--`       | ⬜    |
| 7   | YYYY-MM-DD | Reservation view, cancel, polish          | `--`       | ⬜    |

---

## ✅ Progress Checklist

- [x] Repository created
- [x] README written (title, description, theme)
- [ ] Classes implemented
- [ ] GUI layout built
- [ ] Data integration (houses + guests)
- [ ] Full reservation system working
- [ ] Project tested and delivered

---

> Made with 🧠, 🐾, and a bit of skooma.
