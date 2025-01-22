# Pierwsza aplikacja Spring Boot

## Co robi aplikacja?
- Obsługuje żądanie GET, które zwraca wiadomość tekstową.
- Wykorzystuje widok HTML (`greeting.html`) z obrazem.

## Działanie Aplikacji
Wchodząc na `http://localhost:8080/greeting`, użytkownik widzi widok "greeting", który ilustruje użycie wzorca MVC w Spring Boot – dane z kontrolera są dynamicznie przekazywane do szablonu HTML, który generuje odpowiedź widoczną dla użytkownika w przeglądarce. Strona wyświetla powitanie z możliwością personalizacji za pomocą parametru `name`.  
   Przykładowo:  
   - `http://localhost:8080/greeting?name=Wiktor` wyświetli wiadomość **"Hello, Wiktor!"**.
   - Jeśli parametr `name` nie jest podany, domyślnie zostanie wyświetlone **"Hello, World!"**.

