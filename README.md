Java webapp protected by the Jasig / Apereo CAS client
==

![English](https://www.casinthecloud.com/img/other/flag_en.png)

Maven demo using the Jasig / Apereo CAS client (v3.3.3) to protect a web application.

Use **mvn clean compile jetty:run** to start the webapp on **http://localhost:8080**. The url 'protected/index.jsp' is protected and should trigger a CAS authentication.

Most of the configuration is defined in the **src/main/webapp/WEB-INF/web.xml** file.

Use your own CAS in the cloud server with the following service:
- Service url: 'http://localhost:8080/protected/*' as an 'Ant pattern'
- 'Call from the browser to the specific application url for logout: http://localhost:8080/logout.jsp'.

==

![Français](https://www.casinthecloud.com/img/other/flag_fr.png)

Démo utilisant le client CAS Jasig / Apereo (v3.3.3) pour protéger une application web.

Utilisez **mvn clean compile jetty:run** pour lancer le site web sur **http://localhost:8080**. L'url 'protected/index.jsp' est protégée et déclenche une authentification CAS.

L'essentiel de la configuration est défini dans le fichier **src/main/webapp/WEB-INF/web.xml**.

Utilisez votre propre serveur CAS in the cloud avec le service suivant :
- Url de service : 'http://localhost:8080/protected/*' en tant que 'Expression Ant'
- 'Appel depuis le navigateur de l'url applicative spécifique pour la déconnexion : http://localhost:8080/logout.jsp'.
