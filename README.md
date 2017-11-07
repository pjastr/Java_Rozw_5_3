3. W nowym projekcie wykonaj poniższe czynności:
* Stwórz klasę `Owoc` i klasę potomną `Gruszka`.
* Stwórz interfejs `Jedzenie` i dodaj w nim deklarację metody `Jedz()` typu `void`.
* Podepnij interfejs pod obie klasy stworzonę wyżej, dodaj w obu klasach implementację niejawną w postaci wyświetlania jakiegoś stringa na konsoli.
* W klasie `Main` i instrukcji `Main` dodaj kod.
```java
        Gruszka gruszka1 = new Gruszka();
        Owoc gruszka2 = new Gruszka();
        Jedzenie gruszka3 = new Gruszka();
        Owoc gruszka4 = new Owoc();
        Jedzenie gruszka5 = new Owoc();
        gruszka1.Jedz();
        ((Owoc)gruszka1).Jedz();
        ((Gruszka)gruszka1).Jedz();
        ((Jedzenie)gruszka1).Jedz();
        System.out.println("---");
        gruszka2.Jedz();
        ((Owoc)gruszka2).Jedz();
        ((Gruszka)gruszka2).Jedz();
        ((Jedzenie)gruszka2).Jedz();
        System.out.println("---");
        gruszka3.Jedz();
        ((Owoc)gruszka3).Jedz();
        ((Gruszka)gruszka3).Jedz();
        ((Jedzenie)gruszka3).Jedz();
        System.out.println("---");
        gruszka4.Jedz();
        ((Owoc)gruszka4).Jedz();
        //((Gruszka)gruszka4).Jedz();
        ((Jedzenie)gruszka4).Jedz();
        System.out.println("---");
        gruszka5.Jedz();
        ((Owoc)gruszka5).Jedz();
        //((Gruszka)gruszka5).Jedz();
        ((Jedzenie)gruszka5).Jedz();
```
Przed uruchomieniem przeanalizuj co powinno się wyświetlić na konsoli.
