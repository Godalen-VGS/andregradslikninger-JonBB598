[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/xFdhwFtR)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16297325&assignment_repo_type=AssignmentRepo)
# Løsninger til andregradslikninger
## Oppgave:
Du skal nå lage en funksjon kalt ```losninger``` som skal ha tre parametre: a, b og c.
Funksjonen skal fungere slik at man putter inn argumenter for a, b og c som skal svare til verdien i en andregradslikning på forman: ax^2+bx+c=0.
Funksjonen skal deretter returnere antall løsninger til andregradslikningen.
Funksjonen skal altså se slik ut, så du skal ikke endre navnet eller parameterne til funksjonen:
```Python
losninger(a, b, c)
```

Ta utgangspunkt i programmet som er laget i python-filen "andregradslikning.py" og utvid programmet slik at det klarer denne oppgaven.

### Kriterier for å få til oppgaven:
1. Om likningen ikke har noen løsning skal den returnere "Likningen har ingen løsning!".
2. Om likningen kun har en løsning skal den returnere den ene løsningen som en avrundet float med 2 desimaler
3. Om likningen har to løsninger skal den returnere begge løsningene slik: (losning1, losning2) der begge verdiene skal være avrundet til 2 desimaler.

Eks:
   ```Python
def losninger(a, b, c):
  #Kode her
  #Hvis ingen løsning:
    return "Likningen har ingen løsning!"
  #Hvis kun en løsning:
    return losning1 #Et flyttall avrundet til to desimaler.
  #Hvis to løsninger:
    return (losning1, losning2) En tuppel med to flyttall som begge er avrundet til to desimaler.
   ```
