# Image Folder & Photo Naming Guide

Welcome to **Diwali Fireworks 2026**!

The website is designed to automatically load product images from the local `image` (or `Image`) folder based on exact product filenames.

---

## Folder Structure

Place your product photos inside the `image/` directory located in the same folder as `index.html`:

```text
Fireworks/
├── index.html
├── IMAGE_NAMING_GUIDE.md
└── image/
    ├── 1000 Chatar patar RS 200.jpg
    ├── 12 Shot RS 270.jpg
    ├── 2 Sound Rocket Big Rs 250.jpg
    ├── 2 Sound Rocket Rs 300.jpg
    ├── 288 Chinesse Shot RS 1200.jpg
    ├── 30 Shot RS 700.jpg
    ├── Asharfi Heavy Mitti Anar RS 500.jpg
    ├── Ashoka Small Chakkar RS 150.jpg
    ├── Big Fulljari RS600.jpg
    └── ... (see full list below)
```

---

## Expected Filenames List

Here is the exact list of product filenames expected inside the `image/` directory:

### 1. Sparklers (Fulljari)
- `Big Fulljari RS600.jpg`
- `Gudiya 60cm Fulljari RS 300.jpg`
- `Pogo 18cm Fulljari RS 70.jpg`
- `Pogo 35cm Fulljari RS 90.jpg`
- `Coronation pencil silver tourches Rs200  pack.jpg`
- `Darbar Pencil RS 250 Box.jpg`

### 2. Ground Chakkar
- `Ashoka Small Chakkar RS 150.jpg`
- `Coronation Nazi Original RS 290.jpg`
- `Smallest Chakkar RS100.jpg`
- `Special Big Deluxe Chakkar RS 350.jpg`

### 3. Anar (Flower Pots)
- `Asharfi Heavy Mitti Anar RS 500.jpg`
- `Colour pinjor 5colour Flower pot RS450.jpg`
- `Coronation Asoka Flower pot RS 270.jpg`
- `Gudiya Tum Tim Mitti Anar RS 400.jpg`
- `Super gaint Flower pot RS 350.jpg`

### 4. Rockets
- `2 Sound Rocket Big Rs 250.jpg`
- `2 Sound Rocket Rs 300.jpg`

### 5. Sound Crackers
- `1000 Chatar patar RS 200.jpg`
- `Balaji Clasic Original RS 250.jpg`
- `Chota chatar patar Rs160.jpg`
- `Coronation Bijali RS 70.jpg`
- `Dil Dil hunter 65 per piece.jpg`
- `Dragon Fight Chatar patar RS 150.jpg`
- `Ladhi 1000 RS 450.jpg`
- `Ladhi 2000 RS 850.jpg`
- `Ladhi 5000 RS 2600.jpg`
- `Matches Bomb RS 150 per Box.jpg`
- `Mini Bullet Heavy Volume RS 70.jpg`
- `Mini Hydro Bomb RS 80.jpg`
- `Murga Chaap Chota RS 30.jpg`
- `Ravan Bomb Rs 200.jpg`

### 6. Sky Shots
- `12 Shot RS 270.jpg`
- `288 Chinesse Shot RS 1200.jpg`
- `30 Shot RS 700.jpg`
- `3in1 pcs Big Single Shot RS 700.jpg`
- `7 Single Shot RS 500.jpg`
- `SDS 60 Shot RS 1300.jpg`
- `Single Shot 3in1 PCS RS 450.jpg`
- `Symphony 25 Shot RS650.jpg`

### 7. Fountains
- `Penta 5 Avtaar 5 pcs RS 270.jpg`
- `Special 555 Timing Flash RS 330.jpg`

### 8. Kids Special
- `Coronation Butterfly RS 400.jpg`
- `Pop Pop Rs 380 per box.jpg`

---

## Automatic Fallback & Placeholder System

If a photo is missing or fails to load:
1. The website will automatically attempt to load from both `Image/` and `image/` folders.
2. If no photo is found in the local folder, the site automatically renders a **festive SVG vector art card** customized with the product category icon and title!
3. Store managers can also open the **"View Image Naming Instructions"** modal anytime directly from the website's "How to Order" section.
