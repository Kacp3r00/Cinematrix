# 🎬 Cinematrix

**Aplikacja do rezerwacji kinowych miejsc w seansach filmowych** — projekt pełnej aplikacji do zarządzania repertuarem kina, rezerwacjami i użytkownikami.

>  Aplikacja webowa umożliwiająca zarejestrowanym użytkownikom przeglądanie repertuaru seansów i rezerwowanie miejsc na wybrane pokazy.

---
## Funkcjonalności

Aplikacja oferuje podstawowe funkcje systemu rezerwacji biletów kina:

- **Przeglądanie repertuaru filmów**  
- **Rejestracja i logowanie użytkowników**  
- **Rezerwacja miejsc na wybrane seanse**  
- Obsługa różnych ról (np. admin, kasjer, użytkownik)  
- Panel administracyjny do zarządzania filmami i seansami  

---

## Technologie

Projekt wykorzystuje zestaw technologii i narzędzi:

| Technologia | Zastosowanie |
|-------------|--------------|
| **ASP.NET / C#** | Backend aplikacji |
| **HTML, CSS** | Struktura i styl frontendu |
| **JavaScript** | Interakcje po stronie klienta |
| **Pliki .sln / .csproj** | Rozwiązanie Visual Studio |

---

## Uruchomienie lokalne

Aby uruchomić projekt lokalnie:

1. **Sklonuj repozytorium:**
   ```bash
   git clone https://github.com/Kacp3r00/Cinematrix.git
2. Otwórz projekt w Visual Studio

3. Przywróć pakiety NuGet

4. Skonfiguruj bazę danych
   Otwórz Tools → NuGet Package Manager → Package Manager Console.
   wpisz
   ```bash
   Add-Migration NazwaMigracji
   Update-Database
  
6. Uruchom aplikację (F5)
