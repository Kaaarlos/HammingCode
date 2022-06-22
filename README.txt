Datos del equipo -> main.cpp

Version Code::blocks 20.03

Objetivo
A través de análisis matemático y algorítmico se comprobara la eficiencia de corrección en comparativa con los datos
que sere quiere para un procesamiento aceptable.

Instrucciones
Se programará el código Hamming para corregir más de 1 bit de error en el envío de datos.
La entrada de dato será una trama de bits con uno o más errores que ya se encuentra codificada en Hamming.
Mostrara en la salida de pantalla la trama recibida y remarcará dónde se ha hecho la corrección de dato.
El programa deberá estar validado para entradas erróneas distintas a binario.

Posibles errores:
libgcc_s_seh-1.dll

Motivos:
Los errores relacionados con libgcc_s_seh-1.dll pueden producirse por distintas razones. Por ejemplo, 
una aplicación defectuosa, libgcc_s_seh-1.dll, se ha eliminado o ubicado de forma incorrecta, 
ha sido corrompida por un software malicioso en tu PC o un registro de Windows dañado.

Solucion e intalacion del dll 
https://es.dll-files.com/libgcc_s_seh-1.dll.html
https://es.dll-files.com/support/#208340625
https://www.youtube.com/watch?v=ioTerFFdX1E&t=48s

Algoritmo
    Pedir mensaje al usuario
    codificar cada caracter ascii a Hamming
    agregar ruido aleatoriamente al mensaje (uno máximo dos por caracter)
    decodificar el mensaje con ruido de hamming a ascii
    Imprimir el mensaje con ruido
    detectar errores
    corregir errores
    imprimir el mensaje corregido

Arquitectura
    main.cpp
    Menu.h
    Menu.cpp
    Hamming.cpp
    Hamming.h

Responsabilidades
    main.cpp
        Crear un objeto Menu

    Menu
        Pedir informacion al usuario 
        Mostrar información en pantalla

    Hamming
        Codificar ascii a Hamming
        Decodificar Hamming a ascii        
