# Soluzione 11

Il comando Docker da eseguire è: docker events.

I comandi sono:

```sh
docker events --since '15m'
docker events --since '24h'
docker events --since '2022-01-18'
docker events --since '2022-10-17T09:00:00' --until '2022-10-17T13:00:00'
docker events --since '2022-10-17T09:00:00' --until '2022-10-17T13:00:00' --filter 'event=start'
```
