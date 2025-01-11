Com a informació bàsica del meu programa crec que es poden tenir en compte dues coses importatnts:

- Lectura de dades:
  Quan fem la lectura dels fitxers d'assignatures, just abans del main, ordenem aquestes una llista d'assignatures de manera que totes les que son de tipus "g" es posen abans que les de tipus "r".
  Els fitxers que es generen en aquesta funció són la llista d'assignatures, la llista d'incompatibilitats i els diferents grau-curs que hi ha.
  
- Poda a la solució òptima:
  Al fer la poda per trobar la millor solució, he fet el càlcul de la desviació ideal (màxima desviació que pot arribar a tenir una solució parcial) intentant posar les assignatures que hi falten el màxim          allunyades de la mitjana d'aquell moment. Per a això les he considerat totes a mig camí entre la mitjana i l'extrem més llunya dels torns (torns 0 o l'últim). Amb tota probabilitat no deu ser la millor poda,     ni la que es fa servir a les proves penjades a l'enunciat de la pràctica.  Així doncs,  hi ha una prova que està penjada a l'enunciat de la pràctica, concretament a la prova "./ p2 -m - cr 2 - gc 2               assignatures_poques .txt", que a mi em tarda molt més temps a acabar(uns 500 s).

  Per tant, si que és cert que és pitjor en el sentit que tarda més, però millor en el sentit que, a part de trobar la que està al moodle (vaig fer escriure cada cop que modificava la solució òptima), en troba     una amb una dispersió més gran, per tant millor que la trobada a les proves fetes a l'enunciat de la pràctica.

 
