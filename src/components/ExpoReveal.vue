<template>
  <div id="app">
    <div class="reveal">
        <div class="slides">
			<!-- TITULO DE LA EXPOSICIÓN CON VIDEO DE FONDO -->
			<section data-transition="fade" id="inicio" :data-background-video="require('@/assets/Videos/07_05_00004_fade.mp4')" data-background-video-loop data-background-video-muted data-background-size="cover" data-background-opacity="1.0">
				<h1>Un Paisaje Fronterizo</h1>
				<h2>Cruces e itinerarios en la línea México-Guatemala</h2>
			</section>
			
			<section data-background-color="rgba(0,0,0,0.8)" style="font-size: 2.4rem" data-transition="fade">
				<p>
					La frontera separa y distingue los territorios de los países, pero no significa que sea abstracta y homogénea. Un primer acercamiento al límite internacional entre México y Guatemala en la región de Soconusco, nos ofrece un panorama que invita a reflexionar sobre su carácter heterogéneo y plural.
				</p>
				<p>
					A través del siguiente grupo de fotografías realizamos un análisis del paisaje, entendido como la lectura de los elementos físicos, ecológicos y humanos. Los resultados muestran que estos territorios son diversos según los actores que los practican y las diferentes apropiaciones temporales y espaciales que hacen de ellos.
				</p>
				<p style="text-align: right; font-weight: lighter; font-style: italic;">
					—Mauricio Cervantes Salas
				</p>
			</section>

            <section data-background-color="rgba(0,0,0,0.8)" style="font-size: 2.4rem" data-transition="fade">
				<p>
					El trabajo de campo está lleno de retos: espacios no conocidos, tiempos y ritmos a los que hay que acoplarse. Diversidad de actores sociales y preguntas de investigación previas nos llevan a esa etapa de investigación.
				</p>
				<p>
					La planeación y el trabajo en equipo son clave y, desde diversas disciplinas, las miradas se enriquecen con un objetivo principal: documentar fotográfica y audiovisualmente los variados itinerarios y la cotidianidad de la frontera. Lo anterior es mucho más que operar equipos, es mirar primero muy bien para potenciar la documentación visual, fuentes de investigación que no hallaremos de otra manera más que construyéndolas.
				</p>
				<p style="text-align: right; font-weight: lighter; font-style: italic;">
					—Laboratorio Audiovisual de Investigación Social
				</p>
			</section>

            <!-- MAPA DE LOS LUGARES -->
			<section data-background-color="rgba(0,0,0,0.8)" data-transition="fade" id="mapa" data-state="menu" style="padding: 10px 0;">
				<div style="position: relative;">
					<img :data-src="require('@/assets/MapaGuatemala.jpg')"/>
					<img :data-src="require('@/assets/circle_carmenTalisman.png')" id="lugar" style="border: none;background: none;margin: 0;position: absolute;top: 47px;right: 313px;box-shadow: none;width: 150px;cursor: pointer" @click="goTo('carmen-talisman')" class="animated pulse slow infinite" />
					<img :data-src="require('@/assets/circle_tecunUman.png')" id="lugar" style="border: none;background: none;margin: 0;position: absolute;top: 201px;right: 242px;box-shadow: none;width: 150px;cursor: pointer" @click="goTo('tecun-uman')" class="animated pulse slow infinite"/>
					<img :data-src="require('@/assets/circle_ocos.png')" id="lugar" style="border: none;background: none;margin: 0;position: absolute;top: 352px;right: 311px;box-shadow: none;width: 150px;cursor: pointer" @click="goTo('ocos')" class="animated pulse slow infinite"/>
					<img :data-src="require('@/assets/circle_limones.png')" id="lugar" style="border: none;background: none;margin: 0;position: absolute;top: 249px;right: 642px;box-shadow: none;width: 150px;cursor: pointer" @click="goTo('limones')" class="animated pulse slow infinite"/>
				</div>
				<p style="margin: 0;">
					<a href="#/entrevistados">
						Entrevistados
					</a>
					<br />
					<a href="#/creditos">
						<span class="title">Créditos</span>
					</a>
				</p>
			</section>

            <!-- GRUPO: OCÓS -->
			<section>
				<section id="ocos" data-transition="fade" data-state="fotografia" :data-background-video="require('@/assets/Videos/00028.mp4')" data-background-video-loop data-background-video-muted data-background-size="cover" data-background-opacity="0.25" data-background-color="rgba(0,0,0,1.0)">
				<h3>Ocós</h3>
				<p>
					Nos ubicamos en la desembocadura del Río Suchiate, en el Océano Pacífico, en la región del Soconusco. Aquí se encuentra uno de los puntos de cruce irregular, caracterizado por los movimientos pendulares que diariamente llevan a cabo los habitantes locales por falta de trabajo.
				</p>
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Ocos/1) 46X70cm_CAMBIO.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Ocos/2) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Ocos/3) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Ocos/4) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Ocos/5) 46x70cmPASO.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Ocos/6) 100X66cm_CAMBIO_PASO.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Ocos/7) 46X70cm_CAMBIO.jpg')" style="max-width: 85%;"/>
					<p>
						<a href="#/mapa">
							<img :data-src="require('@/assets/map_white.svg')" style="width: 42px;border: none;background: none;margin: 0;box-shadow: none;"/>
						</a>
						<a href="#/inicio">
							<i class="material-icons" style="font-size: 42px; vertical-align: baseline; color: #FFFFFF;">home</i>
						</a>
					</p>
				</section>
			</section>

            <!-- GRUPO: LIMONES -->
			<section>
				<section id="limones" data-transition="fade" data-state="fotografia" :data-background-video="require('@/assets/Videos/01_03_00017.mp4')" data-background-video-loop data-background-video-muted data-background-size="cover" data-background-opacity="0.25" data-background-color="rgba(0,0,0,1.0)" >
					<h3>Limones</h3>
					<p>
						Encontramos otro punto de cruce irregular oculto entre una propiedad privada y un ejido ubicado al otro lado del río. Por sus características físicas dificulta el cruce a nado, las lanchas son un instrumento necesario para que bicicletas, motocicletas y personas circulen sobre la escorrentía del agua. Para los habitantes del ejido, el río es un lugar de esparcimiento para aliviar el sofocante calor del verano.
					</p>
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Limones/1) 46x70cm_CAMBIO.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Limones/2)100X66cm_CAMBIO.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Limones/3) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Limones/4) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Limones/5) 46x70cmPASO.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Limones/6)100x66cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Limones/7) 46x70cmPASO.jpg')" style="max-width: 85%;"/>
					<p>
						<a href="#/mapa">
							<img :data-src="require('@/assets/map_white.svg')" style="width: 42px;border: none;background: none;margin: 0;box-shadow: none;"/>
						</a>
						<a href="#/inicio">
							<i class="material-icons" style="font-size: 42px; vertical-align: baseline; color: #FFFFFF;">home</i>
						</a>
					</p>
				</section>
			</section>

            <!-- GRUPO: TECÚN UMÁN -->
			<section>
				<section id="tecun-uman" data-transition="fade" data-state="fotografia" :data-background-video="require('@/assets/Videos/00010.mp4')" data-background-video-loop data-background-video-muted data-background-size="cover" data-background-opacity="0.3" data-background-color="rgba(0,0,0,1.0)">
					<h3>Tecún Umán</h3>
					<p>
						Entre Ciudad Hidalgo y Tecún Umán se encuentra una de las zonas de paso más importantes entre México y Guatemala. A escasos 400 metros del puente internacional se conforma una zona de cruce irregular de personas y mercancías en las llamadas “cámaras” En sus bordes se puede ver gente pescando, nadando y lavando ropa.
					</p>
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Panoramicas/2) Tecún Umán 2.jpg')" style="max-width: 100%;"/>
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/1) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/2) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/3) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/4) 100X66cm_CAMBIO.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/5) 100x66cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/6) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/7)C46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/8) 100x66cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/TecunUman/9)46x70cm.jpg')" style="max-width: 85%;"/>
					<p>
						<a href="#/mapa">
							<img :data-src="require('@/assets/map_white.svg')" style="width: 42px;border: none;background: none;margin: 0;box-shadow: none;"/>
						</a>
						<a href="#/inicio">
							<i class="material-icons" style="font-size: 42px; vertical-align: baseline; color: #FFFFFF;">home</i>
						</a>
					</p>
				</section>
			</section>

			<!-- GRUPO: EL CARMEN TALISMAN -->
			<section>
				<section id="carmen-talisman" data-transition="fade" data-state="fotografia" :data-background-video="require('@/assets/Videos/03_03_00007.mp4')" data-background-video-loop data-background-video-muted data-background-size="cover" data-background-opacity="0.25" data-background-color="rgba(0,0,0,1.0)">
					<h3>El Carmen-Talismán</h3>
					<p>
						Entre dos pequeñas localidades se encuentra la aduana conocida como El Carmen. El cruce regular es por el puente internacional, mientras que el flujo irregular se da por debajo de éste, y tiene una organización social y espacial muy particular: el punto de cobro se encuentra en el traspatio de una casa por la cual ingresan mercancías y personas para cruzar el río.
					</p>
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/Panoramicas/1) El carmen Talismán 2.jpg')" style="max-width: 100%;"/>
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/1) 46x70cm.jpg')"/>
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/2) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/3) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/4.1) Frontera Talisman .jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/4.2)Frontera Talismán_1293.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/4.3)  Frontera Talismán_1299.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/4.4)  Frontera Talismán_1301.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/5) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/6) 46x70cm.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<img :data-src="require('@/assets/ElCarmenTalisman/7)100x66cm.jpg')" style="max-width: 85%;"/>
					<p>
						<a href="#/mapa">
							<img :data-src="require('@/assets/map_white.svg')" style="width: 42px;border: none;background: none;margin: 0;box-shadow: none;"/>
						</a>
						<a href="#/inicio">
							<i class="material-icons" style="font-size: 42px; vertical-align: baseline; color: #FFFFFF;">home</i>
						</a>
					</p>
				</section>
			</section>

            <!-- ENTREVISTADOS -->
			<section>
				<section id="entrevistados" data-transition="fade" data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<h4>Experiencias de trabajadoras y trabajadores circulares en Guatemala</h4>
					<span style="font-size: 2.4rem;">Historia familiar, infancia, escolaridad</span>
					<p style="font-size: 1.8rem;">
						Al concluir 2016, en la frontera sur de México con Guatemala se contabilizaron 700 mil cruces de migrantes circulares que trabajan del lado mexicano (Encuesta sobre Migración en la Frontera Sur) ¿Qué rostros e historias familiares hay detrás de las estadísticas? ¿Quienes son estos guatemaltecos? Empleadas domésticas, cargadores de bodega, jornaleros, albañiles, cocineras, meseros, comerciantes…
					</p>
					<span style="font-size: 2.4rem;">Trayectoria laboral</span>
					<p style="font-size: 1.8rem;">
						Algunos de estos trabajadores que cruzan la frontera han iniciado su trayectoria laboral en la infancia. Pasan a trabajar temporalmente “al otro lado” sin fijar su residencia en México, obligados por la falta de empleo en su propio país.
					</p>
					<p style="text-align: right; font-weight: lighter; font-style: italic; font-size: 0.7em">
						—Claudia Barrientos Arana de Arriaga
					</p>
				</section>

				<section data-transition="fade" data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<h4>Experiencias de trabajadoras y trabajadores circulares en Guatemala</h4>
					<span style="font-size: 2.4rem;">Paso por la frontera</span>
					<p style="font-size: 1.8rem;">
						Cruzar la frontera diariamente para ir a trabajar no es común. La movilidad fronteriza es un recurso vital para estos migrantes circulares, algunos de ellos tienen más de tres décadas atravesándola.
					</p>
					<span style="font-size: 2.4rem;">Relación con los mexicanos</span>
					<p style="font-size: 1.8rem;">
						Se considera la frontera como eje desde el cual se establecen complejos proceso de interacción e intercambio social, cultural y económico. En ese ir y venir pendular, guatemaltecos y mexicanos confluyen y entretejen sus relaciones.
					</p>
					<p style="text-align: right; font-weight: lighter; font-style: italic; font-size: 0.7em">
						—Claudia Barrientos Arana de Arriaga
					</p>
				</section>

				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<!-- Entrevistados -->
					<img :data-src="require('@/assets/Retratos/1)_Entrevista Rose Mary_1889.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<img :data-src="require('@/assets/Retratos/2) Entrevista Tío Sam_0663.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<img :data-src="require('@/assets/Retratos/3)_Entrevista Sra Petrona_1648.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<img :data-src="require('@/assets/Retratos/4)LAM_1479.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<img :data-src="require('@/assets/Retratos/5)_Entrevista Sra Karina_1384.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<img :data-src="require('@/assets/Retratos/6) _Entrevista Buki_0716.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<img :data-src="require('@/assets/Retratos/7)_Entrevista Sr Humberto_2018.jpg')" />
				</section>
				<section data-background-color="rgba(0,0,0,0.8)" data-state="fotografia">
					<img :data-src="require('@/assets/Retratos/8) _Entrevista Juanita_1064.jpg')" />
				</section>
				
				<!-- VIDEO (SE MUESTRA EN RECUADRO) -->
				<section data-background-color="rgba(0,0,0,0.9)" data-state="fotografia">
					<video data-autoplay :src="require('@/assets/Master.mp4')" controls></video>
					<p>
						<a href="#/mapa">
							<img :data-src="require('@/assets/map_white.svg')" style="width: 42px;border: none;background: none;margin: 0;box-shadow: none;"/>
						</a>
						<a href="#/inicio">
							<i class="material-icons" style="font-size: 42px; vertical-align: baseline; color: #FFFFFF;">home</i>
						</a>
					</p>
				</section>
			</section>

            <!-- CRÉDITOS -->
			<section id="creditos" data-transition="fade" data-background-color="rgba(0,0,0,0.8)" data-state="fotografia" style="margin-top: -0.5em;">
				<div class="row hide-on-small-only">
					<div class="col s12">
						<p style="font-size: 1rem;font-weight: bold;">
							Un Paisaje Fronterizo. Cruces e itinerarios en la línea México-Guatemala
						</p>
						<p style="font-size: 0.75rem;font-weight: bold;">
							Una producción del Laboratorio Audiovisual de Investigación Social del<br />
							Instituto de Investigaciones Dr. José María Luis Mora con el apoyo del CentroGeo<br />
							(Proyecto Región Transfronteriza México-Guatemala, CONACyT)
						</p>
					</div>
					<div class="col s4" style="font-size: 0.75rem;">
						<p>
							<span style="font-weight: bold;">Fotografías</span><br />
							Felipe Morales Leal
						</p>
						<p>
							<span style="font-weight: bold;">Registros audiovisuales</span><br />
							Carlos Hernández Marines
						</p>
						<p>
							<span style="font-weight: bold;">Textos</span><br />
							Mauricio Pablo Cervantes Salas
						</p>
						<p>
							<span style="font-weight: bold;">Guión y concepto</span><br />
							Felipe Morales Leal<br />
							Carlos Hernández Marines<br />
							Mauricio Pablo Cervantes Salas
						</p>
						<p>
							<span style="font-weight: bold;">Producción y coordinación general</span><br />
							Felipe Morales Leal<br />
							Lourdes Roca<br />
							Carlos Hernández Marines<br />
							Rodrigo Eduardo Colín
						</p>
						<p>
							<span style="font-weight: bold;">Museografía</span><br />
							Lorena Botello Ibarra<br />
							Diego Jesús Flores Olmedo
						</p>
						<p>
							<span style="font-weight: bold;">Identidad gráfica</span><br />
							Federico Martínez Montoya
						</p>
					</div>
					<div class="col s4" style="font-size: 0.75rem;">
						<p>
							<span style="font-weight: bold;">Dibujos</span><br />
							Lorena Botello Ibarra<br />
							Diego Jesús Flores Olmedo
						</p>
						<p>
							<span style="font-weight: bold;">Mapa</span><br />
							Gabriela Quiroz Cázares
						</p>
						<p>
							<span style="font-weight: bold;">Entrevistas</span><br />
							Claudia Inés Barrientos Arana de Arriaga
						</p>
						<p>
							<span style="font-weight: bold;">Entrevistados</span><br />
							Carina León Escalante<br />
							Rosemary Lorena de León Escalante<br />
							Petrona Ayala de López<br />
							Juana López de Girón<br />
							Marconi Monterroso<br />
							Efrén Maldonado<br />
							Armando Mazariegos
						</p>
						<p>
							<span style="font-weight: bold;">Montaje</span><br />
							Jesús Marmolejo<br />
							Erasto Roldán<br />
							I&I Herrería Arquitectónica
						</p>
						<p>
							<span style="font-weight: bold;">Material museográfico</span><br />
							I&I Herrería Arquitectónica
						</p>
					</div>
					<div class="col s4" style="font-size: 0.75rem;">
						<p>
							<span style="font-weight: bold;">Impresiones</span><br />
							Emic Digital
						</p>
						<p>
							<span style="font-weight: bold;">Agradecimientos</span><br />
							Gloria Marvic<br />
							Julia Ros Cuéllar<br />
							Marveli Robledo<br />
							Juan Bautista Hernández Andrés<br />
							Gabriela Quiroz Cázares<br />
							Juan Carlos Domínguez Virgen<br />
							María Eugenia García Gómez<br />
							María Eugenia Icaza Lomelí<br />
							Angélica Huerta Hernández<br />
							Gabriel González Arenas<br />
							Iván Caballero Hernández<br />
							Samantha Gutiérrez<br />
							Yessica Andrea Gómez Hilario<br />
							Nicolás Cruz Galicia<br />
							Daniela Isamar Ramírez Arteaga
						</p>
						<p>
							<span style="font-weight: bold;">Desarrollo web</span><br />
							Rodrigo Colín Rivera<br />
							Yolanda Irene Hernández Oliva<br />
							Astrid Ruiz Nava
							<!-- Astrid Ruiz Nava<br /> -->
							<!-- con el apoyo de <a href="https://revealjs.com">Reveal</a> -->
						</p>
					</div>
				</div>

				<!-- Créditos compactados para pantalla muy pequeña -->
				<div class="hide-on-med-and-up">
					<p style="font-size: 2.125rem;font-weight: lighter;">
						<span style="font-weight: bold;">Fotografías</span>
						Felipe Morales Leal

						<span style="font-weight: bold;">Registros audiovisuales</span>
						Carlos Hernández Marines

						<span style="font-weight: bold;">Textos</span>
						Mauricio Pablo Cervantes Salas

						<span style="font-weight: bold;">Guión y concepto</span>
						Felipe Morales Leal,
						Carlos Hernández Marines,
						Mauricio Pablo Cervantes Salas

						<span style="font-weight: bold;">Producción y coordinación general</span>
						Felipe Morales Leal,
						Lourdes Roca,
						Carlos Hernández Marines,
						Rodrigo Eduardo Colín

						<span style="font-weight: bold;">Museografía</span>
						Lorena Botello Ibarra,
						Diego Jesús Flores Olmedo

						<span style="font-weight: bold;">Identidad gráfica</span>
						Federico Martínez Montoya

						<span style="font-weight: bold;">Dibujos</span>
						Lorena Botello Ibarra,
						Diego Jesús Flores Olmedo

						<span style="font-weight: bold;">Mapa</span>
						Gabriela Quiroz Cázares

						<span style="font-weight: bold;">Entrevistas</span>
						Claudia Inés Barrientos Arana de Arriaga

						<span style="font-weight: bold;">Entrevistados</span>
						Carina León Escalante,
						Rosemary Lorena de León Escalante,
						Petrona Ayala de López,
						Juana López de Girón,
						Marconi Monterroso,
						Efrén Maldonado,
						Armando Mazariegos

						<span style="font-weight: bold;">Montaje</span>
						Jesús Marmolejo,
						Erasto Roldán,
						I&I Herrería Arquitectónica

						<span style="font-weight: bold;">Material museográfico</span>
						I&I Herrería Arquitectónica

						<span style="font-weight: bold;">Impresiones</span>
						Emic Digital

						<span style="font-weight: bold;">Agradecimientos</span>
						Gloria Marvic,
						Julia Ros Cuéllar,
						Marveli Robledo,
						Juan Bautista Hernández Andrés,
						Gabriela Quiroz Cázares,
						Juan Carlos Domínguez Virgen,
						María Eugenia García Gómez,
						María Eugenia Icaza Lomelí,
						Angélica Huerta Hernández,
						Gabriel González Arenas,
						Iván Caballero Hernández,
						Samantha Gutiérrez,
						Yessica Andrea Gómez Hilario,
						Nicolás Cruz Galicia,
						Daniela Isamar Ramírez Arteaga

						<span style="font-weight: bold;">Desarrollo web</span>
						Rodrigo Colín Rivera,
						Yolanda Irene Hernández Oliva,
						Astrid Ruiz Nava,
						<!-- con el apoyo de <a href="https://revealjs.com">Reveal</a> -->
					</p>
				</div>

				<p>
					<a href="#/mapa">
						<img :data-src="require('@/assets/map_white.svg')" style="width: 42px;border: none;background: none;margin: 0;box-shadow: none;"/>
					</a>
					<a href="#/inicio">
						<i class="material-icons" style="font-size: 42px; vertical-align: baseline; color: #FFFFFF;">home</i>
					</a>
				</p>
			</section>
        </div>
    </div>
  </div>
