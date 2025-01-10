# Bachelorproef - Feature Selectie voor het Expected Goals Model

Auteur: **Dolunay Alkan**

## Overzicht
Deze repository bevat de scripts en resultaten van mijn bachelorproef waarin verschillende feature-selectie methoden worden onderzocht en geëvalueerd voor het verbeteren van het Expected Goals (xG) model. De experimenten zijn uitgevoerd met de open-source library [soccer_xg](https://github.com/ML-KULeuven/soccer_xg/tree/master).

Het onderzoek omvat methodes zoals L1/L2 regularisatie, Chi-Square Test, Forward Feature Selection, Convolutional Neural Networks (CNN), en Recurrent Neural Networks (RNN).

---

## Structuur van de Map
Hieronder volgt een overzicht van de mappenstructuur en de bijbehorende bestanden:

### **`BP_resultaten`**
Bevat alle gegenereerde resultaten en scripts. Submappen bevatten de outputs en scripts voor elke methode.

#### **Submappen**
- **`Chi_square_resultaten`**  
  Bevat de resultaten en analyses van de Chi-Square Test experimenten.

- **`Cnn_resultaten`**  
  Bevat de resultaten en analyses van de CNN-gebaseerde feature selectie.

- **`FFS_resultaten`**  
  Bevat de resultaten en analyses van de Forward Feature Selection experimenten.

- **`RNN_test_resultaten`**  
  Bevat de resultaten en analyses van de RNN-gebaseerde feature selectie.

### **Jupyter Notebooks**
De scripts in de root-directory voeren verschillende experimenten uit:
- **`1-feature-selection-l1-l2.ipynb`**
  - Bevat de implementatie en evaluatie van het basismodel met L1- en L2-regularisatie.
- **`2-feature-selection-ChiSquareTest.ipynb`**
  - Voert Chi-Square Tests uit en selecteert features op basis van deze test.
- **`3-feature-selection-ForwardFeatureSelection`**  
  - Variaties zoals `neg_brier`, `accuracy`, `recall`, en `precision` meten verschillende metrieken voor Forward Feature Selection.
- **`4-feature-selection-CNN.ipynb`**
  - Script voor CNN-gebaseerde feature selectie.
- **`5-feature-selection-RNN.ipynb`**
  - Script voor RNN-gebaseerde feature selectie, inclusief architectuurvarianten zoals GRU + Conv1D en Attention.

---

## Installatie en Gebruik
Volg de stappen hieronder om de experimenten te reproduceren:

1. **Clone de Open-Source Library**
   Clone de repository van [soccer_xg](https://github.com/ML-KULeuven/soccer_xg/tree/master):
   ```bash
   git clone https://github.com/ML-KULeuven/soccer_xg.git
   cd soccer_xg
    ```
2. Plaats de Bestanden Kopieer de bestanden uit deze repository naar de root-folder van `soccer_xg`
3. Volg de installatie handleiding van `soccer_xg` om de library ten werke te krijgen. Dit zal er ook voor zorgen dat de beschikbare notebooks van deze repository zullen werken.

## Opmerking 
Dit project is ontwikkeld als onderdeel van mijn bachelorproef en weerspiegelt mijn onderzoek naar feature-selectiemethoden binnen een voetbalanalyse-context.

Voor vragen of feedback kun je contact opnemen met Dolunay Alkan.
