# 📱 Serwis Telefonów Wojtka

**Profesjonalna strona serwisu telefonów komórkowych - wszystkie marki!**

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://peblo13.github.io/wojtekserwis/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=white)](https://wa.me/48793924622)
[![Phone](https://img.shields.io/badge/Telefon-793--924--622-blue)](tel:793924622)

## 🌟 Funkcje

### ✨ Efekty wizualne:
- **Animowane tło** - wirujące gradienty w kolorach cyberpunk (neon blue/pink/gold)
- **50 pływających cząsteczek** - dynamiczne kropki w 6 kolorach
- **Glow animations** - świecące nagłówki i przyciski
- **Hover effects** - wszystkie karty reagują na najechanie myszką
- **Responsywny design** - działa na telefonach i komputerach

### 📱 Usługi serwisowe:
1. **Wymiana Ekranu** - LCD/AMOLED (od 150 zł)
2. **Wymiana Baterii** - z gwarancją (od 80 zł)
3. **Naprawa Płyty Głównej** - mikrospawanie, reballing (od 200 zł)
4. **Wymiana Gniazda Ładowania** - USB-C, Lightning (od 100 zł)
5. **Zalanie Telefonu** - czyszczenie, ratowanie danych (od 150 zł)
6. **Odblokowanie Simlock** - iPhone, Android (od 50 zł)
7. **Wymiana Aparatu** - kamery tylne/przednie (od 120 zł)
8. **Naprawa Głośnika** - czysty dźwięk (od 90 zł)
9. **Montaż Szkła** - hartowane 9H (od 30 zł)

### 🔧 Marki telefonów:
- 🍎 **iPhone** - wszystkie modele
- 📱 **Samsung** - Galaxy, Note, A-series
- 🔷 **Huawei** - P, Mate, Nova
- ⚡ **Xiaomi** - Redmi, Mi, Poco
- 🎯 **Oppo, Realme, OnePlus**
- 📲 **Motorola, Sony, LG**
- **I wszystkie inne marki!**

### 💬 Kontakt:
- **📞 Telefon:** [793-924-622](tel:793924622)
- **💚 WhatsApp:** [Napisz teraz](https://wa.me/48793924622?text=Witam!%20Chciałbym%20zapytać%20o%20naprawę%20telefonu)
- **💬 SMS:** [Wyślij SMS](sms:793924622)
- **📋 Formularz WhatsApp** - automatyczne wysyłanie zgłoszenia

## 🚀 Technologie

- **HTML5** - semantyczny markup
- **CSS3** - animations, gradients, backdrop-filter
- **JavaScript** - WhatsApp integration, smooth scroll
- **Font Awesome 6.4** - ikony
- **100% Vanilla** - bez frameworków, szybkie ładowanie!

## 📦 Instalacja

### Lokalnie (development):
```bash
# Sklonuj repozytorium
git clone https://github.com/peblo13/wojtekserwis.git

# Przejdź do katalogu
cd wojtekserwis

# Uruchom serwer (Python)
python -m http.server 8085
```

Otwórz: http://localhost:8085

### Deploy na GitHub Pages:
Strona automatycznie dostępna pod:
👉 **https://peblo13.github.io/wojtekserwis/**

### Wgrywanie na hosting:
```bash
# FTP/SFTP
Wgraj plik index.html do katalogu public_html/

# cPanel File Manager
Upload → wybierz index.html
```

## 🎨 Customizacja

### Zmiana numeru telefonu:
Znajdź i zamień `793924622` na swój numer w pliku `index.html`:
- Linia 84: Header button
- Linia 91: WhatsApp button
- Linia 239: Contact cards
- Linia 295: WhatsApp form handler
- Linia 652: Footer

### Zmiana kolorów:
W sekcji `:root` (linia 18):
```css
:root {
    --primary: #00D9FF;    /* Niebieski neon */
    --secondary: #FF00F5;   /* Różowy neon */
    --accent: #FFD700;      /* Złoty */
}
```

### Zmiana cen usług:
Edytuj `.service-price` w kartach usług (linie 150-230)

## 📱 WhatsApp Integration

Formularz automatycznie formatuje wiadomość:
```
*Nowe zgłoszenie serwisowe*

👤 *Imię:* [nazwa]
📱 *Telefon:* [numer]
📲 *Marka:* [marka]
📦 *Model:* [model]
⚠️ *Problem:* [opis]
```

I otwiera WhatsApp z gotową wiadomością!

## 🌐 SEO

Strona zawiera:
- Meta description
- Mobile-friendly viewport
- Semantic HTML5
- Fast loading (bez external dependencies oprócz Font Awesome)

## 📊 Performance

- ⚡ **Ładowanie:** < 1s
- 📦 **Rozmiar:** ~30 KB (HTML + CSS + JS)
- 🎨 **Animacje:** 60 FPS (GPU accelerated)
- 📱 **Responsywność:** 320px - 4K

## 🔮 Przyszłe funkcje

- [ ] Blog z poradami naprawy
- [ ] Galeria zdjęć napraw
- [ ] Cennik online
- [ ] System rezerwacji terminów
- [ ] Panel klienta (śledzenie naprawy)
- [ ] Multi-language (EN/PL)

## 📄 Licencja

MIT License - możesz używać, modyfikować i dystrybuować.

## 👨‍💻 Autor

Stworzone dla **Wojtka** - Serwis Telefonów

**Kontakt:**
- 📞 Tel: 793-924-622
- 💬 WhatsApp: [Napisz](https://wa.me/48793924622)

---

**Zbudowane z ❤️ i ☕**

Jeśli podoba Ci się projekt - daj ⭐!
