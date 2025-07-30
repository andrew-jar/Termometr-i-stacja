# Termometr i stacja pogodowa e-paper ESP32.

Termometr i stacja pogodowa na esp32, 4,2  e-paper

Termometr pokojowy, który wykorzystuje czujnik DHT22 do pomiaru temperatury pomieszczenia i pobierania danych pogodowych za pośrednictwem Openweathermap. Jego cechy charakterystyczne:

  4,2 calowy wyświetlacz epaper
  Funkcjonalność punktu dostępu Wifi dla początkowej konfiguracji (dzięki menedżerowi sieci WiFi)
  Interfejs sieci Web do konfigurowania danych potrzebnych do Openweathermap
  Interfejs sieciowy z wyjściem JSON do korzystania z pomiarów za pośrednictwem sieci

 ![term](https://github.com/user-attachments/assets/ac2e40c1-3eaa-403b-a54b-657fcb0a6185)


Po uruchomieniu po raz pierwszy termometr tworzy punkt dostępu "ESP32-termometr". pass= 12345678
Połącz się z nim, wybierz sieć (tylko 2.4 GHz), wprowadź jej poświadczenia. 

Następnie ponownie uruchomi się i powinien wyświetlić adres IP urządzenia w wierszu na dole. 
Przejdz na wyświetlony adres, przeniesiesz się na stronę, aby wprowadzić dane typu: Miasto, Kraj i klucz API Openweathermap (utwórz konto: https://openweathermap.org/).

Obudowa STL pliki (case)

<img width="800" height="458" alt="case" src="https://github.com/user-attachments/assets/d2d721f3-bcec-4876-88a9-a37173a8ea15" />

![pinout](https://github.com/user-attachments/assets/2254c868-e2c5-425f-bea9-56a9a6b94ff6)
![pinout1](https://github.com/user-attachments/assets/4f80ce4c-5f29-4803-851c-f86aa8561a32)