</template>

<script>
import Reveal from 'reveal.js';
import 'reveal.js/dist/reveal.css';
import 'reveal.js/dist/theme/black.css';

import 'materialize-css/dist/css/materialize.min.css';
// import 'materialize-css/dist/js/materialize.min'; // JavaScript

export default {
  name: 'ExpoReveal',
  mounted() {
    Reveal.initialize({
      // Display presentation control arrows
      controls: true,

      // Help the user learn the controls by providing hints, for example by
      // bouncing the down arrow when they first encounter a vertical slide
      controlsTutorial: true,

      // Determines where controls appear, "edges" or "bottom-right"
      controlsLayout: 'bottom-right',

      // Visibility rule for backwards navigation arrows; "faded", "hidden"
      // or "visible"
      controlsBackArrows: 'visible',

      // Display a presentation progress bar
      progress: false,

      // Display the page number of the current slide
      slideNumber: false,

      // Add the current slide number to the URL hash so that reloading the
      // page/copying the URL will return you to the same slide
      hash: false,

      // Push each slide change to the browser history. Implies `hash: true`
      history: false,

      // Enable keyboard shortcuts for navigation
      // keyboard: true,
      keyboard: false,

      // Enable the slide overview mode
      // overview: true,

      // Vertical centering of slides
      center: true,

      // Enables touch navigation on devices with touch input
      touch: false,

      // Loop the presentation
      loop: false,

      // Change the presentation direction to be RTL
      rtl: false,

      // See https://github.com/hakimel/reveal.js/#navigation-mode
      navigationMode: 'default',

      // Randomizes the order of slides each time the presentation loads
      shuffle: false,

      // Turns fragments on and off globally
      fragments: true,

      // Flags whether to include the current fragment in the URL,
      // so that reloading brings you to the same fragment position
      fragmentInURL: false,

      // Flags if the presentation is running in an embedded mode,
      // i.e. contained within a limited portion of the screen
      embedded: false,

      // Flags if we should show a help overlay when the questionmark
      // key is pressed
      help: true,

      // Flags if speaker notes should be visible to all viewers
      showNotes: false,

      // Global override for autoplaying embedded media (video/audio/iframe)
      // - null: Media will only autoplay if data-autoplay is present
      // - true: All media will autoplay, regardless of individual setting
      // - false: No media will autoplay, regardless of individual setting
      autoPlayMedia: null,

      // Global override for preloading lazy-loaded iframes
      // - null: Iframes with data-src AND data-preload will be loaded when within
      //   the viewDistance, iframes with only data-src will be loaded when visible
      // - true: All iframes with data-src will be loaded when within the viewDistance
      // - false: All iframes with data-src will be loaded only when visible
      preloadIframes: null,

      // Number of milliseconds between automatically proceeding to the
      // next slide, disabled when set to 0, this value can be overwritten
      // by using a data-autoslide attribute on your slides
      autoSlide: 0,

      // Stop auto-sliding after user input
      autoSlideStoppable: true,

      // Use this method for navigation when auto-sliding
      autoSlideMethod: Reveal.navigateNext,

      // Specify the average time in seconds that you think you will spend
      // presenting each slide. This is used to show a pacing timer in the
      // speaker view
      defaultTiming: 120,

      // Enable slide navigation via mouse wheel
      mouseWheel: false,

      // Hide cursor if inactive
      hideInactiveCursor: true,

      // Time before the cursor is hidden (in ms)
      hideCursorTime: 5000,

      // Hides the address bar on mobile devices
      hideAddressBar: true,

      // Opens links in an iframe preview overlay
      // Add `data-preview-link` and `data-preview-link="false"` to customise each link
      // individually
      previewLinks: false,

      // Transition style
      transition: 'convex', // none/fade/slide/convex/concave/zoom

      // Transition speed
      transitionSpeed: 'slow', // default/fast/slow

      // Transition style for full page slide backgrounds
      backgroundTransition: 'fade', // none/fade/slide/convex/concave/zoom

      // Number of slides away from the current that are visible
      viewDistance: 3,

      // Parallax background image
      // parallaxBackgroundImage: 'https://s3.amazonaws.com/hakim-static/reveal-js/reveal-parallax-1.jpg', // e.g. "'https://s3.amazonaws.com/hakim-static/reveal-js/reveal-parallax-1.jpg'"
      parallaxBackgroundImage: require('@/assets/Panoramicas/1) El carmen Talismán 2.jpg'), // e.g. "'https://s3.amazonaws.com/hakim-static/reveal-js/reveal-parallax-1.jpg'"

      // Parallax background size
      parallaxBackgroundSize: '3391px 1080px', // CSS syntax, e.g. "2100px 900px"

      // Number of pixels to move the parallax background per slide
      // - Calculated automatically unless specified
      // - Set to 0 to disable movement along an axis
      parallaxBackgroundHorizontal: null,
      parallaxBackgroundVertical: null,

      // The display mode that will be used to show slides
      display: 'block'
    });
  },
  methods: {
	// Hipervinculo a otras diapositivas.
	// Recibe el id de la diapositiva como parámetro (link)
	goTo(link){
		let url = location.protocol + '//' + location.host + location.pathname;
		window.location.href = url + '#/' + link;
	}
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- <style scoped> -->
<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
  /* height: 90vh; */
  height: 100%;
}

/* My styles */
.fotografia .reveal .controls .navigate-right {
  display: none;
}
.fotografia .reveal .controls .navigate-left {
  display: none;
}
.menu .reveal .controls .navigate-right {
  display: none;
}
</style>
