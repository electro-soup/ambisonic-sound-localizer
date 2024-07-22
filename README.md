Repozytorium bardziej do pochwalenia się zrobionym projektem;)

Tematem mojej magisterki był "Projekt i budowa systemu do lokalizacji źródeł dźwięku wykorzystującego mikrofony ambisoniczne". Zamierzenia były duże - miał powstać system wykorzystujący dwa DIY mikrofony ambisoniczne, który lokalizowałby źródło dźwięku oraz podawałyby jego odległość od systemu. Z racji, że projekt był czasochłonny i kiedyś pasowało się obronić, wyszedł tylko lokalizator, który podawał z którego kąta coś grało, ale i tak wyszedł z tego ciekawy miks, powstał soft, powstały płytki PCB, mikrofony itp. 

Źródeł nie ma (zwłaszcza do mikrokontrolera, tak to jest jak się trzyma pliki na zewnętrznym dysku), jedynie został makaron w Labview, który może tu wrzucę.
Co wyszło?:
- 8 kanałowa karta dźwiękowa oparta na AVR XMEGA i FT245 (nawet dało się nagrać coś z poziomu labview), jak na 12-bitowe przetworniki XMegi jakość była całkiem ok
- "frontend" w labview który przetwarzał próbki i rysował na wykresie w czasie rzeczywistym: https://www.youtube.com/watch?v=qcpD8pY3VA0

<img width="279" alt="image" src="https://github.com/user-attachments/assets/66bc1006-9cd9-4e4e-983c-5fbdf84156bb">

<img width="470" alt="image" src="https://github.com/user-attachments/assets/6aa4c7df-737f-4453-822c-e00522b18613">
