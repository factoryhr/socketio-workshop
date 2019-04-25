# socketio-zadatak

## Zadatak
* napraviti chat aplikaciju korištenjem "socket.io" biblioteke.
* poruku koja se pošalje iz jednog klijenta prikazati tom klijentu i svik drugim klijentima spojenim na poslužitelj
* kada jedan od klijenata piše, ostalim klijentima prikazati da jedan od klijenata piše poruku


## Opis datoteka
** package.json i package-lock.json **
- sadrži podatke o potrebnim bibliotekama i njihovim verzijama
- kada se pokreće `npm install` naredba, prema ovim datotekama NPM zna koje verzije biblioteka treba instalirati

**index.js**
- dio koda koji se pokreće na poslužitelju
- pokrenuti naredbu `node index.js`

**index.html**
- dio koda koji se pokreće Internet preglednikom
- otvoriti Internet preglednik na lokaciji http://localhost:3000
