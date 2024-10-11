# Wszystko co musisz wiedzieć o tym projekcie 
to projekt który ma na celu stworzenie logowania ale bez bazy danych użytkownik otrzymuje klucz który musi wprowadzić by się zalogować a ale on sam nie może przeczytać zawartości pliku klucza można powiedzieć że to taki znowiony i działający w zamyśleprojekt zaloguj się przez arbuzik

<details>
<summary>dowiedz się więcej</summary>
<p>Informacje o działaniu klucza.

klucz to spycialny plik zawierający kod z identyfikatorem przez który możesz się zalogować (zwykły użytkownik nie jest w stanie zobaczyć kodu w podglądzie w miejscu tórym przechowuje pliki ani nie może zobaczyć jego zawartośći po przez spycialne programy)  
tylko masza strona może je zobaczyć


# System logowania

Ten projekt zawiera prosty system logowania, który opiera się na plikach `.klucz`.

## Jak to działa?

1. Podczas rejestracji generowany jest plik `.klucz` zawierający unikalny identyfikator.
2. Użytkownik zapisuje ten plik lokalnie na swoim komputerze.
3. Aby zalogować się, użytkownik przesyła plik `.klucz`, a system rozpoznaje go na podstawie zawartego tam identyfikatora.

## Plik `.klucz`

Plik `.klucz` zawiera unikalny identyfikator (ID klucza), który jest używany do rozpoznawania użytkownika. Plik ten nie jest czytelny dla użytkownika.

</p>
</details>
