# HEN AUTOinstaller 4.92 - Instrucciones Básicas para XAMPP y Apache

## 📌 Instrucciones para XAMPP en Windows
1. Descarga e instala **XAMPP** desde [https://www.apachefriends.org/es/download.html](https://www.apachefriends.org/es/download.html).
2. Copia los archivos del proyecto (`.htaccess`, `492.html`, `SETUP.P3T`, `style.html`) en la carpeta:
   ```
   C:\xampp\htdocs\hen_auto_installer\
   ```
3. Abre **XAMPP Control Panel** y asegúrate de que **Apache** esté en ejecución.
4. Ingresa en el navegador de tú consola :
   ```
   http://localhost/hen_auto_installer/492.html
   ```
5. El instalador debería ejecutarse y descargar `SETUP.P3T` automáticamente.

---

## 📌 Instrucciones para Apache en Linux/Servidor
1. Asegúrate de tener Apache instalado. Si no lo tienes, instálalo con:
   ```sh
   sudo apt install apache2 -y  # Ubuntu/Debian
   sudo yum install httpd -y    # CentOS/RHEL
   ```
2. Copia los archivos del proyecto al directorio de Apache:
   ```sh
   sudo cp .htaccess 492.html SETUP.P3T style.html /var/www/html/hen_auto_installer/
   ```
3. Ajusta los permisos para que Apache pueda acceder a los archivos:
   ```sh
   sudo chmod -R 755 /var/www/html/hen_auto_installer/
   ```
4. Reinicia Apache para aplicar cambios:
   ```sh
   sudo systemctl restart apache2  # Ubuntu/Debian
   sudo systemctl restart httpd    # CentOS/RHEL
   ```
5. Ingresa en tu navegador:
   ```
   http://localhost/hen_auto_installer/492.html
   ```
6. El instalador debería ejecutarse y descargar `SETUP.P3T` automáticamente.

---

## 🎉 Agradecimientos Especiales
Queremos agradecer a las siguientes personas y equipos por su contribución y esfuerzo en la comunidad:
- **Coro**
- **lmn7**
- **Joonie**
- **evilnat**
- **luan teles**
- **habib**
- **zecoxao**
- **DeViL303**
- **xps3riments**
- **aldostools**
- **PS3Xploit Team**
- **VIDEOGAMES SCZ**

¡Gracias a todos por su trabajo y dedicación! 🚀

