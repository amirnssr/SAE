> NASSIRI Amir et KHALDI Mohamed



# Introduction



Vous trouverez dans ce rapport tous les détails concernant la réalisation du site web sur la rénovation de l'IUT de Vélizy-Villacoublay. Le rapport se divisera en plusieurs points, où nous aborderons en détails le cheminement de pensée qui nous a permis de mener à bien la conception de notre site web, ainsi que les outils utilisés lors de sa réalisation. Vous pourrez trouver le résultat final de notre site web sur [githack en cliquant ici](https://raw.githack.com/amirnssr/SAE/main/pageprincipale.html)



# Conception



## Brainstorming



> Tout d'abord, la tâche a été de déterminer comment se présentera notre site web, ainsi que quelles informations celui-ci sera amené à renseigner.



***



Celui-ci sera logiquement consitutué d'**une page d'accueil**, qui aura pour objectif de présenter l'IUT avant la rénovation, à l'aide de photographies de celle-ci puis de présenter l'université après la rénovation, notamment avec un plan satellite, afin d'avoir un comparatif clair avant / après, ainsi que des informations essentielles telles que l'*adresse* et le *numéro de téléphone* de l'IUT. Cela permettra d'avoir l'idée générale de la rénovation directement sur la page d'accueil. Nous pourrons ainsi parler des détails de la rénovation tels que le planning, les objectifs de cette rénovation, ainsi que les moyens employés pour cette rénovation dans trois pages bien distinctes, auxquelles nous pourrons accéder directement via une barre de navigation présente sur le haut de toutes nos pages webs.



---



**Le planning** sera un tableau, qui présentera les différentes étapes de la rénovation de l'IUT, tout en prenant en compte les risques de chacune de ces étapes. Une liste détaillée de chaque étape permettra de bien comprendre le processus de rénovation. Il y aura enfin la durée estimée de chacun de ces travaux. Notre tableau se constituera donc en 4 colonnes, comme suit.



| Besoins exprimés | Date | Tâches prévues | Risques |

| ------ | ------ | ------ | ------ |

| étapes | dates | liste de tâches | contraintes |



---



**Les objectifs** quant à eux permettront de comprendre le pourquoi cette rénovation a été entamée, quels seront les avantages d'un tel investissement. Il y aurait des avantages sur l'isolation thermique, en utilisant des matériaux plus écologiques et RGE (Reconnu Garant de l'Environnement), ainsi que des agrandissements d'espaces nécessaires au bien-vivre du campus, tels que les ascenseurs, les espaces verts, et l'espace sportif.



---



Enfin, **les moyens employés** permettront pour chaque étape de la rénovation de déterminer un coût ainsi qu'une liste détaillant les installations prévues.



***



## Création du site



Notre site sera donc constituée en _4 pages distinctes_, qui auront une barre de navigation en haut afin de naviguer librement entre les pages de notre site. Ce `<header>` pourra également contenir le logo de l'IUT, qui pourra être un lien vers la page d'accueil, ainsi que le titre de la page courante. Les couleurs de cet en-tête sont bleues pour la couleur de fond, ainsi qu'orange pour la couleur des boutons, pour que ceux-ci ressortent bien. Excepté le planning qui sera un tableau, chacune de nos pages sera constituée en différentes `<section>`, qui seront bien distinguées dans un cadre au fond blanc, avec une bordure arrondie pour faire moderne, et un padding pour bien espacer les éléments. La police de texte est en `Arial` car c'est une police qui est courante et professionnelle, et le texte sera en couleur noire afin d'être bien lisible. Nous avons élaboré toute une série de tests pour assurer la bonne maintenabilité de notre site.



## Publication du site



Une fois le site terminé, nous avons publié les pages sur **githack**, afin que celui-ci soit visible en ligne par tous.



# Les Outils



Nous avons utilisé Webstorm afin de concevoir l'HTML et le CSS de nos pages. Celles-ci seraient donc constituées d'un en-tête avec le logo, le titre, et une barre de navigation. Le contenu principal sera divisée en section, et chacune des pages aura son style CSS propre, déterminée dans une balise style. Une fois la structure et le style du site en place, nous avons fait une série de tests afin de s'assurer du bon fonctionnement de tout ça.



## La liste de test



1. Nous avons été sur la console de notre navigateur afin de redimensionner horizontalement notre page, pour s'assurer de la responsivité de chacune de nos pages, pour que celles-ci soient visibles sur portable.

2. Nous nous sommes assurés du bon fonctionnement de chacun des liens dans la barre de navigation, ainsi que des liens de contact / localisation de la page d'accueil, ainsi que de la présence de toutes les images.

3. Nous avons utilisé un outil officiel, validator.w3.org afin de valider la bonne sémantique de notre code HTML, pour rendre celui-ci optimal. Nous avons aussi vérifié l'accessibilité de notre site Web à l'ide d'un autre outil officiel, https://wave.webaim.org/ pour être certain que le site Web est accessible à tous.

4. Nous avons vérifié dans notre code CSS si toutes les règles étaient bien appliquées, et si certaines d'entre elles n'étaient pas inutilisées.



# Conclusion



La réalisation de ce site web nous a permis de bien diviser les différentes étapes du travail, nous permettant une meilleure organisation, ainsi que de bien répartir les informations que nous souhaitions communiquer au travers de notre site web. Celui-ci nous a également appris à utiliser le HTML afin d'assurer la bonne sémantique de notre site, et le CSS pour en assurer le style.
 
