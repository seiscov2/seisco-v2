Framework destiné à résoudre des problèmes d'optimisation avec différents optimiseurs. Projet à caractère académique, débuté par Kamel BELKHELLADI en 2006. Cette version est une fork entièrement repensée par Jérôme SCOHY et Bruno BOI.

Une application complète utilisant SEISCO s'articule en 3 parties: le Framework SEISCO, le type de problème et la méthode d'optimisation.

Le Framework contient un ensemble de classes-outils servant à développer les problèmes et les méthodes d'optimisations en gardant un axe commun.

L'unique type de problème intégré, pour l'instant, est appelé Capacitated Arc Routing Problem. Le CARP représente des problèmes de tournées sur arcs, comme le sont le ramassage des ordures, le salage des routes, la vérifications de lignes à haute tension…

Deux méthodes de résolution sont en cours d'implémentation, basées sur les algorithmes génétiques et les algorithmes à colonies de fourmis. Seul le premier est fonctionnel pour le moment.

SEISCO utilise la plateforme multi-agents appelée JADE (http://jade.tilab.com/), l'Apache CommonCodecs (http://commons.apache.org/codec/) ainsi que SnakeYAML (http://code.google.com/p/snakeyaml/).