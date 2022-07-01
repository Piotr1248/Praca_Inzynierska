# Praca_Inzynierska

Niniejszy program został zrealizowany na mikrokontroler Atmega32 z rodziny AVR. 

Realizowane w ramach niniejszej pracy jest budowa prototypu sterownika współpracującego 
z modelem budynku inwentarskiego będzie pełnić następujące, podstawowe funkcje:

- Pomiar temperatury i wilgotności w kilku punktach (Ds18b20>>Onewire & Sy-HS-230>>ADC)
- Sterowanie wentylacją wymuszoną (PWM & Regulator PID)
- Sterowanie przepustnicami kominowymi (Sterowanie silnikami krokowymi)
- Sterowanie oświetleniem LED w trybie dzień / noc (zegar RTC) [I2C]
- Wyświetlanie danych na wyswietlaczu (HD44780>>PCF8575) [I2C]
- Współpraca z aplikacja mobilna (HC-05) [UART>>Bluetooth]
