# 240032 Problems FEM 2D
Some Worked examples on 2D-FEM. See FEM Introduction Course at  Toni Susin's Numerical Factory 

https://numfactory.upc.edu/web/FiniteElements.html

* Plane Elasticity. Meshing with linear triangular elements. An example with 2 Triangles. `planarElasticity2Triangles.pdf`. See, at the same web, the presentation https://numfactory.upc.edu/web/FiniteElements/Guions/T4-MN-StructuralFEM2D.pdf, page 36
* Examen Final 20 de Gener de 2016. **Problema 1**. `Examen_20_Gener_2016_Problema1.pdf`
* Examen Final 2016-17 Quad1 **Problema 5**. `Ex_Final_Q1-2016-17_Problema5.pdf` 
* Examen Final 2016-17 Quad2 **Problema 4**. `Ex_Final_Q2-2016-17_Problema4.pdf` 
  * **Fe d'errors:**  A la figura amb els nodes locals (on el nodes globals estan marcats en vermell) hi ha un error. El segon node local de l'element 2
  hauria d'estar a l'angle recte del triangle i llavors els nodes 1 i 3 es posarien de manera que 1,2,3 anessin en sentit anti-horari. No afecta el càlcul
  de les components de la K (matriu de rigidesa global). En canvi, al càlcul de F<sub>4</sub>, on posa F<sup>2</sup><sub>3</sub> (3a. component del vector
  de forces del 2on. element) hauria de posar F<sup>2</sup><sub>1</sub> (1a. component del vector forces del 2on. element). El resultat per F<sub>4</sub>
  òbviament no canvia: F<sub>4</sub> = 5/3. Nota: això ja està corregit a la versió actual 
* Examen Re-Avaluació 2016-17 **Problema 4**. `Ex_ReAvaluacio-2016-17_Problema4.pdf`
* Examen Final 20 de Gener de 2016. **Problema 2**. `Examen_20_Gener_2016_Problema2.pdf`
* Examen Final 20 de Gener de 2016. **Problema 3**. `Examen_20_Gener_2016_Problema3.pdf`
* Examen Final 2017-18 Quad1 **Problema 4**. `Ex_Final_Q1-2017-18_Problema4.pdf`
* Examen Final 2017-18 Quad2 **Problema 2**. `Ex_Final_Q1-2017-18_Problema2.pdf`
* Examen Re-Avaluació 2017-18 **Problema 2**. `Ex_ReAvaluacio-2017-18_Problema2.pdf`
* Examen Final 2018-19 Quad1 **Problema 2**. `Ex_Final_Q1-2018-19_Problema2.pdf`
* Examen Final 2018-19 Quad2 **Problema 2**. `Ex_Final_Q2-2018-19_Problema2.pdf`
* Examen Re-Avaluació 2018-19 **Problema 2**. `Ex_ReAvaluacio-2018-19_Problema2.pdf`
* Examen Final 2019-20 Quad1 **Problema 2**. `Ex_Final_Q2-2019-20_Problema2.pdf`
* Examen Final 2019-20 Quad2 **Problema T4**. `Ex_Final_Q2-2019-20_ProblemaT4.pdf`

Moreover,
* T2-MN-FEM2D.pdf. Author: prof. Toni Susin. This is the notes' original version 
 as they first uploaded at the _Numerical Factory_. The page numbers for the
 formulas referred in the problems' solutions are those in this document. 

All exercises are completely solved and explained.

**Disclaimer:** this stuff is provided 'as is'. Please, check it (just in case you find it useful), but it's worth you try to write all the programs and do the exercises on your own.

If you find any mistakes (or have any suggestions), please report them to

juan.ramon.pacha@upc.edu

Many thanks,

J.R.
