<h1 align="center">Le French</h1>
<h3 align="center">Auto-complétion pour du pseudo-code</h3>

<p align="center">Faciliter la rédaction de pseudo-code dans des documents textes <code>.txt</code>, cette extension couvre une multitude de raccourcis (cf <a href="#-raccourcis-principaux">Raccourcis principaux</a>)</p>

<h2 id="Raccourcis"> Raccourcis principaux</h2>

- ### Corps d'un algorithme
    `préfixe : algorithme`
  
    ```
    ALGORITHME nom_algo
    // déclaration des types
    // déclaration des prototypes des fonctions
    LEXIQUE

    DÉBUT

    FIN
    ```
- ### Écrire un message
    `préfixes : ecrire,écrire`
  
    ```
    Écrire("")
    ```
- ### Lire un message
    `préfixe : lire`
  
    ```
    Lire()
    ```

## Conditions
- ### Si Alors
    `préfixe : si`
  
    ```
    Si condition Alors

    FinSi
    ```
- ### Si Alors Sinon
    `préfixe : sin`
  
    ```
    Si condition Alors

    Sinon
        
    FinSi
    ```
- ### Selon Dans
    `préfixe : selon`
  
    ```
    Selon valeur Dans
        : 
    FinSelon
    ```

## Boucles
- ### Pour i allant de x à y
    `préfixe : pour`
  
    ```
    Pour i allant de  à  Faire
    
    FinPour
    ```
- ### Tant que
    `préfixe : tantque`
  
    ```
    Tant Que condition
    
    FinTantQue
    ```
- ### Répéter Jusqu'à
    `préfixes : repeter,répéter`
  
    ```
    Répéter
    
    Jusqu'à condition
    ```

## Fonction & Procédure
- ### Créer une fonction
    `préfixe : fonction`
  
    ```
    Fonction nom_fonction() : type
    Lexique

    Début
        Retourner 
    Fin
    ```
- ### Créer une procédure
    `préfixes : procedure,procédure`
  
    ```
    Procédure nom_procedure()

    Début
        
    Fin
    ```
