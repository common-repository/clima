<?php

/*

Plugin Name: clima

Plugin URI: http://www.rodrigoart.com.ar

Description: Levanta imagen y temperatura de yahoo clima

Author: Rodrigo Recasens

Version: 9

Author URI: http://www.rodrigoart.com.ar

*/

function combertir_viento ($wind_direction) {

if ($wind_direction > 348.75 || $wind_direction < 11.25)
			$wind_direction_converted = "N";
		else if ($wind_direction > 11.25 || $wind_direction < 33.75)
			$wind_direction_converted = "NNE";
		else if ($wind_direction > 33.75 || $wind_direction < 56.25)
			$wind_direction_converted = "NE";
		else if ($wind_direction > 56.25 || $wind_direction < 78.75)
			$wind_direction_converted = "ENE";
		else if ($wind_direction > 78.75 || $wind_direction < 101.25)
			$wind_direction_converted = "E";
		else if ($wind_direction > 101.25 || $wind_direction < 123.75)
			$wind_direction_converted = "ESE";
		else if ($wind_direction > 123.75 || $wind_direction < 146.25)
			$wind_direction_converted = "SE";
		else if ($wind_direction > 146.25 || $wind_direction < 168.75)
			$wind_direction_converted = "SSE";
		else if ($wind_direction > 168.75 || $wind_direction < 191.25)
			$wind_direction_converted = "S";
		else if ($wind_direction > 191.25 || $wind_direction < 213.75)
			$wind_direction_converted = "SSW";
		else if ($wind_direction > 213.75 || $wind_direction < 236.25)
			$wind_direction_converted = "SW";
		else if ($wind_direction > 236.25 || $wind_direction < 258.75)
			$wind_direction_converted = "WSW";
		else if ($wind_direction > 258.75 || $wind_direction < 281.25)
			$wind_direction_converted = "W";
		else if ($wind_direction > 281.25 || $wind_direction < 303.75)
			$wind_direction_converted = "WNW";
		else if ($wind_direction > 303.75 || $wind_direction < 326.25)
			$wind_direction_converted = "NW";
		else if ($wind_direction > 326.25 || $wind_direction < 348.75)
			$wind_direction_converted = "NNW";
		else $wind_direction_converted = null;
 
		return $wind_direction_converted;
}

function combertir_codigo ($codigo) {

switch ($codigo):
     case 0: $texto = "tornado";
case 1: $texto = "tormenta tropical";
return $texto; break;
case 2: $texto = "huracanes";
return $texto; break;
case 3: $texto = "fuertes tormentas";
return $texto; break;
case 4: $texto = "tormentas eléctricas";
return $texto; break;
case 5:$texto = "lluvia y nieve mezcladas";
return $texto; break;
case 6: $texto = "lluvias y aguanieve mixta";
return $texto; break;
case 7: $texto = "nieve y aguanieve mixta";
return $texto; break;
case 8: $texto = "llovizna helada";
return $texto; break;
case 9: $texto = "llovizna";
return $texto; break;
case 10: $texto = "lluvia helada";
return $texto; break;
case 11: $texto = "lluvias";
return $texto; break;
case 12:$texto = "lluvias";
return $texto; break;
case 13: $texto = "copos de nieve";
return $texto; break;
case 14: $texto = "nevadas ligeras";
return $texto; break;
case 15: $texto = "nieve que sopla";
return $texto; break;
case 16: $texto = "nieve";
return $texto; break;
case 17: $texto = "granizo";
return $texto; break;
case 18: $texto = "aguanieve";
return $texto; break;
case 19: $texto = "polvo";
return $texto; break;
case 20: $texto = "niebla";
return $texto; break;
case 21: $texto = "Haze";
return $texto; break;
case 22: $texto = "humo";
return $texto; break;
case 23: $texto = "ventoso";
return $texto; break;
case 24: $texto = "ventoso";
return $texto; break;
case 25: $texto = "frío";
return $texto; break;
case 26: $texto = "nubes";
return $texto; break;
case 27: $texto = "Parcialmente nublado (noche)";
return $texto; break;
case 28: $texto = "Parcialmente nublado (día)";
return $texto; break;
case 29: $texto = "Parcialmente nublado (noche)";
return $texto; break;
case 30: $texto = "Parcialmente nublado (día)";
return $texto; break;
case 31: $texto = "clara (noche)";
return $texto; break;
case 32: $texto = "soleado";
return $texto; break;
case 33: $texto = "despejado (noche)";
return $texto; break;
case 34: $texto = "despejado (día)";
return $texto; break;
case 35: $texto = "la lluvia y el granizo mezclado";
return $texto; break;
case 36: $texto = "caliente";
return $texto; break;
case 37: $texto = "tormentas eléctricas aisladas";
return $texto; break;
case 38: $texto = "tormentas eléctricas aisladas";
return $texto; break;
case 39: $texto = "tormentas eléctricas aisladas";
return $texto; break;
case 40: $texto = "lluvias aisladas";
return $texto; break;
case 41: $texto = "nieve";
return $texto; break;
case 42: $texto = "nevadas aisladas";
return $texto; break;
case 43: $texto = "nieve";
return $texto; break;
case 44: $texto = "Parcialmente nublado";
return $texto; break;
case 45: $texto = "Tormentas";
return $texto; break;
case 46: $texto = "nevadas";
return $texto; break;
case 47: $texto = "Tormentas aisladas";
return $texto; break;
default:
$texto = "error!";
endswitch;

}


