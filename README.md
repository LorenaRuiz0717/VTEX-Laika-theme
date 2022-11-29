# Store theme Laika

Este un desarrollo en tecnologia Vtex, con el reto de replicar los diferentes componentes en los diferentes tamaños de dispositivos de la plataforma 
Ecommerce [Laika]( https://laika.com.co/), productos para mascotas. :paw_prints:

### Home theme Laika
![image](https://user-images.githubusercontent.com/75150307/204445133-9f9733e2-d3ec-4588-a83f-5de5294c1a89.png)
### Footer theme Laika
![image](https://user-images.githubusercontent.com/75150307/204445231-fb017d74-e871-4f7a-b0f7-76f8f8e063b5.png)
### Vista Mobile Home theme Laika
![image](https://user-images.githubusercontent.com/75150307/204445592-449d26f9-9267-49c4-b72d-6575d1d202b6.png)

## Configuración

### Paso 1 - Configuración básica  
Ingresar a la [guía básica de configuración](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-2-basicsetuptodevelopinvtexio) de VTEX IO donde encontrara paso a paso como realizar la configuración , al finalizar tendra instalada la interfaz de línea de comandos de [VTEX IO](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-toolbelt) y podra hacer uso de un espacio de trabajo para comenzar su desarrollo.

### Paso 2 - Clonación del repositorio Minimum Boilerplate.

Este repositorio le permitira tener un tema con las minimas caracteristicas de un store, [plantilla](https://github.com/vtex-apps/minimum-boilerplate-theme).
Clonelo con el comando git clone para crear un repositorio de forma local y asi poder trabajarlo independientemente en su espacio de desarrollo.

### Paso 3 - Editando el archivo Manifest.json
Una vez el repositorio este clonado, visualicelo desde su editor, en la raiz del proyecto encontrara el archivo manifest.json.
En este es necesario cambiar el valor de vendor según el partner,vname el cual es el del store en desarrollo y por ultimo version de 0.0.0 a esta primera version 0.0.1

Por ejemplo:  
{
  "vendor": "itgloberspartnercl",
  "name": "store-theme",
  "version": "0.0.1"
}

### Paso 4 - Instalando las apps requeridas
Es necesario tener  `vtex.store-sitemap` y `vtex.store` instalados para usar Store Framework y trabajar en el tema de su tienda, en la terminal verifique con el comando `vtex list` si se encuentran instaladas. De no ser así debe ejecutar el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`

### Paso 5 - Desinstalar cualquier tema existente
Con el comando `vtex list` podra ver si tiene instalado un tema por defecto en la tienda, si es asi identifiquelo y desisntalelo con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme
```

### Paso 6 - Ejecute y obtenga una vista previa de su tienda
Para poder ver la tienda en proceso es necesario ejecutar el comando `vtex link` el cual si se ejecuta de forma correcta dara un estado `App linked successfully` en la terminal y se podra visualizar la tienda en la URL dada.
El comando vtex browse abrira una ventana del navegador con su tienda vinculada.

## Dependencias  
1. Store minimun boilerplate theme  
2. Store GraphQl

## Store Component Apps  
1. "vtex.store": "2.x"  
2. "vtex.store-header": "2.x"  
3. "vtex.product-summary": "2.x"  
4. "vtex.store-footer": "2.x"  
5. "vtex.store-components": "3.x"  
6. "vtex.styleguide": "9.x"  
7. "vtex.slider": "0.x"  
8. "vtex.carousel": "2.x"  
9. "vtex.shelf": "1.x"  
10. "vtex.menu": "2.x"  
11. "vtex.minicart": "2.x"  
12. "vtex.product-details": "1.x"  
13. "vtex.product-kit": "1.x"  
14. "vtex.search-result": "3.x"  
15. "vtex.login": "2.x"
16. "vtex.my-account": "1.x"  
17. "vtex.flex-layout": "0.x"  
18. "vtex.rich-text": "0.x"  
19. "vtex.store-drawer": "0.x"  
20. "vtex.locale-switcher": "0.x"  
21. "vtex.product-quantity": "1.x"  
22. "vtex.product-identifier": "0.x"  
23. "vtex.product-specification-badges": "0.x"  
24. "vtex.product-review-interfaces": "1.x"  
25. "vtex.telemarketing": "2.x"  
26. "vtex.order-placed": "2.x"  
27. "vtex.stack-layout": "0.x"  
28. "vtex.tab-layout": "0.x"  
29. "vtex.responsive-layout": "0.x"  
30. "vtex.slider-layout": "0.x"  
31. "vtex.iframe": "0.x"  
32. "vtex.breadcrumb": "1.x"  
33. "vtex.sticky-layout": "0.x"  
34. "vtex.add-to-cart-button": "0.x"  
35. "vtex.store-image": "0.x"  
36. "vtex.modal-layout": "0.x"  
37. "vtex.search": "2.x"  
38. "vtex.store-icons": "0.x"   
39. "vtex.disclosure-layout": "1.x"  
40. "vtex.product-list": "0.x"  
41. "vtex.product-price": "1.x"  
42. "vtex.store-link": "0.x"
43. "vtex.store-newsletter": "1.x"

## Dependencias Peer store component  
1. "vtex.wish-list": "1.x"  

## Custom Apps  
1. "itgloberspartnercl.whatsapp-button": "0.x"
2. "itgloberspartnercl.bullets-diagramation": "0.x"
3. "itgloberspartnercl.add-to-cart-info": "0.x"
4. "itgloberspartnercl.custom-deparment-search": "0.x"
5. "itgloberspartnercl.pdf-reader": "0.x"

## Contributors  
1.	Lorena Ruiz
