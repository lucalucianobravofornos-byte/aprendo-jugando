<!DOCTYPE html>
<html lang="es">
<cabeza>
<meta conjunto de caracteres="UTF-8">
<meta nombre="ventana gráfica" contenido="width=device-width, initial-scale=1">
<meta nombre="color del tema" contenido="#6c5ce7">
<title>Aprendo Jugando</title>
<estilo>
:raiz{--purpura:#6c5ce7;--rosa:#ff6b81;--azul:#1e90ff;--amarillo:#ffd166;--verde:#20bf6b;--tinta:#273043}
*{tamaño de la caja: caja de borde}
cuerpo{ margen: 0; familia de fuentes: system-ui, -apple-system, Segoe UI, Roboto, sans-serif; fondo: degradado(lineal, 160deg, #eef4ff, #fff1f5); color: var(--tinta) }
encabezamiento{ alineación de texto: centro; relleno: 22px 14px 16px; fondo: degradado(lineal, 135deg, #6c5ce7, #a66cff); color: #fff; radio de borde: 0 0 28px 28px; sombra de caja: 0 5px 18px #6c5ce733 }
encabezamiento h1{ margen: 0; tamaño de fuente: clamp(1.7rem,6vw,2.5rem) } encabezamiento p{ margen: 6px 0 0 }
principal{ ancho máximo: 850px; margen: automático; relleno: 14px }
.estadisticas{ mostrar: flex; justificar-contenido: centro; espacio entre elementos: 10px; ajustar-elementos: ajustar; margen: 12px 0 }
.estadistica{ fondo: #fff; relleno: 8px 14px; radio de borde: 15px; sombra de caja: 0 3px 12px #28304412; grosor de fuente: negrita }
.barraIdioma{ mostrar: flex; alinear-elementos: centro; justificar-contenido: centro; espacio entre elementos: 10px; ajustar-elementos: ajustar; margen: 14px 0 8px; grosor de fuente: 800 }
.barraIdioma select{ borde: 2px sólido #d9d4ff; radio de borde: 12px; relleno: 9px 12px; fondo: #fff; color: var(--tinta); grosor de fuente: 800; tamaño de fuente: 1rem }
.navegacion{ mostrar: cuadrícula; columnas de plantilla de cuadrícula: repetir(3, 1fr); espacio entre filas y columnas: 8px; margen: 14px 0 }
.navegacion botón{ borde: 0; radio de borde: 15px; relleno: 12px 4px; fondo: var(--azul); color: #fff; tamaño de fuente: clamp(.85rem,3.6vw,1rem); grosor de fuente: 800; sombra de caja: 0 4px 0 #1769aa }
.navegacion botón.activo{ fondo: var(--purpura); sombra de caja: 0 4px 0 #4a3bb4; transformación: translateY(1px) }
.panel{ fondo: #fff; radio de borde: 22px; relleno: 16px; sombra de caja: 0 5px 20px #28304412 }
h2{ margen: 0 0 12px; alineación de texto: centro }
.cuadrícula{ mostrar: cuadrícula; columnas de plantilla de cuadrícula: repetir(5, minmax(0,1fr)); espacio entre filas y columnas: 8px }
.letras{ columnas de plantilla de cuadrícula: repetir(5, minmax(0,1fr)) }
.teja{ borde: 0; radio de borde: 15px; altura mínima: 64px; fondo: #f0f4ff; color: var(--tinta); tamaño de fuente: 1.3rem; grosor de fuente: 900; sombra interior: inset 0 -3px #dce5ff; cursor: puntero }
.teja pequeño{ tamaño de visualización: bloque; tamaño de fuente: .65rem; grosor de fuente: 600 }
.teja:activo, .elección:activo, .acción:activo{ transformación: escala(.96) }
.teja.seleccionado{ fondo: #d9fbe8; sombra interior: inset 0 -3px #9be6b8 }
.tarjetaGrande{ alineación de texto: centro; relleno: 14px }
.emojiGrande{ tamaño de fuente: 4rem }
.letraGrande{ tamaño de fuente: 4rem; color: var(--purpura); grosor de fuente: 900; altura de línea: 1.1 }
.ejemplo{ tamaño de fuente: 1.25rem; grosor de fuente: 700 }
.acción, .elección{ borde: 0; radio de borde: 14px; relleno: 11px 16px; grosor de fuente: 800; tamaño de fuente: 1rem; cursor: puntero }
.acción{ fondo: var(--purpura); color: blanco }
.acción.secundario{ fondo: #edf0ff; color: var(--purpura) }
.centro{ alineación de texto: centro }
.emojiJuego{ tamaño de fuente: 3.2rem; margen: 5px }
.palabra{ tamaño de fuente: 2rem; espaciado entre letras: 7px; grosor de fuente: 900; color: #343b50; margen: 12px }
.opciones{ mostrar: flex; justificar-contenido: centro; espacio entre elementos: 10px; ajustar-elementos: ajustar }
.elección{ fondo: #fff0f3; color: #c44569; borde: 2px sólido #ffd3dc; ancho mínimo: 52px; tamaño de fuente: 1.25rem }
.mensaje{ grosor de fuente: 800; altura mínima: 28px; margen: 12px 0 4px }
.mensaje.bueno{ color: #159957 } .mensaje.malo{ color: #d63031 }
.tarjetaNumero{ fondo: #fff8dc }
.elementosContados{ tamaño de fuente: 2rem; altura de línea: 1.6; altura mínima: 80px; ajuste de desbordamiento: anywhere }
.anuncio{ margen: 16px 0 4px; alineación de texto: centro; borde: 1px discontinuo #b6becb; fondo: #f1f3f7; color: #667085; relleno: 12px; radio de borde: 12px; tamaño de fuente: .8rem }
.pieDePagina{ alineación de texto: centro; relleno: 8px 12px 22px; color: #687386; tamaño de fuente: .85rem }
.oculto{ mostrar: ninguno !importante }
@media(min-ancho: 600px){ .cuadrícula{ columnas de plantilla de cuadrícula: repetir(7, minmax(0,1fr)) } .letras{ columnas de plantilla de cuadrícula: repetir(7, minmax(0,1fr)) } .teja{ altura mínima: 74px } }
</estilo>
</cabeza>
<cuerpo>
<encabezamiento><h1>🌈 Aprendo Jugando</h1><p>¡Aprender es una aventura!</p></encabezamiento>
<principal>
<div class="estadisticas"><div class="estadistica">⭐ Puntos: <span id="puntos">0</span></div><div class="estadistica">🏆 Aciertos: <span id="aciertos">0</span></div></div>
<div class="barraIdioma"><label for="selectorIdioma" id="etiquetaIdioma">🌐 Idioma / Language</label>
<select id="selectorIdioma" etiqueta-de-accesibilidad="Idioma"><option valor="es">🇦🇷 Español</option><option valor="en">🇬🇧 English</option></select></div>
<navegacion aria-label="Secciones">
<button class="activo" pestaña-datos="letras" id="pestañaLetras">🔤 Letras</button>
<button pestaña-datos="numeros" id="pestañaNumeros">🔢 Números</button>
<button pestaña-datos="juego" id="pestañaJuego">🧩 Palabras</button>
</navegacion>
<seccion id="letras" class="panel">
<h2 id="encabezadoLetras">¡Tocá una letra y escuchá su nombre!</h2>
<div id="grillaLetras" class="cuadrícula letras"></div>
<div id="tarjetaLetra" class="tarjetaGrande oculto" aria-vivo="polite">
<div class="letraGrande" id="letraGrande">A a</div><div class="emojiGrande" id="emojiLetra">🍍</div>
<div class="ejemplo" id="ejemploLetra">A de avión</div>
<p><button class="acción" id="decirLetra" al-hacer-clic="hablar('Tocá cualquier letra para escuchar su nombre')">🔊 Repetir sonido</button></p>
</div>
</seccion>
<seccion id="numeros" class="panel oculto">
<h2 id="encabezadoNumeros">¡Tocá un número para escucharlo!</h2>
<div id="grillaNumeros" class="cuadrícula"></div>
<div class="tarjetaGrande tarjetaNumero oculto" id="tarjetaNumero" aria-vivo="polite">
<div class="letraGrande" id="numeroGrande">1</div><div id="elementosContados" class="elementosContados">⭐</div>
<div class="ejemplo" id="palabrasNumero">uno</div>
<button class="acción" id="decirNumero">🔊 Escuchar número</button>
</div>
</seccion>
<seccion id="juego" class="panel oculto">
<h2 id="encabezadoJuego">¡Completá la palabra y escuchá la respuesta!</h2>
<p class="centro" id="instruccionesJuego">Elegí la letra que falta para ganar puntos.</p>
<div class="centro"><div class="emojiJuego" id="emojiJuego">🐱</div><div class="palabra" id="palabraIncompleta">G _ T O</div><div class="opciones" id="opciones"></div><div class="mensaje" id="mensajeJuego" aria-vivo="polite"></div><button class="acción secundario" id="siguientePalabra">Otra palabra ↻</button></div>
</seccion>
<div class="anuncio" id="avisoPublicidad">📢 Espacio reservado para publicidad.</div>
</principal>
<pieDePagina>Hecho para aprender jugando 💜<br>Los puntos se guardan en este dispositivo.</pieDePagina>
<guion>
const letras = [
['A','🍍','avión'],['B','⚽','pelota'],['C','🏠','casa'],['D','🦷','diente'],['E','⭐','estrella'],['F','🌸','flor'],['G','🐱','gato'],['H','🍦','helado'],['I','⛪','iglesia'],['J','🦒','jirafa'],['K','🥝','kiwi'],['L','🦁','león'],['M','🍎','manzana'],['N','☁️','nube'],['Ñ','🪆','ñoqui'],['O','🐻','oso'],['P','🐟','pez'],['Q','🧀','queso'],['R','🤖','robot'],['S','☀️','sol'],['T','🐢','tortuga'],['U','🍇','uvas'],['V','🐄','vaca'],['W','🌐','web'],['X','🎷','xilófono'],['Y','🪁','yoyó'],['Z','🦊','zorro']
];
const palabrasNumero = ['cero','uno','dos','tres','cuatro','cinco','seis','siete','ocho','nueve','diez'];
const emojisNumero = ['⭐','🍎','🐸','🦋','🚗','🌼','⚽','🐠','🍓','🚀','❤️'];
const listaPalabras = [
  {emoji:'🐱', es:'GATO', esFalta:1, esRespuesta:'A', esOpciones:['A','E','O'], en:'CAT', enFalta:1, enRespuesta:'A', enOpciones:['A','E','O']},
  {emoji:'🐶', es:'PERRO', esFalta:2, esRespuesta:'R', esOpciones:['L','R','S'], en:'DOG', enFalta:1, enRespuesta:'O', enOpciones:['A','O','U']},
  {emoji:'☀️', es:'SOL', esFalta:1, esRespuesta:'O', esOpciones:['A','O','U'], en:'SUN', enFalta:1, enRespuesta:'U', enOpciones:['A','I','O']},
  {emoji:'🌙', es:'LUNA', esFalta:2, esRespuesta:'N', esOpciones:['M','N','P'], en:'MOON', enFalta:2, enRespuesta:'O', enOpciones:['A','O','U']},
  {emoji:'🍎', es:'MANZANA', esFalta:3, esRespuesta:'Z', esOpciones:['S','Z','C'], en:'APPLE', enFalta:2, enRespuesta:'P', enOpciones:['P','B','T']}
];

let puntos = Número(localStorage.getItem('aj_puntos') || 0);
let aciertos = Número(localStorage.getItem('aj_aciertos') || 0);
let indicePalabra = 0;
let respondido = falso;
let idiomaActual = 'es';
let temporizadorAvance = nulo;

const $ = id => documento.obtenerElementoPorId(id);

function actualizarEstadisticas() {
  $('puntos').contenidoDeTexto = puntos;
  $('aciertos').contenidoDeTexto = aciertos;
  localStorage.setItem('aj_puntos', puntos);
  localStorage.setItem('aj_aciertos', aciertos);
}

function hablar(texto) {
  // Verificamos si el navegador soporta la función de voz
  if (!('speechSynthesis' in ventana) || !('SpeechSynthesisUtterance' in ventana)) {
    consola.log('Texto a voz no disponible en este navegador');
    devolver;
  }
  
  intentar {
    ventana.speechSynthesis.cancel();
    const emision = nuevo SpeechSynthesisUtterance(texto);
    emision.idioma = idiomaActual === 'en' ? 'en-US' : 'es-AR';
    emision.velocidad = 0.85;
    emision.altura = 1;
    
    // No mostramos cartel feo si falla, solo lo registramos
    emision.alOcurrirError = () => {
      consola.log('No se pudo reproducir la voz');
    };
    
    ventana.speechSynthesis.hablar(emision);
    
    if (ventana.speechSynthesis.enPausa) {
      ventana.speechSynthesis.reanudar();
    }
  } capturar(error) {
    consola.log('Error al activar la voz:', error);
  }
}

function mostrarPestaña(pestaña) {
  documento.querySelectorAll('navegacion botón').forEach(b => b.claseLista.alternar('activo', b.datos.pestaña === pestaña));
  ['letras','numeros','juego'].forEach(id => $(id).claseLista.alternar('oculto', id !== pestaña));
}

documento.querySelectorAll('navegacion botón').forEach(b => b.agregarOyenteDeEvento('al hacer clic', () => mostrarPestaña(b.datos.pestaña)));

// Generar grilla de letras
letras.forEach(([letra, emoji, palabra]) => {
  const boton = documento.crearElemento('botón');
  boton.clase = 'teja';
  boton.contenidoInterno = letra + '<pequeño>' + letra.minúsculas() + '</pequeño>';
  boton.setAttribute('etiqueta-de-accesibilidad', 'Letra ' + letra);
  boton.alHacerClic = () => {
    documento.querySelectorAll('#grillaLetras .teja').forEach(t => t.claseLista.remover('seleccionado'));
    boton.claseLista.agregar('seleccionado');
    $('tarjetaLetra').claseLista.remover('oculto');
    $('letraGrande').contenidoDeTexto = letra + ' ' + letra.minúsculas();
    $('emojiLetra').contenidoDeTexto = emoji;
    const ejemplo = idiomaActual === 'es' ? palabra : palabra;
    $('ejemploLetra').contenidoDeTexto = idiomaActual === 'es' ? 'La letra ' + letra + '. ' + letra + ' de ' + palabra : 'The letter ' + letra + '. ' + letra + ' for ' + palabra;
    hablar(idiomaActual === 'es' ? 'La letra ' + letra + '. ' + letra + ' de ' + palabra : 'The letter ' + letra + '. ' + letra + ' for ' + palabra);
  };
  $('grillaLetras').agregarHijo(boton);
});

// Generar grilla de números
para (let n = 0; n <= 10; n++) {
  const boton = documento.crearElemento('botón');
  boton.clase = 'teja';
  boton.contenidoDeTexto = n;
  boton.alHacerClic = () => {
    documento.querySelectorAll('#grillaNumeros .teja').forEach(t => t.claseLista.remover('seleccionado'));
    boton.claseLista.agregar('seleccionado');
    $('tarjetaNumero').claseLista.remover('oculto');
    $('numeroGrande').contenidoDeTexto = n;
    $('elementosContados').contenidoDeTexto = n === 0 ? '¡Cero elementos!' : Array.desde({longitud: n}, () => emojisNumero[n]).unir(' ');
    $('palabrasNumero').contenidoDeTexto = idiomaActual === 'es' ? (n === 0 ? 'cero' : palabrasNumero[n]) : ['zero','one','two','three','four','five','six','seven','eight','nine','ten'][n];
    hablar(idiomaActual === 'es' ? 'El número ' + palabrasNumero[n] : 'The number ' + ['zero','one','two','three','four','five','six','seven','eight','nine','ten'][n]);
  };
  $('grillaNumeros').agregarHijo(boton);
}

function camposPalabra(palabra) {
  devolver {
    palabra: palabra[idiomaActual],
    falta: palabra[idiomaActual + 'Falta'],
    respuesta: palabra[idiomaActual + 'Respuesta'],
    opciones: palabra[idiomaActual + 'Opciones']
  };
}

function renderizarPalabra() {
  respondido = falso;
  si (temporizadorAvance) {
    limpiarTiempoEspera(temporizadorAvance);
    temporizadorAvance = nulo;
  }
  const palabra = listaPalabras[indicePalabra];
  const campos = camposPalabra(palabra);
  
  $('emojiJuego').contenidoDeTexto = palabra.emoji;
  $('palabraIncompleta').contenidoDeTexto = campos.palabra.dividir('').map((c, i) => i === campos.falta ? '_' : c).unir(' ');
  $('mensajeJuego').contenidoDeTexto = '';
  $('mensajeJuego').clase = 'mensaje';
  $('opciones').contenidoInterno = '';
  
  [...campos.opciones].ordenar(() => Número.aleatorio() - 0.5).forEach(letra => {
    const boton = documento.crearElemento('botón');
    boton.clase = 'elección';
    boton.contenidoDeTexto = letra;
    boton.alHacerClic = () => {
      si (respondido) devolver;
      respondido = verdadero;
      documento.querySelectorAll('.elección').forEach(x => x.deshabilitado = verdadero);
      
      si (letra === campos.respuesta) {
        puntos += 10;
        aciertos += 1;
        $('mensajeJuego').contenidoDeTexto = idiomaActual === 'es' ? '¡Muy bien! La palabra es ' + campos.palabra + '. +10 puntos 🎉' : '¡Great job! The word is ' + campos.palabra + '. +10 points 🎉';
        $('mensajeJuego').clase = 'mensaje bueno';
        $('palabraIncompleta').contenidoDeTexto = campos.palabra.dividir('').unir(' ');
        actualizarEstadisticas();
        hablar((idiomaActual === 'es' ? '¡Muy bien! La palabra es ' : 'Great job! The word is ') + campos.palabra);
        temporizadorAvance = establecerTiempoEspera(() => {
          indicePalabra = (indicePalabra + 1) % listaPalabras.longitud;
          renderizarPalabra();
        }, 1400);
      } sino {
        $('mensajeJuego').contenidoDeTexto = idiomaActual === 'es' ? 'La respuesta correcta es ' + campos.respuesta + '. La palabra es ' + campos.palabra + '.' : 'The correct letter is ' + campos.respuesta + '. The word is ' + campos.palabra + '.';
        $('mensajeJuego').clase = 'mensaje malo';
        hablar((idiomaActual === 'es' ? 'La letra correcta es ' : 'The correct letter is ') + campos.respuesta + '. ' + (idiomaActual === 'es' ? 'La palabra es ' : 'The word is ') + campos.palabra);
      }
    };
    $('opciones').agregarHijo(boton);
  });
}

$('siguientePalabra').alHacerClic = () => {
  indicePalabra = (indicePalabra + 1) % listaPalabras.longitud;
  renderizarPalabra();
};

function establecerIdioma(idioma) {
  idiomaActual = idioma;
  const esIngles = idioma === 'en';
  documento.documentElemento.idioma = idioma;
  
  $('pestañaLetras').contenidoDeTexto = esIngles ? '🔤 Letters' : '🔤 Letras';
  $('pestañaNumeros').contenidoDeTexto = esIngles ? '🔢 Numbers' : '🔢 Números';
  $('pestañaJuego').contenidoDeTexto = esIngles ? '🧩 Words' : '🧩 Palabras';
  $('encabezadoLetras').contenidoDeTexto = esIngles ? 'Tap a letter and hear its name!' : '¡Tocá una letra y escuchá su nombre!';
  $('encabezadoNumeros').contenidoDeTexto = esIngles ? 'Tap a number to hear it!' : '¡Tocá un número para escucharlo!';
  $('encabezadoJuego').contenidoDeTexto = esIngles ? 'Complete the word and hear the answer!' : '¡Completá la palabra y escuchá la respuesta!';
  $('instruccionesJuego').contenidoDeTexto = esIngles ? 'Choose the missing letter to earn points.' : 'Elegí la letra que falta para ganar puntos.';
  $('etiquetaIdioma').contenidoDeTexto = esIngles ? '🌐 Language / Idioma' : '🌐 Idioma / Language';
  $('decirLetra').contenidoDeTexto = esIngles ? '🔊 Repeat sound' : '🔊 Repetir sonido';
  $('decirNumero').contenidoDeTexto = esIngles ? '🔊 Hear number' : '🔊 Escuchar número';
  $('siguientePalabra').contenidoDeTexto = esIngles ? 'Next word ↻' : 'Otra palabra ↻';
  $('avisoPublicidad').contenidoDeTexto = esIngles ? '📢 Advertising space reserved.' : '📢 Espacio reservado para publicidad.';
  
  $('tarjetaLetra').claseLista.agregar('oculto');
  $('tarjetaNumero').claseLista.agregar('oculto');
  
  renderizarPalabra();
}

$('selectorIdioma').agregarOyenteDeEvento('cambio', evento => establecerIdioma(evento.objetivo.valor));

renderizarPalabra();
actualizarEstadisticas();
</guion>
</cuerpo>
</html>
