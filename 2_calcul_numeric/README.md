# 2. Càlcul Numèric

## Errors

Material UPC:

* [Mòdul 1 - Errors i representació dels nombres](https://atenea.upc.edu/pluginfile.php/4580391/mod_folder/content/0/M%C3%B2dul%201%20Errors%20i%20representaci%C3%B3%20dels%20nombre.pdf?forcedownload=1)
* [Llista de problemes C2](https://atenea.upc.edu/pluginfile.php/4580390/mod_resource/content/4/Problemes_Contingut_2_FOMA.pdf)

Recursos propis:

* [Resum de la teoria d'errors necessària per fer els exercicis](./2_1_errors/resum_errors.jpg)

## Taylor

Material UPC:

* [Mòdul 2 - Aproximació: Polinomi de Taylor i error de truncament](https://atenea.upc.edu/pluginfile.php/4580391/mod_folder/content/0/M%C3%B2dul%202%20Aproximaci%C3%B3%20Polinomi%20de%20Taylor.pdf?forcedownload=1)
* [Llista de problemes C2](https://atenea.upc.edu/pluginfile.php/4580390/mod_resource/content/4/Problemes_Contingut_2_FOMA.pdf)

Recursos externs:

* [Vídeo de youtube que explica que és el polinomi de Taylor i dedueix d'on surten els coeficients que es fan servir](https://youtu.be/3VwDLy_0L5E)

Recursos propis:

* Geogebra d'exemple d'aproximació amb Taylor: https://www.geogebra.org/classic/gq7rnqyu
* Geogebra dels exercicis 1 i 2: https://www.geogebra.org/classic/vwwjeshw
* Geogebra de l'exercici 4: https://www.geogebra.org/classic/tj3qradu
* Geogebra de l'exercici 5: https://www.geogebra.org/classic/pjkymgnu
* Resolució de l'exercici 5: https://youtu.be/FudVYBNXdHs
* [Explicació exercici cota teòrica del test](./2_1_errors/Explicacio_exercici_cota_teorica_del_test.pdf)

## Zeros de funcions

Material UPC:

* [Presentació sobre Zeros de Funcions](https://atenea.upc.edu/pluginfile.php/4580391/mod_folder/content/0/M%C3%B2dul%203%20Apunts%20zeros.pdf?forcedownload=1)
* [Mètode de la bisecció amb matlab](https://atenea.upc.edu/pluginfile.php/4580397/mod_page/content/7/Zeros_Biseccio.html)
* [Mètodes iteratius amb matlab](https://atenea.upc.edu/pluginfile.php/4580397/mod_page/content/7/Zeros_Newton.html)

Recursos propis:

* Geogebra d'exemple de bisecció: https://www.geogebra.org/classic/zkm7bg7b
* [Com derivar una funció amb matlab](https://youtu.be/k6j3ssb_KSg)
* Geogebra d'exemple de Newton-Raphson que no convergeix: https://www.geogebra.org/classic/jzs4dgy7

```matlab
% zero amb Newton-Raphson
format long g;
f=@(x) 1/(1+x^2) - 1/2;
df=@(x) -(2*x)/(x^2 + 1)^2;
x0=2; % convegergeix a -1, no a 1!!!
n=60;
newton(f,df,x0,n)
```

## Integració numèrica

Material UPC:

* [Presentació sobre Integració Numèrica](https://atenea.upc.edu/pluginfile.php/4580391/mod_folder/content/0/M%C3%B2dul%204%20Apunts%20%20integraci%C3%B3.pdf?forcedownload=1)
* [Mètode dels trapecis i Mètode de Simpson](https://atenea.upc.edu/pluginfile.php/4580397/mod_page/content/7/Integracio_numeric_nou.html)

Recursos propis:

* Geogebra d'exemple de trapecis: https://www.geogebra.org/classic/vptqdx9b
* Geogebra d'exemple de Simpson: https://www.geogebra.org/classic/zt8wzqm6
* Resolució de l'exemple anterior: [punts interseccio](./2_2_integracio_numerica/exercici_a_classe_PUNTS_INTERSECCIO.m) i [area entre les dues corbes](./2_2_integracio_numerica/exercici_a_classe_AREA_ENTRE_LES_DUES_CORBES.m)

## Primitives

Material UPC:

* [Contingut 2. Càlcul numèric i càlcul de primitives - APARTAT 4 -](https://atenea.upc.edu/pluginfile.php/4580390/mod_resource/content/4/Problemes_Contingut_2_FOMA.pdf)

Recursos propis:

* Geobrebra de l'interpretació de l'integral definida: https://www.geogebra.org/classic/paxqtgyj
