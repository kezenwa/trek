## [TrekDB](https://www.maravento.com)

**TrekDB** is a rescue tool for MySQL/MariaDB databases. It is used only when there is damage to the structure, which prevents access to dbs and it is not possible to export them with [mysqldump](https://mariadb.com/kb/en/mysqldump/) tool, or in **.sql** format or with third-party tools / **TrekDB** es una herramienta de rescate para bases de datos MySQL/MariaDB. Se usa únicamente cuando hay daños en la estructura, que impiden el acceso a las dbs y no es posible exportarlas con la herramienta [mysqldump](https://mariadb.com/kb/en/mysqldump/), o en formato **.sql** o con herramientas de terceros

### DATA SHEET

|File|Version|OS|Update|Size|
| :---: | :---: | :---: | :---: | :---: |
|[trekdb.exe (.zip)](https://raw.githubusercontent.com/maravento/trekdb/master/trekdb.zip)|1.0|Windows 7/8/10 x86 x64|May 15/2020|2.1 MB|

### HOW TO USE
---

Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Unzip trekdb.exe (.zip) to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen

Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique la fecha y hora de su PC sea la correcta. Descomprima trekdb.exe (.zip) en el escritorio, ejecutarlo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla

### IMPORTANT BEFORE USE
---

- The **TREK** option migrates the contents of the "source" directory (for MARIADB: `\mariadb(version)\data` and for MYSQL: `\mysql(version)\data`) to the "destination" directory (For MysQL: `c:\MYSQLTREK`, for MariaDB: `c:\MARIADBTREK`, for MySQL WampServer: `c:\MYSQLTREKW`, For MariaDB WampServer: `c:\MARIADBTREKW`) and **RESTORE** option restores the contents of the "destination" directory to the "source" directory / La opción **TREK** migra el contenido del directorio "origen" (Para MARIADB: `\mariadb(version)\data` y Para MYSQL: `\mysql(version)\data`) al directorio "destino" (Para MysQL: `c:\MYSQLTREK`, Para MariaDB: `c:\MARIADBTREK`, Para MySQL WampServer: `c:\MYSQLTREKW`, Para MariaDB WampServer: `c:\MARIADBTREKW`) y la opción **RESTORE** restaura el contenido del directorio "destino" al directorio "origen"
- These tools use [Robust File Copy](https://en.wikipedia.org/wiki/Robocopy), which has some limitations and may not achieve the desired results. Use them at your own risk / Estas herramientas utilizan [Robust File Copy](https://es.wikipedia.org/wiki/Robocopy), el cual tiene algunas limitaciones y puede no obtener los resultados deseados. Úselas bajo su propio riesgo

### DB SELECTOR
---

[![Image](https://1.bp.blogspot.com/-RJB_IL4T3iE/XmF7YdWSKPI/AAAAAAAALKo/OA4YZ0yPrEg5RJl7g6iWH7xwtjdvzc5UQCLcBGAsYHQ/s1600/trekdb-selector.png)](https://www.maravento.com)

Select database to migrate. Press Cancel to exit / Seleccione la base de datos a migrar. Pulse Cancel para salir

### MySQL Trek
---

[![Image](https://1.bp.blogspot.com/-Jjkp7DQCDNM/XmF7VqHXAkI/AAAAAAAALKg/l8vSqF9isc4QrFas0n9fGZs0Uk-91g7AQCLcBGAsYHQ/s1600/trekdb-mysql.png)](https://www.maravento.com)

MySQL Trek replicates or restore data from MySQL databases (and associated files) into the `%HOMEDRIVE%\mysql\mysql-%version%\data` folder, using **TREK** (to migrate) and **RESTORE** (to restore) / MySQL Trek replica o restaura datos de las bases de datos MySQL (y archivos asociados) dentro de la carpeta `%HOMEDRIVE%\mysql\mysql-%version%\data`, usando las opciones **TREK**(para migrar) y **RESTORE** (para restaurar)

##### MySQL: Trek and Restore

If you selected **TREK** option at the end, the following message will appear: / Si seleccionó la opción **TREK** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-0nEo_0MfXu0/XmF7VRcAx5I/AAAAAAAALKc/l0JPHaIxI5odL25n2GmXsL2-SyW10qxRACLcBGAsYHQ/s1600/trekdb-mysql-end-trek.png)](https://www.maravento.com)

If you selected **RESTORE** option at the end, the following message will appear: / Si seleccionó la opción **RESTORE** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-EGAv0XgBXCI/XmF7VWCWkSI/AAAAAAAALKY/3A--wjEP8lsR0Ng1wk8bJbpUFH3jxjxSgCLcBGAsYHQ/s1600/trekdb-mysql-end-restore.png)](https://www.maravento.com)

### MariaDB Trek
---

[![Image](https://1.bp.blogspot.com/-uITXn-iW-gg/XmF7UCrRvPI/AAAAAAAALKM/f37Vd5xGXI0ou3NHYOvurSh1EPdnHFFkgCLcBGAsYHQ/s1600/trekdb-mariadb.png)](https://www.maravento.com)

MariaDB Trek Trek replicates or restore data from MySQL databases (and associated files) into the `%HOMEDRIVE%\mariadb\mariadb-%version%\data` folder, using **TREK** (to migrate) and **RESTORE** (to restore) / MariaDB Trek Trek replica o restaura datos de las bases de datos MySQL (y archivos asociados) dentro de la carpeta `%HOMEDRIVE%\mariadb\mariadb-%version%\data`, usando las opciones **TREK**(para migrar) y **RESTORE** (para restaurar)

##### MariaDB: Trek and Restore

If you selected **TREK** option at the end, the following message will appear: / Si seleccionó la opción **TREK** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-lxVaE1CjZQo/XmF7UBWHKXI/AAAAAAAALKQ/1Ysm01DfjLIPHapZR4LKgMRCh2d9gbuHQCLcBGAsYHQ/s1600/trekdb-mariadb-end-trek.png)](https://www.maravento.com)

If you selected **RESTORE** option at the end, the following message will appear: / Si seleccionó la opción **RESTORE** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-4_zd_-zcQvg/XmF7UUjSVnI/AAAAAAAALKU/y10JaXLya48wjT-pUfQV6B4GMAgXTEMmQCLcBGAsYHQ/s1600/trekdb-mariadb-end-restore.png)](https://www.maravento.com)

##### Important about MariaDB Trek

- MariaDB Trek is designed only to work with the [MariaDB 10.4.x Stable (.zip version x86 x64)](https://downloads.mariadb.org/mariadb/10.4.12/), which must be decompressed in the path `%HOMEDRIVE%\mariadb\mariadb-%version%` / MariaDB Trek está diseñada únicamente para trabajar con el paquete [MariaDB 10.4.x Stable (.zip version x86 x64)](https://downloads.mariadb.org/mariadb/10.4.12/), el cual debe estar descomprimido en el path `%HOMEDRIVE%\mariadb\mariadb-%version%`

### MySQL WampServer Trek
---

[![Image](https://1.bp.blogspot.com/-hBfmbtfVLTw/XmF7Z2s3AQI/AAAAAAAALK8/LmoVIiddwToBTa2VSE0NCI0cg5vCWVihACLcBGAsYHQ/s1600/trekdb-wampmysql.png)](https://www.maravento.com)

MySQL WampServer Trek replicates or restore data from MySQL databases (and associated files) into the `data` folder, using **TREK** (to migrate) and **RESTORE** (to restore) / MySQL WampServer Trek replica o restaura datos de las bases de datos MySQL (y archivos asociados) dentro de la carpeta `data`, usando las opciones **TREK** (para migrar) y **RESTORE** (para restaurar)

##### MySQL WampServer: Trek and Restore

If you selected **TREK** option at the end, the following message will appear: / Si seleccionó la opción **TREK** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-A1g6Tbe3SM0/XmF7Z0ra0zI/AAAAAAAALK4/qULod2aGLUs2vSeRS1rkYdNLD6_pv8_9ACLcBGAsYHQ/s1600/trekdb-wampmysql-end-trek.png)](https://www.maravento.com)

If you selected **RESTORE** option at the end, the following message will appear: / Si seleccionó la opción **RESTORE** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-WuvdodOnLi0/XmF7Zrq9CMI/AAAAAAAALK0/G3ud9Z_S5R4KNTJEYgJ2J6wfKC4NiD-tQCLcBGAsYHQ/s1600/trekdb-wampmysql-end-restore.png)](https://www.maravento.com)

### MariaDB WampServer Trek
---

[![Image](https://1.bp.blogspot.com/-qtXO_hBmwxU/XmF7Y4LNZWI/AAAAAAAALKw/2fj1m84vH-o91JAZaZlYZ49c30e2TN_EgCLcBGAsYHQ/s1600/trekdb-wampmariadb.png)](https://www.maravento.com)

MariaDB WampServer Trek replicates or restore data from MariaDB databases (and associated files) into the `data` folder, using **TREK** (to migrate) and **RESTORE** (to restore) / MariaDB WampServer Trek replica o restaura datos de las bases de datos MariaDB (y archivos asociados) dentro de la carpeta `\data`, usando las opciones **TREK** (para migrar) y **RESTORE** (para restaurar)

##### MariaDB WampServer: Trek and Restore

If you selected **TREK** option at the end, the following message will appear: / Si seleccionó la opción **TREK** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-cIgXndRRG8M/XmF7YospfdI/AAAAAAAALKs/79lnV4tY0TIf3-iO6Ew23Gpjfp185lnKQCLcBGAsYHQ/s1600/trekdb-wampmariadb-end-trek.png)](https://www.maravento.com)

If you selected **RESTORE** option at the end, the following message will appear: / Si seleccionó la opción **RESTORE** al finalizar saldrá el siguiente mensaje:

[![Image](https://1.bp.blogspot.com/-BeEVtP4G7_k/XmF7X4zFPEI/AAAAAAAALKk/jj_gkI9LGlcJP4mJrenYwOkQyYsdIv0LQCLcBGAsYHQ/s1600/trekdb-wampmariadb-end-restore.png)](https://www.maravento.com)

### CONTRIBUTIONS
---

We thank all those who contributed to this project / Agradecemos a todos los que han contribuido con este proyecto

### DONATE
---

BTC: 3M84UKpz8AwwPADiYGQjT9spPKCvbqm4Bc

### LICENCES
---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)

[![CreativeCommons](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)
[maravento.com](https://www.maravento.com) is licensed under a [Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional License](http://creativecommons.org/licenses/by-sa/4.0/).

[WinZenity](https://github.com/maravento/winzenity), [Jpsoft](https://jpsoft.com/), [SteelWerX](https://fstaal01.home.xs4all.nl/swreg-us.html), [Microsoft](https://www.microsoft.com/), [74cz](http://74.cz/es/make-sfx/index.php), [Resource Hacker](http://www.angusj.com/resourcehacker/), [7zSFX Builder](https://sourceforge.net/projects/s-zipsfxbuilder/)

© 2020 [Maravento Studio](https://www.maravento.com)

### DISCLAIMER
---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
