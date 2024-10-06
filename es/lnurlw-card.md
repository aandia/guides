¿Alguna vez has querido regalarle sats a alguien en forma física? Con una billetera LNbits, puedes crear fácilmente una tarjeta de regalo NFC. Esto funciona escribiendo un enlace LNURLw en la tarjeta NFC, desde el cual el destinatario puede retirar sus sats con una billetera compatible con LNURL.

## ¿Qué necesitas?

- Billetera LNbits
- Teléfono Android
- Tarjeta NFC con capacidades de al menos NTAG2*, por ejemplo, NTAG216. Consulta la nostr:naddr1qqxnzd3e8qcr2wfn8qcrgwf4qyg8wumn8ghj7mn0wd68ytnhd9hx2q3qtx0k0a7lw62vvqax6p3ku90tccgdka7ul4radews2wrdsg0m865sxpqqqp65whwqrr5 para saber dónde comprar las tarjetas.

💡 Las tarjetas NTAG2* te permiten escribir **un** enlace en ellas. Por ejemplo, pueden funcionar como una tarjeta de presentación que contiene la URL del sitio web de la empresa. Las tarjetas NTAG424 no solo tienen más memoria, sino que también cuentan con un parámetro SUN que permite la autenticación del servidor web, lo cual añade más seguridad a tus pagos. Este último tipo de tarjetas también se pueden convertir en [BoltCards](https://boltcard.org/).

## 1. Activa la extensión
Abre tu billetera LNbits. Activa la extensión LNURLw desde la barra de herramientas y ve a la extensión.

## 2. Crea un enlace de retiro
- En la página de la extensión LNURLw, elige `Advanced Withdraw Link(s)` ("Enlace(s) de retiro avanzado").

- Selecciona la billetera desde la cual se retirarán los sats. Probablemente quieras separar esto de tu billetera principal de LNbits. Para hacerlo, puedes crear primero una nueva billetera LNbits yendo a la barra de herramientas y seleccionando `+ Agregar nueva billetera`, luego depositando algunos sats en la billetera recién creada.

![configure](https://cdn.satellite.earth/9eefb0bcc03e218aac55a5c3bfa06f0cdd59d3b36959c58e3f2f88941cca0d01.webp)

- Asigna un título al enlace de retiro.

- Establece los montos mínimo y máximo que se pueden canjear.

- Establece el número de veces que se puede utilizar el enlace y el tiempo entre intentos de retiro.

- Opcionalmente, puedes añadir una imagen personalizada marcando la casilla `Use a custom voucher design` ("Usar un diseño de cupón personalizado") e ingresando la URL de una imagen en formato .png.

- No marques la casilla de usar un codigo QR único.

Cuando estés satisfecho con la configuración, procede a crear el enlace de retiro.

## 3. Escribe el enlace en la tarjeta NFC
En tu enlace de retiro recién creado, haz clic en `view LNURL` ("ver LNURL"). Haz clic en el botón `Write to NFC` ("Escribir en NFC") y acerca tu tarjeta NFC a tu teléfono para que se pueda escribir en ella.

![write](https://cdn.satellite.earth/7d290d0c076c724af88089f3ad2bdc7c22cac5bc7bb521e5f28c5646a4fe350d.webp)

✔️ HECHO

💡 Informa al destinatario de la tarjeta sobre el saldo de sats que tiene para que no pierda tiempo intentando obtener hasta el último satoshi.

💡 Una vez que el destinatario haya retirado sus sats de la tarjeta de regalo, puede volver a escribir en ella su propia billetera y reutilizarla. ¡Dos pájaros de un tiro! Si la tarjeta que le diste es NTAG424, puede convertirla en una "tarjeta de débito" de Lightning como describimos en la nostr:naddr1qqxnzd3e8qcr2wfn8qcrgwf4qyg8wumn8ghj7mn0wd68ytnhd9hx2q3qtx0k0a7lw62vvqax6p3ku90tccgdka7ul4radews2wrdsg0m865sxpqqqp65whwqrr5. Si la tarjeta es solo NTAG2*, entonces solo puede convertirla en otra tarjeta de regalo.
