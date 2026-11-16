# peche-carte

Carte IGN (Plan IGN v2 et photographies aériennes, Géoplateforme) pour placer le point d'une pêche de sauvetage et obtenir ses coordonnées en Lambert 93 (EPSG:2154).

- « Me localiser » : position GPS du téléphone (précision affichée).
- Toucher la carte ou déplacer le repère pour ajuster le point.
- Altitude du terrain au point : service altimétrique IGN (RGE ALTI), à défaut altitude GPS du téléphone.
- « Envoyer à l'appli » : renvoie X/Y et l'altitude dans l'appli de saisie des pêches de sauvetage.

Conversion WGS84 → Lambert 93 selon les formules IGN (ellipsoïde GRS80).
Fond de carte © IGN – Géoplateforme. Carte : Leaflet 1.9.4 (BSD-2).

Adresse : https://eulaniem.github.io/peche-carte/
