# SpeedGuard V47 — estimació visual de distància

- Estimació monocular aproximada basada en la mida aparent dels objectes.
- Llindars independents per a persones, vehicles motoritzats i bicicletes/patinets.
- Alertes configurables per categoria, so, vibració (si el navegador ho permet) i halo visual.
- Les etiquetes dels objectes mostren una distància aproximada.
- La vista de càmera manté tota l'amplada i ja no limita la imatge a una fracció petita de la pantalla.
- Es manté el canvi entre velocitat/radars i càmera amb botons i gest lateral.

Classes del model COCO-SSD: person, car, motorcycle, bus, truck, bicycle. Els patinets no tenen classe pròpia i poden no detectar-se o classificar-se com bicicleta/motocicleta.

**Limitació important:** la distància és una estimació no calibrada d'una sola càmera. El camp de visió, zoom/crop, angle, mida real i errors de detecció poden causar desviacions importants. No s'ha de fer servir per prendre decisions de conducció ni com a sistema de seguretat.
