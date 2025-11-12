# 6GEI311-lab5
# Rapport de laboratoire

## Résumé
En résumé, ce laboratoire agissait comme une simulation d’une panne serveur. En effet, les deux ordinateurs qui comportaient les pages web servaient de service à offrir, et l’ordinateur exécutant **nginx** servait d’égaliseur de charge.  

Dans ce cas-ci, les deux pages web étaient différentes, mais dans un contexte réel, elles auraient pu êtres identiques. Ainsi, nous avons pu observer comment **nginx** effectuait la gestion des services, puisqu’il faisait la répartition des connexions entre les serveurs. Lorsque l’un de ceux-ci tombait « en panne », **nginx** redirigeait automatiquement la connexion vers un autre serveur disponible.

Au niveau de l'architecture, l'égalisateur de charge est un dispositif utile afin d'éviter un arrêt de service si jamais un des deux serveur arrête de fonctionner.
C'est un atout incontournable pour la gestion de service et permettre une bonne disponibilité.

---

## Réponses aux questions

**6.** Nous n’avons plus accès à la page web.  

**16.** À chaque fois que la page est rafraîchie, l’affichage de la page alterne entre la page du membre A et celle du membre B.  

**17.**  
     a) Nous n’avons plus accès à la page web.  
     b) Nous n’avons plus accès à la page web du membre A, mais la page web du membre B est affichée à la place.  
