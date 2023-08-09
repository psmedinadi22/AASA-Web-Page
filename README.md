# AASA-Web-Page

Usted podrá vizualizar la página web en el siguiente link:

[https://psmedinadi22.github.io/AASA-Web-Page/](https://psmedinadi22.github.io/AASA-Web-Page/)


# Tutorial para agregar un proyecto en la página web
## Subir imágenes a GitHub

1. Para subir las imágenes del proyecto usted debe ingresar a la carpeta de imágenes
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/4b074a0b-288f-48b0-915d-3b95d2165d15)

2. Entrar a la carpeta "Fotos web"
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/bedf6128-7c17-472f-9893-70d6a43996e0)
   
3. Crear una nueva carpeta 
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/269d5ba2-9295-4612-b3d3-fd18d4b2dfeb)
4. Escribir el nombre del proyecto
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/475c05d4-e041-4310-91a4-91c17cce4b15)
5. Escriba un forwardslash "/" con ctl + 7, a continuación escriba de nuevo el nombre de su proyecto seguido de algún comentario referente al proyecto y oprima en el botón "commit changes"
![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/e7be9111-ca15-4022-a98b-2c4f83046b0d)
6. Su carpeta estará creada, ahora debe subir las fotos del proyecto, para ello de click en el botón "add file", luego "Upload files"y finalmente "choose your files-
 ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/f7d05f7c-218c-4e4f-b250-596ee5447c16)
![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/a9d0ec60-7338-4ab4-9521-6a0fc6756843)

7. Luego de seleccionadas las imágenes de clic el botón de "Commit changes"
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/6e8311b4-f616-4763-aba8-f45ef6c2561f)


El proceso de subir las imágenes es exitoso, ahora es momento de agregar la sección a la página web.

## Agregar sección de proyecto en la página web


1. Se debe dirigir al documento llamado portfolio.html
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/98be6f96-2488-47b5-97be-be0c3d3ecff8)


2. Dar clic en el lápiz de la parte superior izquierda
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/9f1b0e41-bcfa-44ec-85f5-6cbbbab2fff8)

3. Una vez en el editable tendrá que editar el documento en dos pasos para agregar un nuevo proyecto. El primero es para agregar un nuevo circulo en el cual debe ir una imagen, un título y una descripción corta del proyecto. El segundo paso tiene como objetivo crear un collage de imágenes, un título, una fecha y una descripción detallada del proyecto.
   a. Para agregar un nuevo circulo de proyecto debe dirigirse al comentario de finalización del último proyecto
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/a1211357-a630-40bf-9abc-ef1628c9d995)
   b. Copie y pegue la siguiente línea de código en el editable

```
                                        <!--Aqui comienza el NUMERO proyecto -->
					<li class="item web identity">
						<div class="image">
							<img src="images/Fotos web/PROYECTO/NOMBRE DE LA IMAGEN" alt="" />
							<div class="hover">
								<a class="fancybox" rel="gallery1" href="#portfolio_NUMERO">
									<div class="item-content">
										<h4>Nombre del proyecto</h4>
										<p>Haga aqui la descripción corta de su proyecto</p>
									</div>
								</a>
							</div>
						</div>
					</li>
					<!--Aqui termina el NUMERO proyecto-->
```

Ahora usted debe editar 4 ítems, los cuales son:
- El ID del proyecto
- NUMERO del proyecto en donde comienza y en donde finaliza
- Agregar la ruta de la imagen que desea que quede en el círculo, esto incluye el nombre de la carpeta donde se aloja (carpeta que creo anteriormente) y el nombre de la imagen
-  Escribir el título del proyecto y la descripción corta del proyecto


4. Ahora se creará la página desplegable con la información detallada del proyecto

![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/9479d0f9-3d1c-466e-86a6-c149071f8468)

5. Copie y pegue el siguiente código en esta sección 
```
<!--Aqui comienza el Collage de imagenes proyecto NUMERO-->
		<div id="portfolio_NUMERO" class="popup_portfolio">
			<div class="collage">

				<div class="image-container">
					<img src="images\Fotos web\P18013\20190705_145918.jpg" alt="Imagen 1">
				</div>

				<!-- Agrega más divs con clase "image-container" para más imágenes -->
			</div>
			<h3>TITULO DEL PROYECTO </h3>
			<time datetime="2014-06-20">Made: 06/20/14</time>
			<p>DESCRIPCIÓN DETALLADA DEL PROYECTO</p>
		</div>
```
6. Del código copiado edite el ID del proyectro, el título del proyecto, la descripción detallada del proyecto y la ruta de las imágenes que desea agregar, en el código anterior solo hay una imagen agregada, si desea más imágenes en su collage debe agregar el siguiente código cuantas veces quiera encima del comentario "Agrega más divs con clase "image-container" para más imágenes"
   
```
                                <div class="image-container">
					<img src="images\Fotos web\P18013\20190705_145918.jpg" alt="Imagen 1">
				</div>
```

7. Finalmente para guardar con cambios realizados, de click en "commit changes"
   ![image](https://github.com/psmedinadi22/AASA-Web-Page/assets/64180738/49c296a0-5dd8-407d-8098-35534b80601b)

8. Comente detalladamente los cambios que realizó y oprima "Commit changes". Ahora espere un aproximado de 5 min y actualice la página de AASA para ver los resultados.


  
