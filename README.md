# DamenBrett
# Spiel Damen Java Projekt

/*
 das Spiel Solitär

- - x x x - - 
- - x x x - -
x x x x x x x
x x x - x x x
x x x x x x x
- - x x x - -
- - x x x - -

Ziel: Alle Figuren bis auf eine abräumen!
      Die letzte Figur bleibt idealerweise auf dem mittlren Feld übrig

Regeln:
    Zug: - Springen über eine einzelne Figur auf das freie Feld dahinter
         - Die übersprungene Figur wird entfernt

Nötige Klassen:
    Frame <- Fenster
    Panel <- Spielfeld
    Panel <- Feld (33) die 2x2 Felder in Ecken sind NICHT erlaubt
    Button <- Figur (32x)
        Oder: Mehr Aufwand, aber flexibler
        Component <- Figur (32x)
        MouseListener <- Schiedsrichter
    Zug
    Panel <- Statistik
        oder: Dialog <- Statistik
    Panel <- Steurung
        oder: MenuBar <- Steuerung
        

        Fenster
            Spielfeld
            Statistik
            Steuerung

        Spielfeld
            Feld[7][7]

        Statistikzeile
            Label
            TextField

        Statistik
            Statistikzeile[3]



Regeln
 */
package fiea_16_solitaer;

/**
 *
 * @author mmartinez
 */
public class Fiea_16_solitaer {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    }
    
}

