<h1 align="center">Le French</h1>
<h3 align="center">Auto-complétion pour du pseudo-code</h3>

<p align="center">Faciliter la rédaction de pseudo-code dans des documents textes <code>.txt</code>, cette extension couvre une multitude de raccourcis (cf <a href="#-raccourcis-principaux">Raccourcis principaux</a>)</p>

<h2 id="Raccourcis"> Raccourcis principaux</h2>

- ### Corps d'un algorithme
    ```
    ALGORITHME nom_algo
    // déclaration des types
    // déclaration des prototypes des fonctions
    LEXIQUE

    DÉBUT

    FIN
    ```
- ### Écrire un message
    ```
    Écrire("")
    ```
- ### Lire un message
    ```
    Lire()
    ```

## Conditions
- ### Si Alors
    ```
    Si condition Alors

    FinSi
    ```
- ### Si Alors Sinon
    ```
    Si condition Alors

    Sinon
        
    FinSi
    ```
- ### Selon Dans
    ```
    Selon valeur Dans
        : 
    FinSelon
    ```

## Boucles
- ### Pour i allant de x à y
    ```
    Pour i allant de  à  Faire
    
    FinPour
    ```
- ### Tant que
    ```
    Tant Que condition
    
    FinTantQue
    ```
- ### Répéter Jusqu'à
    ```
    Répéter
    
    Jusqu'à condition
    ```

## Fonction & Procédure
- ### Créer une fonction
    ```
    Fonction nom_fonction() : type
    Lexique

    Début
        Retourner 
    Fin
    ```
- ### Créer une procédure
    ```
    Procédure nom_procedure()

    Début
        
    Fin
    ```
