# calculator-java
simple calculator written in Java; supports addition, subtraction, multiplication and division

LOC (Lines of Code) za sve fajlove zbirno iznosi 95 linija.

Ciklomatska složenost metode evaluateExpression iznosi 3. Ciklomatska složenost metode Calculate iznosi 2.

Kognitivna složenost metode evaluateExpression iznosi 6. Kognitivna složenost metode Calculate iznosi 4.

Analizirajući kod statički, bez pokretanja istog, moja zapažanja su:

Calculator.java

5: Nedostaje Javadoc komentar za klasu.
8: Nedostaje Javadoc komentar za konstruktor.
14: Nedostaje Javadoc komentar za metodu.
14: Loš naziv metode, trebalo bi nazvati evaluateExpression.
14: Metoda je dugačka i kompleksna, sa visokom kognitivnom složenošću i nekoliko loše strukturisanih blokova koda.
25: Nedostaje Javadoc komentar za metodu.
25: Loš naziv metode, trebalo bi nazvati Calculate.
25: Metoda je dugačka i kompleksna, sa visokom kognitivnom složenošću i nekoliko loše strukturisanih blokova koda.
35: Nedostaje Javadoc komentar za metodu.
35: Loš naziv metode, trebalo bi nazvati isNumeric.
40: Loša praksa korišćenja System.out.println() umesto korišćenja loggera.
47: Loša praksa korišćenja System.out.println() umesto korišćenja loggera.
Ova zapažanja ne moraju nužno da ukazuju na greške u kodu, ali mogu ukazati na potencijalne nedoslednosti ili propuste u praksi kodiranja (Code Smells).

