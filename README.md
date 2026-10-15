# PSU – laboratorijske vježbe (LV1–LV9)

Rješenja laboratorijskih vježbi iz strojnog učenja i obrade podataka u Pythonu,
izrađena tijekom studija računarstva na FERIT-u u Osijeku.

## Sadržaj

| Vježba | Tema | Alati |
|--------|------|-------|
| LV1 | Osnove Pythona: petlje, funkcije, rječnici, obrada tekstualnih datoteka (brojanje riječi, analiza SMS spam/ham poruka) | Python |
| LV2 | Zadaci iz osnova programiranja | Python |
| LV4 | Linearna regresija: aproksimacija šumovite funkcije i predviđanje cijene automobila | pandas, scikit-learn, matplotlib, seaborn |
| LV5 | Klasifikacija: logistička regresija i vrednovanje modela, procjena zauzetosti prostorije iz senzora temperature i CO2 | pandas, scikit-learn |
| LV6 | Grupiranje podataka (K-means) i kvantizacija boja slike | scikit-learn, matplotlib |
| LV7 | Neuronska mreža (Dense) za prepoznavanje rukom pisanih znamenki, skup MNIST | TensorFlow / Keras |
| LV8 | Konvolucijska neuronska mreža (CNN) na MNIST-u, TensorBoard, ModelCheckpoint, matrica zabune, predikcija na vlastitoj slici | TensorFlow / Keras |
| LV9 | CNN za klasifikaciju prometnih znakova (43 klase), Dropout, matrica zabune, predikcija na vlastitoj slici | TensorFlow / Keras |

## Pokretanje

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scikit-image tensorflow
python LV8/LV8Zad1.py
```

## Napomene

- Vježbe su rješavane na temelju zadanih predložaka (TODO komentari) i uputa u PDF-ovima u svakoj mapi.
- Skup slika za LV9 (`dataset/Train`, `dataset/Test`) nije uključen u repozitorij zbog veličine.
- Neke skripte imaju putanje do datoteka postavljene za računala na fakultetu pa ih je potrebno prilagoditi.
