# Lab3
Wykonanie 2 zadań 

***Zadanie 1***

Dany jest robotyczny system sterowania, który używa klasy RobotNowy, przetwarzającej dane 
lokalizacyjne przy pomocy współrzędnych biegunowych (kąt i odległość). Część systemu wciąż 
korzysta z klasy RobotStary, która obsługuje współrzędne prostokątne (x, y).
Twoim zadaniem jest użycie wzorca Adapter, aby umożliwić nowemu robotowi współpracę z 
kodem opartym na starym systemie.

**INSTRUKCJA**

Skopiuj kod do pliku `.cpp` (np. `robot_adapter.cpp`). Skompiluj go za pomocą polecenia bash
g++ -o robot_adapter robot_adapter.cpp -lm lub za pomocą przycisku w kompilatorze.
Uruchom program bash ./robot_adapter
Program wyświetli wynik w postaci kąta i odległości w układzie biegunowym.

***Zadanie 2***

Należy stworzyć system, który pozwala na dodawanie nowych funkcji do robota za pomocą 
wzorca Dekorator. Bazowego robota (który tylko potrafi się poruszać) będzie trzeba ‘dekorować’
dodatkowymi funkcjami, np. dodaniem kamery, czujnika temperatury czy systemu dźwiękowego.

**INSTRUKCJA**

Skopiuj kod do pliku `.cpp` (np. `robot_Ryszard.cpp`). Skompiluj go za pomocą polecenia bash
g++ -o robot_adapter robot_adapter.cpp -lm lub za pomocą przycisku w kompilatorze.
Uruchom program bash ./robot_Ryszard
Program wyświetli wynik w postaci kąta i odległości w układzie biegunowym.
