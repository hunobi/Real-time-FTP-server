# Real-time-FTP-server

## PL

Zadaniem aplikacji jest aktualizowanie w czasie rzeczywistym każdej zmiany na serwerze ftp u wszystkich podłączonych w tym samym czasie użytkowników. W logach serwera możemy zaobserwować kto  dokonał jakiej czynności na w aplikacji. Np użytkownik A pobrał plik abc.jpg, a użytkownik B przeszedł do katalogu Szachy.

Aplikacja wykorzystuje technologię nodejs, system zarządzania bazą danych mysql oraz serwer ftp do zarządzania plikami. Do obsługi zdarzeń w czasie rzeczywistym wykorzystałem bibliotekę socket.io zaś do zbudowania serwera http użyłem express.js. Część wizualna została zbudowana na Bootstrapie 4.

W celu uruchomienia aplikacji należy skonfigurować plik config.json, posiadać wcześniej dostęp do serwera ftp i mysql. Warto wspomnieć że sam serwer MySQL służy tylko do logowania i rejestracji. W bazie nie są zapisywane inne dane.


## EN

The application's task is to update in real time every change on the ftp server for all users connected at the same time. In the server logs, we can observe who has performed what in the application. For example, user A downloaded abc.jpg and user B went to the Chess directory.

The application uses nodejs technology, mysql database management system and ftp server to manage files. I used the socket.io library to handle events in real time and express.js to build the http server. The visual part was built on Bootstrap 4.

In order to run the application, you must configure the config.json file, previously have access to the ftp and mysql server. It is worth mentioning that the MySQL server itself is only used for logging in and registration. No other data is saved in the database.
