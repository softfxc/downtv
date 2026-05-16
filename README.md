https://softfxc.github.io

La librería abierta libtorrent4j de DownTV maneja archivos de extensión torrent. Un archivo torrent es un formato que ha convivido durante mucho tiempo en material de piratería, aún así conteniendo en ciertos casos material legítimo. Este formato basa su funcionamiento en una red P2P que significa semilla a semilla, estos archivos suelen pesar unos pocos KB y con ellos pueden obtenerse archivos de un tamaño relevante. Esto es posible gracias al principio del servidor, es decir, un conjunto de ordenadores decentes encendidos diariamente y conectados en todo momento a la red para compartir dichos archivos con otros usuarios a través de programas que soporten este tipo de conexión llamada P2P.

¿Qué se añadió en esta segunda versión nueva?

1. La primera mejoría grande consta de la integración IPTV de deportes en directo 24/7 (IPTV significa “Televisión por Protocolo de Internet”, sin necesidad de cable) y su repositorio concreto se encuentra en: 
https://iptv-org.github.io/iptv/categories/sports.m3u 

Algunos servicios ya fueron removidos y se encuentran disponibles con previo pago y son tales como, por ejemplo, NBA o LaLiga TV.

A pesar del intento de agregar streamed.su al catálogo deportivo no se obtuvo buen resultado y fue debido a que esa página no devolvía un vídeo reproducible válido, un error similar a los streams de audiovisuales que eran provocados durante el desarrollo de la versión anterior de esta aplicación.

2. También se agregó un catálogo de series reproducibles o descargables para los mayores cinéfilos, que aparece sin la categoría "- IMDB" en la sección HOME.

A pesar del intento de agregar https://grantorrent.wtf/inicio como catálogo adicional y, aunque sí se consiguió cargar su catálogo en DownTV gracias a Orbot (de The Tor Project:  https://play.google.com/store/apps/details?id=org.torproject.android  o  https://guardianproject.info/releases/orbot-latest.apk ) como aplicación adicional, no se obtuvo el gratificante resultado de reproducción con VLC y descarga automática por torrent ya que, aunque dicha web no hospeda publicidad repetitiva ni acortadores frustrantes para los enlaces de descargas, el culpable fue, al igual que en streamed.su: el Cloudflare que actúa como sistema anti-bots y anti-scraping, ocurriendo también con www.opensubtitles.com para libVLC con su opción '+'.

Ambos puntos tratan de tener filtrado de idioma al castellano o incluso inglés, evitando el español latino y otros derivados distintos.