function show_clima($mostrar = "r") {
	
//levanto el feed y lo parseo con php
$url = get_option('url_feed');
$rss = file_get_contents($url);
$yWeather = simplexml_load_string(str_replace('yweather:', '', $rss));

if ($url == "" or $url == null) {
echo "must enter the feed url for clima plugin";
} else {

$aConditions = array();
foreach($yWeather->channel->item->condition->attributes() as $a => $b) {
   $cleanStr = array("'" => '', '"' => '', '=' => '', $a => '');
   $aConditions[$a] = trim(strtr($b->asXML(), $cleanStr));
}

($aConditions);


$cConditions = array();
foreach($yWeather->channel->item->forecast->attributes() as $c => $d) {
   $cleanStr = array("'" => '', '"' => '', '=' => '', $c => '');
   $cConditions[$c] = trim(strtr($d->asXML(), $cleanStr));
}

($cConditions);

$xConditions = array();
foreach($yWeather->channel->item->forecast[1]->attributes() as $x => $z) {
   $cleanStr = array("'" => '', '"' => '', '=' => '', $x => '');
   $xConditions[$x] = trim(strtr($z->asXML(), $cleanStr));
}

($xConditions);


$eConditions = array();
foreach($yWeather->channel->atmosphere->attributes() as $e => $f) {
   $cleanStr = array("'" => '', '"' => '', '=' => '', $e => '');
   $eConditions[$e] = trim(strtr($f->asXML(), $cleanStr));
}

($eConditions);

$gConditions = array();
foreach($yWeather->channel->wind->attributes() as $g => $h) {
   $cleanStr = array("'" => '', '"' => '', '=' => '', $g => '');
   $gConditions[$g] = trim(strtr($h->asXML(), $cleanStr));
}

($gConditions);

$temperatura = $aConditions['temp'];
$humedad = $eConditions['humidity'];
$maxima = $cConditions['high'];
$minima = $cConditions['low'];
$direccion_viento = combertir_viento($gConditions['direction']);
$velocidad_viento = $gConditions['speed'];
$codigo_clima = $aConditions['code'];
$texto_clima = combertir_codigo($aConditions['code']);
$manana_maxima = $xConditions['high'];
$manana_minima = $xConditions['low'];
$manana_estado = combertir_codigo($xConditions['code']);
switch ($mostrar):
     case temperatura:
         echo $temperatura;
         break;
     case humedad:
         echo $humedad;
         break;
     case maxima:
         echo $maxima;
         break;
  case minima:
         echo $minima;
         break;
case direccion_viento:
         echo $direccion_viento;
         break;
case velocidad_viento:
         echo $velocidad_viento;
         break;
case codigo_clima:
         echo $codigo_clima;
         break;
case texto_clima:
         echo $texto_clima;
         break;
case manana_maxima:
         echo $manana_maxima;
         break;
case manana_minima:
         echo $manana_minima;
         break;
case manana_estado:
         echo $manana_estado;
         break;
     default:
echo "<div id=\"clima\"><center>";



//tomo el contenido de la etiqueta description.

$imagen = $yWeather->channel->item->description;

// uso esta funcion para seprar solo la etiqueta img de todo lo que hay en description.

$numResults = preg_match( "/<img .+?\/?>/im", $imagen, $results );

   

       

   

      if( $numResults > 0 )

   

      {

   

          // Got some results.

   

          // $numResults will never be more than 1 (one).

   

          echo( $results[ 0 ] );

   

      }

   

      else

  

      {

            echo "fallo";



      } 



//imprimo la temperatura y luego el campo unidad

echo "<br>";

echo $aConditions['temp'];

echo get_option('unidad');



echo "</center></div>";
 endswitch;



}
}



function clima_options() {



	echo "<div style=\"margin-left:200px; width:250px;\" class=\"wrap\">";



	echo "<h2>Clima local</h2>";
echo "aca pones la url del feed, ejemplo: http://weather.yahooapis.com/forecastrss?p=ARBA1809&u=c , en la p de la url va el codigo postal de la ciudad de cual queres el clima, lo podes sacar de aca ( http://weather.yahoo.com/ ), y en la u, va c si lo queres en centigrados y f en farnheit 911, jeje<br>";



	echo '<form method="post" action="options.php">';



	wp_nonce_field('update-options');



	echo 'Url del feed: <input type="text" name="url_feed" value="' .get_option('url_feed') . '" /><br/><br/>';

echo 'Unidad de la temperatura (aca podes poner simplemente un ºC o ºF o le podes poner "Grados ºC", esto sale al lado del numerito: <input type="text" name="unidad" value="' .get_option('unidad') . '" /><br/><br/>';

	echo '<input type="hidden" name="action" value="update" />';

echo '<input type="hidden" name="page_options" value="url_feed,unidad" />';

	


	echo '<p class="submit">



	<input type="submit" name="Submit" value="Salvar" />



	</p>';



	echo "</div> Por ultimo donde quieras levantar la temperatura y la imagen del clima invocas la funcion show_clima() o podes usar el WIDGET"; ?>

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=faldaconhueso%40gmail%2ecom&lc=AR&item_name=rodrigoart&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted" target="_blank">DONATE</a>

<?php



}

//EL widget!


function clima_register() {







	function clima_widget($args) {



	



		extract($args);



	   echo $before_widget; 



	   echo $before_title . $after_title; 



	   show_clima();			



	   echo $fssText;



	   echo $after_widget; 



	   



      }


register_sidebar_widget('Clima WidGet','clima_widget');

}


add_action('init', 'clima_register');

	
function clima_add_menu(){	
add_menu_page('clima', 'clima', 7, __FILE__, 'clima_options');

	add_submenu_page(__FILE__, 'clima', 'clima', 7, __FILE__, 'clima_options');

	
}
if (function_exists('add_action')) {
	add_action('admin_menu', 'clima_add_menu'); 
}

?>
