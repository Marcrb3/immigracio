# Mapes i Open Data: Localització, visualització i anàlisi de geodades.
<h1>Pràctica final</h1>
  
<h3>El contingut d'aquest repositori es fonamenta en un <strong>visor web</strong> en el que podem observar les taxes d'immigració de la ciutat de Barcelona representades en forma de mapes temàtics.</h3>
<p> La metodologia emprada per a realitzar la web ha estat la seguent:</p>
<p> - S'han descarregat les dades d'immigració per barris del portal de dades obertes de l'Ajuntament de Barcelona, en format CSV. Anàlogament, s'ha descarregat dues capes vectorials en format shape (.shp), corresponents als barris i districtes de la ciutat. </p>
<p> - S'ha fet un join entre la taula d'immigració i la capa de barris. Seguidament, hem calculat la mitjana d'immigració entre els barris d'un districte per generar una nova capa referent als districtes. </p>
<p> - Mitjançant QGIS, s'han treballat i guardat les capes de barris i districtes en format GeoJSON i projecció WGS84 per tal de carregarles al nostre visor </p>
<p> - Amb totes les dades disponibles, hem programat el nostre visor a través de Leaflet. Hem integrat la nostra capa GeoJSON a través d'una llibreria AJAX i posteriorment hi hem integrat algunes funcions per modificar-ne la visualització i fer-lo una mica interactiu.</p>
<p> - A través de Mapbox Studio, hem generat estils personalitzats i posteriorment els hem integrat al nostre visor com a TileSets </p>
