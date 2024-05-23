# Bokförings Cheat Sheet för Frilansande IT-konsult (AB)

## Innehåll
- [Månadsavstämning](#månadsavstämning)
- [Vanliga Bokföringar](#vanliga-bokföringar)
  - [Kostnader](#kostnader)
  - [Inkomster](#inkomster)

## Månadsavstämning
Följ dessa steg vid varje månadsslut för att säkerställa korrekt bokföring:
1. **Bokföring av samma månads skatter/avgifter som skuld:**
   - Skulder för skatter och avgifter bokförs automatiskt.
2. **Bokföring av skatter/avgifter från föregående månad:**
   - Bokför genom dokument som laddats upp automatiskt. Försök koppla dokumentet till den relevanta transaktionen.
3. **Bokföring av moms från två månader tidigare:**
   - Koppla momsbokföringen till momsrapporten och den relevanta transaktionen.
4. **Bokför eventuella inkommande betalningar av fakturor:**
   - Bokför inkommande betalningar och säkerställ att kundfordran bokförs automatiskt.
5. **Stäm av skattekontot för eventuella räntebetalningar:**
   - Kontrollera och bokför eventuella räntebetalningar på skattekontot.
6. **Stäm av bankkontot:**
   - Kontrollera att 1930 för sista datumet i månaden matchar kontoutdraget

## Vanliga Bokföringar

### Kostnader
#### Inköp av mjukvara (inom EU)
| Konto                             | Debet  | Kredit |
| --------------------------------- | ------ | ------ |
| 1930 Företagskonto/checkkonto     |        | X - M  |
| 2641 Ingående moms                |        | M      |
| 6500 Övriga externa tjänster      | X      |        |

#### Inköp av mjukvara (utanför EU)
| Konto                             | Debet  | Kredit |
| --------------------------------- | ------ | ------ |
| 1930 Företagskonto/checkkonto     |        | X      |
| 6500 Övriga externa tjänster      | X      |        |

#### Friskvård
| Konto                             | Debet   | Kredit |
| --------------------------------- | ------- | ------ |
| 1930 Företagskonto/checkkonto     | 0       | X      |
| 2640 Ingående moms                | M       | 0      |
| 7690 Övriga personalkostnader     | X - M   | 0      |
#### Fika
| Konto                             | Debet  | Kredit |
| --------------------------------- | ------ | ------ |
| 1930 Företagskonto/checkkonto     | 0      | X      |
| 2640 Ingående moms                | M      | 0      |
| 7690 Övriga personalkostnader     | X - M  | 0      |

### Inkomster
#### Skattefri ränte-intäkter (skattekontot)
| Konto          | Debet  | Kredit |
| -------------- | ------ | ------ |
| 1630 Avräkning för skatter och avgifter |  X | |
| 8314 - Skattefria ränteintäkter | | X |
