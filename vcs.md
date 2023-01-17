# Control de versions a IntelliJ:

IntelliJ té un control de versions integrat i, a més, deixa integrar-ne altres com GitHub.

# Control a IntelliJ de Linux

## Integració amb GitHub:

Per integrar IntelliJ amb GitHub hem de seguir els següents passos:

1.- VCS -> Enable Version Control Integration.

![image](https://user-images.githubusercontent.com/110727546/212978510-407cc4e7-fa24-45c7-98e2-ceaa2cf7651b.png)

Seleccionem Git.

## Commit:

1.- Seleccionar fitxers per fer commit:

Commit i seleccionem tots els fitxers o Git-> Commit.

![image](https://user-images.githubusercontent.com/110727546/212978769-f5bfcb59-af91-4958-ba11-9e5647dcec01.png)

2.- Possem un missatge de commit i clickem el botó Commit:

![image](https://user-images.githubusercontent.com/110727546/212978851-946ba13c-8a9d-4b65-8eed-d3c4c9a6e8e9.png)

## Push:

1.- Seleccionem Git->Push

![image](https://user-images.githubusercontent.com/110727546/212979040-7aa233f3-4f00-486f-a71b-eb9491c1e15a.png)


2.- Clickem Define Remote

![image](https://user-images.githubusercontent.com/110727546/212979100-f234c5b5-126a-43e6-ad93-96299b421fec.png)

Ara ens demana la URL del projecte que l'hem de buscar a la web de Github.

![image](https://user-images.githubusercontent.com/110727546/212979313-901d1728-cb3a-4df7-8980-de0c2f6f135d.png)


Copiem la URL i la enganxem a IntelliJ.

![image](https://user-images.githubusercontent.com/110727546/212979428-3257a588-40c1-4fde-8419-020a6cc679b0.png)

![image](https://user-images.githubusercontent.com/110727546/212979463-e4aacda1-d86e-45fb-af66-bf44799e2f38.png)


Clickem Commit.

![image](https://user-images.githubusercontent.com/110727546/212979514-2a7c2f6f-f507-479a-b2d1-e0d77eaeab38.png)

Ja s'haurà pujat el projecte.


# Control a IntelliJ de Windows


## Integració amb GitHub:

Per integrar IntelliJ amb GitHub hem de seguir els següents passos:

1. Crear un Token a GitHub, a [https://github.com/settings/tokens](https://github.com/settings/tokens).

Heu de seleccionar gist i repo al crear el token i possar-li un nom, **copieu el codi**.

![image](https://user-images.githubusercontent.com/110727546/207140573-c9b7e253-d63f-4184-8b4a-87bd9bb3be3d.png)

2. Afegir el nostre compte de Github a IntelliJ, a File->Settings->Version Control->GitHub

![image](https://user-images.githubusercontent.com/110727546/207140191-d0a6fb77-832e-4fdb-8895-62442507f467.png)

Aquí afegim el nostre mail i el Token que hem generat abans.

3. A la web de GitHub creem un repositori nou i copiem la seva URL HTTPS. 

![image](https://user-images.githubusercontent.com/110727546/207141982-b5a57486-d79b-4434-9926-4d6c78d8b824.png)

4. Ara a VCS->Git->Push definim origen amb la URL anterior:

![image](https://user-images.githubusercontent.com/110727546/207142395-bb0a2245-c814-49c7-9192-380e2b128f61.png)


![image](https://user-images.githubusercontent.com/110727546/207142260-4080a46d-dd6e-404c-81bd-c47b83065969.png)


Ara al menu de Git podrem fer les comandes típiques de Git des de IntelliJ: Commit, Comparar amb el repositori, mostrar historial, fer push, pulls, etc...



