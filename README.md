# workshop readme

## NDR Hamburg Seminar

### This repository was made for the git workshop

#### Dieses Repository wurde für den Git-Workshop erstellt

##### Deze repository is gemaakt voor de git-workshop

####### Ce référentiel a été créé pour l'atelier git

[Über folgenden Link lässt sich die Repository aufrufen](https://github.com/SoFarAway64/workshop)

### 5 Vorteile von git

+ Verteilte Versionskontrolle (Jeder hat eine Kopie des repositorys)
+ Bessere/Effizientere Zusammenarbeit
+ Änderungen sind nachvollziehbarer 
+ Branching und Merging 
+ Geschwindigkeit, Effizienz und Perfomance

Hier ein Java Programm zur Berechnung von Monatstagen
===================================================== 

```javascript
import java.util.Scanner;

public class A44_Kalender {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Monatseingabe
        System.out.print("Wie lautet der Monat (1-12): ");
        int month = scanner.nextInt();
        
        int days;

        // Bestimmung der Tage
        switch (month) {
            case 1: // Januar
            case 3: // März
            case 5: // Mai
            case 7: // Juli
            case 8: // August
            case 10: // Oktober
            case 12: // Dezember
                days = 31;
                break;
            case 4: // April
            case 6: // Juni
            case 9: // September
            case 11: // November
                days = 30;
                break;
            case 2: // Februar
                days = 28; // Kein Schaltjahr! 
                break;
            default:
                System.out.println("Ungültige Eingabe. Bitte geben Sie eine Zahl zwischen 1 und 12 ein.");
                return; // Programm beenden
        }

        // Ausgabe
        System.out.println("Der Monat " + month + " hat " + days + " Tage.");
    }
}
```

Hier ein Foto der Backrooms 
===========================

![alt text](https://github.com/SoFarAway64/workshop/blob/main/Backrooms_model.jpg "Nett hier.")

Einkaufsliste
-------------
* 12 Liter Orangensaft
* 30 Orangen
* 4 Packung Instanttee (Orangengeschmack)
* Orangenaroma
* 2 Packungen Himbeereis
* 4 Dosen Felgenreiniger