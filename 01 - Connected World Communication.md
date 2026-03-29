UNIDAD 5: HACKING DE REDES Y SISTEMAS INFORMÁTICOS

Resultados de Aprendizaje a trabajar en esta Unidad:
RA 3. Ataca y defiende en entornos de prueba, redes y sistemas consiguiendo
acceso a información y sistemas de terceros.
Contenidos a trabajar en esta Unidad:

    Ingeniería social. Phishing.
    Herramientas de búsqueda y explotación de vulnerabilidades.
    Manipulación e inyección de tráfico

Contenidos de la Unidad Didáctica
1. OBTENCIÓN DEL PRIMER ACCESO ........................................................ 3

1.1. Ingeniería social ................................................................................. 3
1.2. Técnicas de phishing .......................................................................... 4
1.3. Herramientas de phishing ................................................................... 6
1.4. Evitar la protección del doble factor de autenticación (2FA) .................. 8
1.5. Técnicas de red team ......................................................................... 8

2. ATAQUES CRIPTOGRÁFICOS ................................................................. 9

2.1. Criptografía aplicada .......................................................................... 9
2.2. Password hashing ............................................................................ 10
2.3. Almacenamiento de contraseñas en los sistemas operativos .............. 11
2.4. Uso y creación de diccionarios .......................................................... 12
2.5. Cracking de contraseñas .................................................................. 14

    Curso 2024/
        ATAQUES A REDES TCP/IP
        3.1. Ataques man-in-the-middle (MItM)
        3.2. MAC flooding
        FRAMEWORK METASPLOIT
        4.1. Arquitectura de Metasploit
        4.2. Manejo básico de metasploit
        ACCIONES EN LA MÁQUINA EXPLOTADA
        5.1. Obtención de una shell reversa
        5.2. Transferencia de archivos
        BIBLIOGRAFÍA

Curso 2024/

1. OBTENCIÓN DEL PRIMER ACCESO

El acceso a la red empresarial es un punto crítico para el éxito de un test de
intrusión. Dependiendo de las características del test de intrusión que se vaya a
realizar, puede estar permitido el uso de técnicas de ingeniería social para evaluar
la seguridad de la empresa contra este tipo de ataques. Sin embargo, esta no es la
única estrategia que se puede utilizar, ya que se pueden realizar acciones sobre el
terreno como, por ejemplo, accesos físicos a las oficinas o ataques de las
comunicaciones inalámbricas.

1.1. Ingeniería social

La ingeniería social es el término moderno con el que se hace referencia a algo que
ha existido desde tiempos remotos: el engaño.

La ingeniería social se estudia en psicología, en el área que se conoce como teoría
de influencia. Esta teoría estudia la manera de influir en las decisiones de las
personas aprovechando las características del comportamiento humano y sus
vulnerabilidades. Esta teoría se basa en seis principios básicos:

    Reciprocidad : engloba un amplio abanico de técnicas para obtener favores.
    Un ejemplo es solicitar un gran favor que sabemos que no nos van a hacer,
    y a continuación, otro favor más fácil de cumplir. Si nos paramos a pensar,
    si nos hubieran pedido el segundo favor en primer lugar, probablemente
    también nos habríamos negado. Esta técnica es conocida como técnica de
    la puerta en la cara.
    Compromiso y constancia. Las personas son más propensas a aumentar
    su confianza en algo después de haberse comprometido con ello. La técnica
    del pie en la puerta sugiere que una persona que acepte realizar una
    pequeña acción, será más propensa a comprometerse posteriormente con
    una mayor.
    Aprobación social: la gente es más propensa a tomar decisiones
    basándose en las decisiones de otro. Por ejemplo, si una persona tiene
    dudas sobre si invertir en criptomonedas, se podría tratar de convencerla
    mostrándole la cantidad de gente que ya ha invertido o está invirtiendo.
    Simpatía : la gente es más propensa a hacer lo que le piden si viene de
    alguien que les gusta, o les genera simpatía.
    Autoridad : las personas realizan acciones sin pararse a pensar en lo que
    están haciendo si estas acciones provienen de alguien con autoridad sobre
    ella.

Curso 2024/

    Escasez o urgencia : la gente tiende a desear más algo que escasea, aunque
    no estuviera la interesado en ello sino escaseara. Este principio también
    engloba la urgencia con la que se debe tomar una decisión.

