# Multi Modal Mario Kart

Projekt realizowany w ramach przedmiotu Interfejsy człowiek komputer na 1 roku studiów magisterskich Automatyka i 
Robotyka.

### Cel

Projekt miał na celu realizacje gry inspirowanej na Mario Kart natomiast zamieniając sterowanie na bazujące na wielomodalnościowym podejściu. Zaproponowane przez nas sterowanie opiera się na wizji, dzwięku oraz dotyku. Takie rozwiązanie może zapewnić nadzwyczajne doświadczenia z gry oraz stanowić bazę pod multimodalne interfejsy użytkownika w przyszłości, które dzięki rozwojowi metod analizy danych i sztucznej inteligencji zyskują popularność.

### Struktura

Projekt składa się z 2 kluczowych folderów

- **Unreal_project** w którym znajduje się gra stworzona z pomocą silnika Unreal Engine
- **Control_scripts** zawierający skrypty w pythonie umożliwiające wielomodalnościowe sterowanie

### Komunikacja

Komunikacja z grą odbywa się za pomocą protokołu udp i jest zdefiniowana w pliku connection_settings.json.

### Modalności

Sterowanie grą składa się z poniższych modalności

- [Wizja](Control_scripts/steering_DG)
- [Dzwięk](Control_scripts/Audio)
- [Dotyk](Control_scripts/Pedal)