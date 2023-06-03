# Docker-L11

1. Uruchomienie usług zdefiniowanych w pliku docker-compose.yml:
    ```
    docker compose up -d
    ```
2. Odblokowanie portu 6666 w przeglądarce (tutorial z którego korzystałem): 
    ```
    https://thegeekpage.com/err-unsafe-port/
    ```
3. Uruchomienie usług w przeglądarce na portach 6001 oraz 6666:
    ```
    http://localhost:6001/
    ```
    ```
    http://localhost:6666/
    ```
4. Zatrzymanie oraz usunięcie konterów:
    ```
    docker compose down
    ```
