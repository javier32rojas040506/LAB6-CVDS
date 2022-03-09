### Francisco Javier Rojas
### Juan Camilo Rojas

---


# LAB 6

![Heroku](https://pyheroku-badge.herokuapp.com/?app=lab6-cvds&style=plastic)

[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/javier32rojas040506/LAB6-CVDS)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/4ad12e0c049a42a188a846552775c02c)](https://www.codacy.com/gh/javier32rojas040506/LAB6-CVDS/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=javier32rojas040506/LAB6-CVDS&amp;utm_campaign=Badge_Grade)
---

## Integración contínua con CircleCI y Heroku

Usando la siguiente documentacion:
[Documentación CircleCI para Heroku:](https://circleci.com/integrations/heroku/)


Para este ejercicio haga uso de la versión funcional de su aplicación: la rama 'master' con la aplicación basada en un 'mock' de la lógica, o la versión completa (en caso de que ya la tenga) ya mezclada en la rama 'master'.

### Parte II.

1.2.3 NoS autenticamos y creamos el proyecto, luego vinculamos el repo de github y finalmente regenramos la key api
    
![](img/HEROKU2.png) 

![](img/HEROKU1.png)

4. Realizamos la integracion con CIRCLE CI  y agregamos la siguinete llaves o variables de entorno

![](img/confAPIKEY.PNG)
![](img/APIKEY.png)  

   (nota: es importante usar esos nombre como variable)
   (des: en la variable name va el nombre del proyecto en HEROKU
        Y  en la variable API KEY la llave que se genero en HEROKU)
   

5.6 Agregamos el archivo /.circle/config.yml este puede ser copiado de la web
de circle CI (OPCION TRES PUNTOS A LADO DEL PROYECTO >>> ARCHIVO DE CONFIGURACION)

![](img/pipeline0.png)
![](img/pipeline1.png)



7.8.9 archivos necesarios para deploy

![](img/confDEPLOY.png)
![](img/confDEPLOY1.png)
![](img/confDEPLOY2.png)

10. Deploy
    
    ![](img/deploy0.png)
    ![](img/deploy1.png)
    ![](img/deploy2.png)
    
11. Codacy
    
    ![](img/codacy.png)
    ![](img/codacy1.png)
    ![](img/codacy2.png)
    ![](img/codacy3.png)
    
12. badges
    
    ![](img/badges.png)