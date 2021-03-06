# Custom Video Player (Video Player)

Projekt odtwarzacza filmów wideo przygotowany z wykorzystaniem HTML 5, CSS (3) oraz Javascript ES6+.

## Opis

Po najechaniu na element **video** wyświetla się panel z opcjami dotyczącymi odtwarzania filmu. Z jego pomocą istnieje możliwość wpływania przez użytkownika na:

-   odtwarzanie filmu (`play/pause`),
-   zmianę głośności (`volume bar`) oraz wyciszenie dźwięku (`mute/unmute` po kliknięciu na przycisk głośności),
-   zmianę szybkości odtwarzania (`select`),
-   przeskoczenie do wybranego momentu filmu (po kliknięciu na `progress bar`) - co istotne, w panelu znajduje się także informacja o aktualnej minucie i sekundzie oraz sumarycznym czasie trwania wideo,
-   wyboru trybu pełnoekranowego (`fullscreen`).

Od strony CSS wykorzystywane są m. in. `zmienne`, `FlexBox`, `@media`, `pseudoklasy` czy wektorowe tło **Hero Patterns**. Defaultowo w projekcie wstawione zostało nagranie z **Pixabay**.

## Zastosowanie i plany rozwoju

Możliwość szerokiego zastosowania jako widgetu na stronie internetowej do odtwarzania filmów bądź też jako elementu biblioteki mediów.

Do rozważenia m. in. dodanie **loadera** (na czas wczytywania filmu ze źródła). Oczywiście, implementacja odtwarzacza w konkretnym projekcie wiązałaby się również z koniecznością wprowadzenia **wyboru filmu do odtworzenia** (ze źródeł dostępnych na przyszłym serwerze bądź też z możliwością wczytania własnych zasobów).

Preview dostępne [na serwerze własnym (eGildia Graczy)](https://egildia.pl/projects/video-player/)
