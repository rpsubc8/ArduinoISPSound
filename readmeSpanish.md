# Arduino ISP Sound
Programador de ISP en Arduino donde la entrada de datos viene desde tonos DTMF y AFSK (FSK audio).<br>
Se compone de 2 partes:
<ul>
 <li>Software convertidor de HEX (arduino) a WAV</li>
 <li>Programa Arduino que envía con el protocolo <b>STK500</b> los datos de sonido a otro arduino via ISP</li>
</ul>
<br><br>

# DTMF
Se utiliza un módulo <b>MT8870</b> para decodificar los tonos de audio:<br>
<center><img src='https://raw.githubusercontent.com/rpsubc8/ArduinoISPSound/main/preview/previewDTMF.gif'></center>
