## WeatherAPI - Opis aplikacji

### Opis aplikacji
WeatherAPI to nowoczesna aplikacja mobilna na platformę Android, stworzona w Android Studio, której głównym celem jest dostarczanie użytkownikom bieżących informacji pogodowych. Aplikacja korzysta z zewnętrznego API pogodowego, aby pobierać i wyświetlać dokładne dane dotyczące warunków atmosferycznych w wybranej lokalizacji.

### Funkcje aplikacji
1. **Aktualne dane pogodowe**: WeatherAPI oferuje natychmiastowy dostęp do aktualnych informacji o pogodzie, takich jak temperatura, wilgotność, prędkość wiatru, ciśnienie atmosferyczne i stan zachmurzenia.
2. **Prognoza na kolejne dni**: Aplikacja zapewnia prognozy pogody na nadchodzące dni, umożliwiając użytkownikom planowanie aktywności na podstawie przewidywanych warunków atmosferycznych.
3. **Lokalizacja GPS**: WeatherAPI automatycznie wykrywa lokalizację użytkownika za pomocą GPS i dostarcza dane pogodowe specyficzne dla tej lokalizacji.
4. **Wyszukiwanie lokalizacji**: Użytkownicy mogą również ręcznie wyszukiwać i dodawać różne lokalizacje, aby sprawdzić pogodę w dowolnym miejscu na świecie.
5. **Interfejs użytkownika**: Aplikacja posiada intuicyjny i estetyczny interfejs użytkownika, zaprojektowany zgodnie z wytycznymi Material Design, zapewniając łatwość obsługi i atrakcyjny wygląd.
6. **Powiadomienia pogodowe**: WeatherAPI wysyła powiadomienia dotyczące nagłych zmian pogody, ostrzeżeń meteorologicznych i innych ważnych informacji.
7. **Tryb ciemny**: Aplikacja wspiera tryb ciemny, co pozwala na oszczędność energii i przyjemniejsze korzystanie w warunkach słabego oświetlenia.

### Technologie
- **Język programowania**: Kotlin
- **Środowisko deweloperskie**: Android Studio
- **API pogodowe**: Aplikacja integruje się z zewnętrznym API pogodowym (np. OpenWeatherMap, WeatherAPI, AccuWeather) za pomocą zapytań HTTP i przetwarza zwrócone dane w formacie JSON.
- **Architektura**: MVVM (Model-View-ViewModel) dla lepszej organizacji kodu i łatwości utrzymania.
- **Biblioteki**: Retrofit do wykonywania zapytań sieciowych, Glide do ładowania obrazów, LiveData i ViewModel z Android Jetpack do zarządzania danymi i ich obserwacji.

### Jak to działa?
1. Po uruchomieniu aplikacji, WeatherAPI automatycznie pobiera lokalizację użytkownika za pomocą GPS.
2. Aplikacja wysyła zapytanie do wybranego API pogodowego z informacją o bieżącej lokalizacji.
3. Otrzymane dane pogodowe są przetwarzane i wyświetlane na ekranie głównym aplikacji.
4. Użytkownik może również wyszukiwać inne lokalizacje za pomocą paska wyszukiwania i dodawać je do listy ulubionych miejsc.
5. Aplikacja regularnie aktualizuje dane pogodowe i wysyła powiadomienia w przypadku istotnych zmian.

### Przykładowy ekran
- **Ekran główny**: Wyświetla aktualne dane pogodowe dla bieżącej lokalizacji oraz podstawowe informacje o prognozie na najbliższe dni.
- **Ekran szczegółowy**: Po kliknięciu na dzień prognozy, użytkownik może zobaczyć bardziej szczegółowe informacje, takie jak godzinna prognoza pogody.

WeatherAPI to niezbędne narzędzie dla każdego, kto chce być na bieżąco z warunkami atmosferycznymi, niezależnie od miejsca pobytu. Aplikacja łączy w sobie dokładność danych, wygodę użytkowania i estetykę, czyniąc codzienne sprawdzanie pogody prostym i przyjemnym.
