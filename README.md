# <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/HTML5.png" alt="Sizmek" width="26" height="36" /></a> FloorAd <a href="https://platform.mediamind.com"><img src="http://www.sizmek.es/eb/users/javiegido_/__logos/logo-dark.png" alt="Sizmek" width="57" height="15" /></a>

Plantilla genérica con todo lo necesario para crear formatos tipo FloorAd utilizando workspaces de Sizmek.

## Descripción

La plantilla para montar un FloorAd consta de tres ficheros html, uno que funcionará de base del formato y que no es necesario modificar(index.html); otro para el panel de menor tamaño (smallPanel.html)y el ultimo para el panel de mayor tamaño (bigPanel.html).

## Configuración 

Para cambiar el tamaño de los elementos del formato o el tiempo de delay para la expansión del panel mayor, modifica los valores del fichero *adConfig.js* que se encuentra en el directorio raíz de la plantilla.

```javascript
var adConfig = {
    "panel_small_width": "1280",
    "panel_small_height": "128",
    "panel_big_width": "1280",
    "panel_big_height": "467",
    "delay_expansion": "300" // milisegundos
};
```

Una vez configurado esto ya puedes trabajar tu creatividad sobre la plantilla.

La expansión del formato no se puede probar en local, es necesario subir la pieza a la [Plataforma de Sizmek](https://platform.mediamind.com) para poder revisar que todo funciona correctamente.

Cuando tengas terminada la creatividad, sube la pieza a la plataforma. En este caso, el formato que debes seleccionar en la plataforma es **HTML5 EXPANDABLE BANNER**. ¿No tienes claro cómo? Puedes seguir esta pequeña guia [Subir Creatividades Sizmek](http://sizmek.es/wiki/doku.php?id=subir_creatividades_html5).

Tambien tendras que añadir los paneles y darles el tamaño correspondiente. Si tienes que realizar algun cambio despúes de configurar la creatividad y reemplazar alguno de los html de los paneles, tendrás que volver a configurar el tamaño de los paneles.

Recuerda que si tienes cualquier duda puedes ponerte en contacto con el equipo de <a href="mailto:creativesupport-spain@sizmek.com">Soporte Creativo de Sizmek</a>

***