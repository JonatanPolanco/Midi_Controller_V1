# Midi_Controller_V1
Arduino nano controller for Helix Native plug-in

## Prerequisitos:
- Line 6 Helix Native (Pueden escribirme por Facebook para adquirirlo: https://www.facebook.com/jonatan.polanco.94/)
- Ableton Live 10 lite (Pueden descargarlo desde aquí: https://www.ableton.com/en/products/live-lite/) ** Yo uso el ableton live por que es el que me permite asignarle el tap tempo al controlador

## Software necesario (En los archivos adjuntos los pueden descargar):
- Programa LoopMidi (Se encarga de crear el puerto virtual midi)
- Programa Hairless midiserial (Enlaza nuestra controlador con el puerto virtual midi)
- Software de Arduino IDE : https://www.arduino.cc/en/software (De aquí lo descargan según su sistema operativo)
## Hardware necesario (dejo algunas páginas sólo como referencia):
- 1 Microcontrolador Arduino nano : https://www.amazon.com/Elegoo-placa-ATmega328P-compatible-Arduino/dp/B0713XK923/ref=sr_1_1_sspa?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=arduino+nano&qid=1630649378&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzTVlMRjUyQTM2STg4JmVuY3J5cHRlZElkPUEwOTMyNjI5N0lFTDNJVkNFU0Q2JmVuY3J5cHRlZEFkSWQ9QTA2NjkyODkxN1hJSjdRU1JQNlpVJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==
- Foot's switch 3pdt (depende de cuantos pulsadores quieran en su controlador **Yo uso 6): https://www.amazon.com/ESUPPORT-3PDT-Interruptor-dise%C3%B1o-guitarra/dp/B012CF181K/ref=sr_1_1_sspa?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1FBF06V02KIEL&dchild=1&keywords=3pdt+foot+switch&qid=1630649627&sprefix=3pdt+%2Caps%2C229&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzNVVXVlc1RDg2TVU4JmVuY3J5cHRlZElkPUEwOTk5MTAxWEZNOFM2T1RXNFNPJmVuY3J5cHRlZEFkSWQ9QTAwNDk2NzdKMk1HWUZJME9WSkomd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl
- cable largo para arduino nano. O si el arduino ya les viene con cable corto, adquirir una extensión (usb a usb) ya que el arduino siempre va a ir conectado al pc.
- Caja metálica (Pueden diseñarla y hacerla ustedes mismos, mandarla a hacer o comprar una ya hecha, lo importante es que quede comoda al pisar cada botón)
- Baquelita pcb perforada: https://www.amazon.com/-/es/prototipo-soldadura-bricolaje-circuito-experimental/dp/B00FXHXT80/ref=sr_1_2?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=24GFYQ3OU8WEJ&dchild=1&keywords=bakelite+pcb&qid=1630651981&sprefix=baquel%2Caps%2C263&sr=8-2
- 20 Jumpers (Aprox) macho-macho para hacer las conexiones: https://www.amazon.com/-/es/cables-multicolor-alambre-tableros-arruinar/dp/B01EV47GI4/ref=sr_1_1?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&dchild=1&keywords=male%2Bjumpers&qid=1630652544&sr=8-1&th=1
- Diodos led's para indicar encendido/apagado (1 por cáda preset que quieran asignar. Y del color que quieran): https://www.amazon.com/-/es/circuito-experimentos-proyectos-cient%C3%ADficos-multicolor/dp/B07PG84V17/ref=sr_1_3?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2GCDSQOHYH4LU&dchild=1&keywords=led+diodes&qid=1630653557&sprefix=leds+diod%2Caps%2C217&sr=8-3

# Instrucciones
![image](https://user-images.githubusercontent.com/65262178/132110204-f72a70df-a6de-4b71-a717-8ae2a3ba9a49.png)

