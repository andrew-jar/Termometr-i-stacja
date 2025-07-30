Termometr i stacja pogodowa e-paper ESP32.

Termometr i stacja pogodowa na esp32, 4,2  e-paper

Termometr pokojowy, który wykorzystuje czujnik DHT22 do pomiaru temperatury pomieszczenia i pobierania danych pogodowych za pośrednictwem Openweathermap. Jego cechy charakterystyczne:

  4,2 calowy wyświetlacz epaper
  Funkcjonalność punktu dostępu Wifi dla początkowej konfiguracji (dzięki menedżerowi sieci WiFi)
  Interfejs sieci Web do konfigurowania danych potrzebnych do Openweathermap
  Interfejs sieciowy z wyjściem JSON do korzystania z pomiarów za pośrednictwem sieci

 ![term](https://github.com/user-attachments/assets/40114ef1-7e9d-4b4c-8e03-ce0d42f800ee)

Po uruchomieniu po raz pierwszy termometr tworzy punkt dostępu "ESP32-termometr". pass= 12345678
Połącz się z nim, wybierz sieć (tylko 2.4 GHz), wprowadź jej poświadczenia. 

Następnie ponownie uruchomi się i powinien wyświetlić adres IP urządzenia w wierszu na dole. 
Przejdz na wyświetlony adres, przeniesiesz się na stronę, aby wprowadzić dane typu: Miasto, Kraj i klucz API Openweathermap (utwórz konto: https://openweathermap.org/).

Obudowa STL pliki (case)
<img width="800" height="458" alt="a" src="https://github.com/user-attachments/assets/356c71e2-a828-4a08-a154-5154613f0ba1" />

![2](https://github.com/user-attachments/assets/daf168f7-c106-44c2-92c3-7ea4bc010418)
![1](https://github.com/user-attachments/assets/1f20293a-c0a9-468c-9af5-a1d6d5c1d88e)
