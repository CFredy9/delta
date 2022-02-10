## LISTA DE COMANDOS

| MODELO                 | NOMBRE                  | COMANDO                                            |
|------------------------|-------------------------|----------------------------------------------------|
| ATRACK AL1             |  Apagado de motor       | AT$OUTC=1,0                                        |
| ATRACK AL1             |  Encendido de motor     | AT$OUTC=1,1                                        |
| ATRACK AL1             |  Encendido de motor     | AT+XIOW=E,0                                        |
| ATRACK AL1             |  Apagado de motor       | AT+XIOW=E,1                                        |
| ATRACK AL1             |  Puerta abierta         | AT+XIMEN=1                                         |
| ATRACK AL1             |  Puerta cerrada         | AT+XIMEN=0                                         |
| Cellocator             |  Reseteo de dispositivo | at+xrst=1                                          |
| Cellocator             |  Encendido de motor     | AT+XIOW=E,1                                        |
| Cellocator             |  Apagado de motor       | AT+XIOW=E,0                                        |
| Cellocator             |  Puerta abierta         | AT+XIMEN=0                                         |
| Cellocator             |  Puerta cerrada         | AT+XIMEN=1                                         |
| Cellocator             |  Apagado de motor       | K                                                  |
| Cellocator             |  Apagado de motor       | J                                                  |
| Cellocator             |  Encendido de motor     | K                                                  |
| Cellocator             |  Encendido de motor     | J                                                  |
| COBAN 303F             |  Apagado de motor       | J                                                  |
| COBAN 303F             |  Apagado de motor       | K                                                  |
| COBAN 303F             |  Encendido de motor     | K                                                  |
| COBAN 303F             |  Encendido de motor     | J                                                  |
| 303G                   |  Encendido de motor     | J                                                  |
| 303G                   |  Encendido de motor     | K                                                  |
| 303G                   |  Apagado de motor       | J                                                  |
| 303G                   |  Apagado de motor       | K                                                  |
| COBAN 403A             |  Puerta abierta         | Disarm123456                                       |
| COBAN 403A             |  Puerta cerrada         | Arm123456                                          |
| COBAN 403A             |  Apagado de motor       | Relay,1#                                           |
| COBAN 403A             |  Encendido de motor     | Relay,0#                                           |
| 303G                   |  Apagado de motor       | Relay,0#                                           |
| 303G                   |  Encendido de motor     | Relay,1#                                           |
| Concox X3 / Concox GX7 |  Reseteo de dispositivo | RESET#                                             |
| Concox X3 / Concox GX7 |  Apagado de motor       | #stopelec#123456#                                  |
| Concox X3 / Concox GX7 |  Encendido de motor     | #supplyelec#123456#                                |
| Concox X3 / Concox GX7 |  Encendido de motor     | #supplyelec#123456#                                |
| Concox X3 / Concox GX7 |  Apagado de motor       | #stopelec#123456#                                  |
| GT06                   |  Reseteo de dispositivo | AT$REST=1,5                                        |
| GT06                   |  Solicitud de posición  | AT$GPOS=0                                          |
| GT06                   |  Encendido de motor     | AT$OUTC=1,1                                        |
| GT06                   |  Apagado de motor       | AT$OUTC=1,0                                        |
| GT06e                  |  Puerta abierta         | FIND#                                              |
| GT06N                  |  Encendido de motor     | RELAY,0#                                           |
| GT06N                  |  Apagado de motor       | RELAY,1#                                           |
| GT06N                  |  Encendido de motor     | RELAY,1#                                           |
| GT06N                  |  Apagado de motor       | RELAY,0#                                           |
| GT06N                  | Puerta -                | DOOR,0                                             |
| GT06N                  | Puerta +                | DOOR,1                                             |
| FM*                    | Activación Salida 1     | setdigout 1                                        |
| FM*                    | Desactivación Salida 1  | setdigout 0                                        |
| FM*                    | Activación Salida 1     | setdigout 0                                        |
| FM*                    | Desactivación Salida 1  | setdigout 1                                        |
| FM*                    | Activación Salida 2     | setdigout ?0?                                      |
| FM*                    | Desactivación Salida 2  | setdigout ?1?                                      |
| FM*                    | Desactivación Salida 2  | setdigout ?0?                                      |
| FM*                    | Activación Salida 2     | setdigout ?1?                                      |
| FMB130                 |  Puerta abierta         | setdigout ?1? ?1?                                  |
| FMC130                 |  Encendido de motor     | setdigout ?0?                                      |
| FMC130                 |  Apagado de motor       | setdigout ?1?                                      |
| FMC130                 |  Apagado de motor       | setdigout ?0?                                      |
| FMC130                 |  Encendido de motor     | setdigout ?1?                                      |
| Teltonika FMU130       |  Reseteo de dispositivo | cpureset                                           |
| Teltonika FMU130       |  Solicitud de posición  | ggps                                               |
| Teltonika FMU130       |  Encendido de motor     | setdigout 1                                        |
| Teltonika FMU130       |  Apagado de motor       | setdigout 0                                        |
| Teltonika FMU130       |  Encendido de motor     | setdigout 0                                        |
| Teltonika FMU130       |  Apagado de motor       | setdigout 1                                        |
| GL200                  |  Reseteo de dispositivo | AT+GTRTO=gl200,3,,,,,,FFFF$                        |
| GL300                  |  Reseteo de dispositivo | AT+GTRTO=gl300,3,,,,,,FFFF$                        |
| GMT100                 |  Reseteo de dispositivo | AT+GTRTO=gmt100,3,,,,,,FFFF$                       |
| GMT200                 |  Reseteo de dispositivo | AT+GTRTO=gmt200,3,,,,,,FFFF$                       |
| GV300                  |  Apagado de motor       | AT+GTOUT=gv300,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300                  |  Encendido de motor     | AT+GTOUT=gv300,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300                  |  Apagado de motor       | AT+GTOUT=gv300,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300                  |  Encendido de motor     | AT+GTOUT=gv300,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300                  |  Reseteo de dispositivo | AT+GTRTO=gv300,3,,,,,,FFFF$                        |
| GV300                  |  Fotografía             | AT+GTTAP=gv300,0,,,2,,,,,FFFF$                     |
| GV300N                 |  Apagado de motor       | AT+GTOUT=gv300,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300N                 |  Encendido de motor     | AT+GTOUT=gv300,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300N                 |  Apagado de motor       | AT+GTOUT=gv300,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300N                 |  Encendido de motor     | AT+GTOUT=gv300,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV300N                 |  Fotografía             | AT+GTTAP=gv300,0,,,2,,,,,FFFF$                     |
| GV300N                 |  Puerta abierta         | AT+GTOUT=gv300,0,0,0,1,10,1,,,,0,,,,,,,FFFF$       |
| GV300W                 |  Apagado de motor       | AT+GTOUT=gv300w,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$    |
| GV300W                 |  Encendido de motor     | AT+GTOUT=gv300w,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$    |
| GV300W                 |  Apagado de motor       | AT+GTOUT=gv300w,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$    |
| GV300W                 |  Encendido de motor     | AT+GTOUT=gv300w,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$    |
| GV300W                 |  Reseteo de dispositivo | AT+GTRTO=gv300w,3,,,,,,FFFF$                       |
| GV300W                 |  Fotografía             | AT+GTTAP=gv300w,0,,,2,,,,,FFFF$                    |
| GV300W                 |  Puerta cerrada         | AT+GTOUT=gv300w,0,,,0,0,0,1,10,1,0,,0,0,,,,FFFF$   |
| GV300W                 |  Puerta abierta         | AT+GTOUT=gv300w,0,,,0,10,1,0,0,0,0,,0,0,,,,FFFF$   |
| GV300W                 |  Puerta cerrada         | AT+GTOUT=gv300w,0,,,0,0,0,1,10,1,0,,0,0,,,,FFFF$   |
| GV300W                 |  Puerta abierta         | AT+GTOUT=gv300w,0,,,0,10,1,0,0,0,0,,0,0,,,,FFFF$   |
| GV300W                 |  Puerta abierta         | AT+GTOUT=gv300w,0,,,0,10,1,0,0,0,0,,0,0,,,,FFFF$   |
| GV300W                 |  Puerta cerrada         | AT+GTOUT=gv300w,0,,,0,0,0,1,10,1,0,,0,0,,,,FFFF$   |
| GV50MA                 |  Reseteo de dispositivo | AT+GTRTO=gv50m,03,,0,,,,FFFF$                      |
| GV50MA                 |  Encendido de motor     | AT+GTOUT=gv50m,1,0,0,0,0,0,,,,,,,,,,0,0,0,,,,FFFF$ |
| GV50MA                 |  Apagado de motor       | AT+GTOUT=gv50m,0,0,0,0,0,0,,,,,,,,,,0,0,0,,,,FFFF$ |
| GV50MA                 |  Encendido de motor     | AT+GTOUT=gv50m,0,0,0,0,0,0,,,,,,,,,,0,0,0,,,,FFFF$ |
| GV50MA                 |  Apagado de motor       | AT+GTOUT=gv50m,1,0,0,0,0,0,,,,,,,,,,0,0,0,,,,FFFF$ |
| GV55                   |  Apagado de motor       | AT+GTOUT=gv55,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55                   |  Encendido de motor     | AT+GTOUT=gv55,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55                   |  Apagado de motor       | AT+GTOUT=gv55,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55                   |  Encendido de motor     | AT+GTOUT=gv55,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55                   |  Reseteo de dispositivo | AT+GTRTO=gv55,3,,,,,,FFFF$                         |
| GV55 Lite              |  Encendido de motor     | AT+GTOUT=gv55L,0,0,0,0,0,0,,,,0,,,,,,,FFFF$        |
| GV55 Lite              |  Apagado de motor       | AT+GTOUT=gv55L,1,0,0,0,0,0,,,,0,,,,,,,FFFF$        |
| GV55 Lite              |  Apagado de motor       | AT+GTOUT=gv55L,0,0,0,0,0,0,,,,0,,,,,,,FFFF$        |
| GV55 Lite              |  Encendido de motor     | AT+GTOUT=gv55L,1,0,0,0,0,0,,,,0,,,,,,,FFFF$        |
| GV55 Lite              |  Reseteo de dispositivo | AT+GTRTO=gv55L,3,,,,,,FFFF$                        |
| GV55 Lite              |  Puerta abierta         | AT+GTOUT=gv55L,0,0,0,1,10,1,,,,0,,,,,,,FFFF$       |
| GV55                   |  Apagado de motor       | AT+GTOUT=gv55,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55                   |  Encendido de motor     | AT+GTOUT=gv55,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55                   |  Apagado de motor       | AT+GTOUT=gv55,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55                   |  Encendido de motor     | AT+GTOUT=gv55,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$      |
| GV55T                  |  Encendido de motor     | AT+GTOUT=gv55,0,0,0,0,0,0,,,,0,,,,,,,FFFF$         |
| GV55T                  |  Apagado de motor       | AT+GTOUT=gv55,1,0,0,0,0,0,,,,0,,,,,,,FFFF$         |
| GV55T                  |  Reseteo de dispositivo | AT+GTRTO=gv55,3,,,,,,FFFF$                         |
| GV55T                  |  Encendido de motor     | AT+GTOUT=gv55,0,0,0,0,0,0,,,,0,,,,,,,FFFF$         |
| GV55T                  |  Apagado de motor       | AT+GTOUT=gv55,1,0,0,0,0,0,,,,0,,,,,,,FFFF$         |
| GV55T                  |  Puerta abierta         | AT+GTOUT=gv55,0,0,0,1,10,1,,,,0,,,,,,,FFFF$        |
| GV55T                  |  Puerta abierta         | AT+GTOUT=gv55,0,0,0,1,10,1,,,,0,,,,,,,FFFF$        |
| GV55w                  |  Reseteo de dispositivo | AT+GTRTO=gv55w,3,,,,,,FFFF$                        |
| GV55w                  |  Encendido de motor     | AT+GTOUT=gv55w,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV55w                  |  Apagado de motor       | AT+GTOUT=gv55w,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV55w                  |  Encendido de motor     | AT+GTOUT=gv55w,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV55w                  |  Apagado de motor       | AT+GTOUT=gv55w,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV55w                  |  Puerta abierta         | AT+GTOUT=gv55w,0,5,1,0,0,0,,,,0,,0,,,,,FFFF$       |
| GV75W                  |  Apagado de motor       | AT+GTOUT=gv75w,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV75W                  |  Encendido de motor     | AT+GTOUT=gv75w,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV75W                  |  Apagado de motor       | AT+GTOUT=gv75w,1,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV75W                  |  Encendido de motor     | AT+GTOUT=gv75w,0,,,0,0,0,0,0,0,0,,0,0,,,,FFFF$     |
| GV75W                  |  Reseteo de dispositivo | AT+GTRTO=gv75w,3,,,,,,FFFF$                        |
| H02                    |  Encendido de motor     | *HQ,{0},S20,{1},1,0#                               |
| H02                    |  Apagado de motor       | *HQ,{0},S20,{1},1,1#                               |
| H02                    |  Encendido de motor     | *HQ,{0},S20,{1},1,1#                               |
| H02                    |  Apagado de motor       | *HQ,{0},S20,{1},1,0#                               |
| HUABAO HB-A1L          | COMMAND_UNLOCK_ROPE     | (P43,888888)                                       |
| LK210                  |  Encendido de motor     | 666 |
| LK210                  |  Apagado de motor       | 555 |
| LK210                  |  Encendido de motor     | 555 |
| LK210                  |  Apagado de motor       | 666 |
| LT05(7023)             |  Encendido de motor     | resume123456                                       |
| LT05(7023)             |  Apagado de motor       | stop123456                                         |
| LT05(7023)             |  Apagado de motor       | resume123456                                       |
| LT05(7023)             |  Encendido de motor     | stop123456                                         |
| LT05(7023)             |  Reseteo de dispositivo | reset123456                                        |
| SP3600                 |  Apagado de motor       | *GS00,DOO0;1#                                      |
| SP3600                 |  Encendido de motor     | *GS00,DOO0;0#                                      |
| SP3600                 |  Apagado de motor       | *GS00,DOO0;0#                                      |
| SP3600                 |  Encendido de motor     | *GS00,DOO0;1#                                      |
| SP3600                 |  Reseteo de dispositivo | *GS00,GPO;1;0#\n*GS00,GPO;1;1#\n*GS00,RST#         |
| SP8502                 |  Reseteo de dispositivo | AT+GTRTO=AIR11,3,,,,,,000B$                        |
| SRV 303F               |  Encendido de motor     | 109 |
| SRV 303F               |  Apagado de motor       | 110 |
| SRV 303F               |  Encendido de motor     | 110 |
| SRV 303F               |  Apagado de motor       | 109 |
| ST7200                 |  Reseteo de dispositivo | +XT:7008                                           |
| ST906                  |  Apagado de motor       | 9400000 |
| ST906                  |  Encendido de motor     | 9410000 |
| SUNTECH ST310U         |  Encendido de motor     | Disable1                                           |
| SUNTECH ST310U         |  Apagado de motor       | Enable1                                            |
| SUNTECH ST310U         |  Encendido de motor     | Enable1                                            |
| SUNTECH ST310U         |  Apagado de motor       | Disable1                                           |
| SUNTECH 4310           |  Encendido de motor     | CMD;{0};04;01                                      |
| SUNTECH 4310           |  Apagado de motor       | CMD;{0};04;02                                      |
| SUNTECH 4310           |  Encendido de motor     | CMD;{0};04;02                                      |
| SUNTECH 4310           |  Apagado de motor       | CMD;{0};04;01                                      |
| *                      | getver                  | getver                                             |
| TK103                  |  Encendido de motor     | Resume123456                                       |
| TK103                  |  Apagado de motor       | Stop123456                                         |
| TK103                  |  Encendido de motor     | Stop123456                                         |
| TK103                  |  Apagado de motor       | Resume123456                                       |
| TT8750                 |  Apagado de motor       | RST=T;ID=8750_XXXX;AT$IOGP3=0                      |
| TT8750                 |  Encendido de motor     | RST=T;ID=8750_XXXX;AT$IOGP3=1                      |
| TT8750                 |  Apagado de motor       | RST=T;ID=8750_XXXX;AT$IOGP3=1                      |
| TT8750                 |  Encendido de motor     | RST=T;ID=8750_XXXX;AT$IOGP3=0                      |
| TT8750                 |  Reseteo de dispositivo | >RSP=T;ID=8750_{};AT$RESET<                        |
| TT8750N                |  Apagado de motor       | AT$TTIOCO3=0                                       |
| TT8750N                |  Apagado de motor       | AT$TTIOCO3=1                                       |
| TT8750N                |  Encendido de motor     | AT$TTIOCO3=0                                       |
| TT8750N                |  Encendido de motor     | AT$TTIOCO3=1                                       |
| TT8750N                |  Reseteo de dispositivo | AT$TTGPSRI=1,2
AT&W
AT$RESET                       |
| TT8750P                |  Encendido de motor     | AT$TTIOCO3=1                                       |
| TT8750P                |  Encendido de motor     | AT$TTIOCO3=0                                       |
| TT8750P                |  Apagado de motor       | AT$TTIOCO3=1                                       |
| TT8750P                |  Apagado de motor       | AT$TTIOCO3=0                                       |
| TT8750P                |  Reseteo de dispositivo | AT$TTGPSRI=1,2
AT&W
AT$RESET                       |
| VT03D                  |  Reseteo de dispositivo | RESET#                                             |
| VT09X                  |  Encendido de motor     | ky                                                 |
| VT09X                  |  Apagado de motor       | dy                                                 |
| VT09X                  |  Encendido de motor     | dy                                                 |
| VT09X                  |  Apagado de motor       | ky                                                 |
| VT09X                  |  Reseteo de dispositivo | CQGPS                                              |
| VT09X                  |  Puerta abierta         | cf                                                 |
| VT09X                  |  Puerta cerrada         | sf                                                 |
| Wan Way Tech GS05      |  Encendido de motor     | RELAY,0#                                           |
| Wan Way Tech GS05      |  Apagado de motor       | RELAY,1#                                           |
| Wan Way Tech GS05      |  Encendido de motor     | RELAY,1#                                           |
| Wan Way Tech GS05      |  Apagado de motor       | RELAY,0#                                           |
