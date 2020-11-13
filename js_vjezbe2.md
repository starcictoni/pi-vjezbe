---
description: Programsko inženjerstvo - JS - Zadaci za vježbanje
author: Toni Starčić, Nikola Tanković
license: CC BY-SA
---

<img src="art/fipu.png" alt="fipu" style="zoom:24%;" />



1. Implementirajte funkciju **isDivisible** koja provjerava je li broj dijeljiv s brojem tri i vraća *boolean* vrijednost. Ograničenja su sljedeća: zabranjeno je korištenje operatora "/" i "%". Input ne smije prazan, ne smije sadržavati ništa osim cijelih brojeva i naravno 0.

   ```javascript
   function isDivisible(string) {
       //tvoj kod
       return;
   }
   console.log(isDivisible("333")) //True
   console.log(isDivisible("334")) //False
   console.log(isDivisible("0")) //Input nije valjan
   console.log(isDivisible("a")) //Input nije valjan
   
   ```

   

2. Implementirajte funkciju **shortestOne** koja prima polje *stringova* i vraća onaj najkraći. Input ne smije biti prazno polje.

   ```javascript
   function shortestOne(array) {
   	//tvoj kod
       return;
   }
   console.log(shortestOne(["Aaaa", "Bbbbbb", "Ccc", "", "Ddddddd", "3"])) //3
   console.log(shortestOne([])) //Input nije valjan
   
   ```

   

3. Implementirajte funkciju **reverseEverything** koja kao input prima rečenicu, odnosno string, a vraća zamijenjen redoslijed svake riječi i slova u rečenici. Input ne smije biti prazan i rečenicu moraju činiti makar dvije riječi. U outputu riječi moraju biti odvojene jednim i samo jednim praznim mjestom.

   ```javascript
   function reverseEverything(string) {
       //tvoj kod
       return;
   }
   console.log(wordsAndCharactersReverser("Riba ribi grize rep")) //"per ezirg ibir abiR"
   console.log(wordsAndCharactersReverser("Riba_ribi_grize_rep")) //Input nije valjan
   
   ```

   

4. Implementirajte funkciju **emailValidator** koja validira uneseni email koristeći *RegExp* a vraća boolean vrijednost. Input ne smije biti prazan. Istu funkciju možete koristiti za svoj projekt.

   ```javascript
   function emailValidator(string) {
       //tvoj kod
       return;
   }
   console.log(emailValidator("tstarcic@student.unipu.hr")) //Mora zadovoljiti i ovakav input 
   //Sadrži mnogo rubnih slučajeva, ograničite ih što više.
   
   ```

   

5. Implementirajte funkciju **passwordValidator** koja validira uneseni password koristeći *RegExp*. Password mora biti dulji od 6 znakova, a manji od 15. Osim duljine, password mora činiti barem jedno veliko slovo, broj i poseban znak. Ukoliko je rezultat funkcije "False", ispišite zašto input ne zadovoljava pravilo. Istu funkciju možete iskoristiti za svoj projekt. 

   ```javascript
   function passwordValidator(string) {
       //tvoj kod
       return;
   }
   console.log(passwordValidator("123Aa!")) //True
   console.log(passwordValidator("A")) //False -> Input je prekratak
   console.log(passwordValidator("123aa!")) //False -> Nedostaje veliko slovo
   //etc.
   ```

   

6. Implementirajte funkciju **removeDuplicates** koja prima *polje* elemenata i vraća *polje* u kojemu se nalaze podaci koji se pojavljuju točno jednom iz polja *inputa*. Input ne smije biti prazan.

   ```javascript
   function removeDuplicates(array) {
       //tvoj kod
       return;
   }
   console.log(removeDuplicates([1, 2, 1, 3, 1, 4, 1, 5, "a", "a", "b", "c"])) //[1, 2, 3, 4, 5, "a", "b", "c"] 
   console.log(removeDuplicates([])) //Input nije valjan
   ```

   

7. Implementirajte funkciju **sumIntervalElements** koja kao *input* prima dva cijela broja koji čine granicu zatvorenog intervala. Zbrojite brojeve tog intervala i osigurajte valjan input. Pritom, input ne smije biti prazan, sadržavati *string*, necijeli broj i argumenti moraju biti nejednaki.

   ```javascript
   function sumIntervalElements(var a, var b) {
       //tvoj kod
       return;
   }
   console.log(sumIntervalElements(2, 5)) //14
   console.log(sumIntervalElements(2, "a")) //Input nije valjan
   console.log(sumIntervalElements(5.3, 2)) //Input nije valjan
   console.log(sumIntervalElements(2, 2)) //Input nije valjan
   
   ```

   

8. Implementirajte funkciju koja izračunava ***manhattanDistance*** s time da točke čine dva para [x1, y1] i [x2, y2], a parovi čine dva člana polja. Osigurajte validan input.

   ```javascript
   function manhattanDistance(array) {
       //tvoj kod
       return;
   }
   console.log(manthattanDistance([[5,4], [3,2]])) //4
   console.log(manthattanDistance([[5,"a"], [3,2]])) //Input nije valjan -> String nije podržan
   console.log(manthattanDistance([[5,4], [3,]])) //Input nije valjan -> Nedostaje vrijednost
   
   ```

   

9. Implementirajte funkciju **descriptive** koja kao input prima *polje* brojeva. U glavnoj funkciji pozovite 3 funkcije koje također treba implementirati: prva ispisuje *aritmetičku sredinu*, druga ispisuje *modalnu vrijednost* i treća ispisuje *medijan*. Modularizirajte kod po vašoj potrebi, odnosno ovakva struktura je samo prijedlog. Input ne smije biti prazno *polje* i polje ne smije sadržavati podatke tipa *string*.

   ```javascript
   function mean (array) {
       //tvoj kod
       console.log()
   }
   function mode (array) {
       //tvoj kod
       console.log()
   }
   function median (array) {
       //tvoj kod
       console.log()
   }
   function descriptive(array) {
       mean(array);
       mode(array);
       median(array);
   }
   console.log(main([[0, 1, 2, 3, 3, 3.3, 4, 5, 5.2, 6, 7]])) //mean() -> 3.59, mode() -> 3, median() -> 3.3
   console.log(main([0, 1, 2, 3, 3, "x", 4, 5, 5.2, 6, 7])) //Input nije valjan 
   
   ```

   





