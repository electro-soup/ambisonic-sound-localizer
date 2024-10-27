Repozytorium bardziej do pochwalenia się zrobionym projektem:)

Tematem mojej magisterki był "Projekt i budowa systemu do lokalizacji źródeł dźwięku wykorzystującego mikrofony ambisoniczne". Zamierzenia były duże - miał powstać system wykorzystujący dwa DIY mikrofony ambisoniczne, który lokalizowałby źródło dźwięku oraz podawałyby jego odległość od systemu. Z racji, że projekt był czasochłonny i termin obrony zbliżał się nieubłaganie, wyszedł tylko lokalizator, który podawał z którego kąta dochodził dźwięk, ale i tak to był dosyć ciekawe, edukacyjne i multidyscyplinarne przedsięwzięcie - w jego wyniku powstał soft napisany w C, zaprojektowałem też płytki PCB i sam model mikrofonu.

Niestety źródła zaginęły w skutek awarii dysku na którym były trzymane (zwłaszcza do mikrokontrolera).

Co udało się zrobić w ramach projektu:
- 8 kanałową kartę dźwiękową oparta na AVR XMEGA i FT245 (możliwe było wykonanie nagrań z poziomu Labview), jak na 12-bitowe przetworniki XMegi jakość była całkiem dobra
- "frontend" w labview który przetwarzał próbki i rysował na wykresie w czasie rzeczywistym: https://www.youtube.com/watch?v=qcpD8pY3VA0
- końcowym wynikiem był lokalizator wektora źródła dźwięku oraz analizator energii pola akustycznego wokół mikrofonu

<img width="279" alt="image" src="https://github.com/user-attachments/assets/66bc1006-9cd9-4e4e-983c-5fbdf84156bb">

<img width="470" alt="image" src="https://github.com/user-attachments/assets/6aa4c7df-737f-4453-822c-e00522b18613">

<img width="464" alt="image" src="https://github.com/user-attachments/assets/3f9962f2-43d0-4679-b802-f609810196f7">

<img width="472" alt="image" src="https://github.com/user-attachments/assets/28ba9e1d-6ae9-4e6c-84ac-6cd77af08ad0">


