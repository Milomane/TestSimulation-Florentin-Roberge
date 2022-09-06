# TestSimulation
Florentin Roberge
Temps total de travail : Environs 4h40min

Pendant se projet j'ai réalisé :
- Un point GPS
- Se point possède un material avec une emission rouge de (255, 0, 0)
- Un script qui permet de placé la sphere à n'importe quelle coordonée GPS sur le globe
- La position GPS est modifiable en Edit Mode et la position de la sphere se met à jour
- Un GUI composé de 2 sliders qui permet de modifier la position de la sphere en latitude et longitude ainsie qu'un affichage du nom et de la latitude et la longitude en question

- J'ai utilisé la texture water_NM comme normal map dans le shader du globe
- J'ai modifié le shader EarthShader pour prendre en compte la normal map dans le calcul de la lumière
- J'ai modifié le shader EarthShader pour calculer la lumière spéculaire sur le globe en essayant de m'approcher du rendu donné sur le doc
- Un script qui permet au runtime de charger le fichier externe water_mask.png dans une texture 2D et de l'appliqué dans la texture du material du globe
- J'ai modifier le shader du globe pour que le spéculaire ne s'applique que sur l'océan

Additionnel :
- J'ai appris les bases de script des custom shader.
- J'ai réalisé un document décrivant les étapes de mon travail ainsie que mon organisation pour sa réalisation. Si joint dans le zip.

Amélioration possible :
- Qualité du de la normal map et speculaire
- Possibilité de tapé précisément la latitude et longitude hors editeur
