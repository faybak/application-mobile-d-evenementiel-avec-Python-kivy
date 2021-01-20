# event-app-with-Python-kivy
Exemple d'application mobile pour la publication d'evenement en tout genre.

Je me suis inspiré des explications et publications d'Erik Sandberg, qui pour moi est l'un des meilleurs en terme d'explication sur l'utilisation de kivy.
Pour ceux qui ne connaissent pas encore kivy, je publierais prochainement un code plus explicite avec peut être une video en complément d'information, afin de mieux assimiler son fonctionnement.

Cette application est adaptée que ce soit pour la plateforme IOS ou la plateforme Android. Pour faire la conversion il faut tout simplement utiliser le module "kivy-ios" dans le cas de IOS et "python-for-android" dans le cas des androids.

Context:

Cette application dont j'ai nommé "P2B" qui correspond a "Place to be" permet de publier des événements en tout genre tels que mariage, showcase, concert, soirée pyjama, barbecue, journée culturelle,... . Cela dans l'objectif de pouvoir gerer plus facilement ses evenements grâce à l'intégration de professionnels de l'événementiel(traiteur,chanteur, organisateur,sécurité,..), la gestion des participants/invités mais aussi de pouvoir être au courant des événements qui sont dans vos alentours.

Principe:

Le principe est très simple. Une personne souhaitant créer un événement pourra creer et publier en moins de 5min son evenement avec toutes les informations nécessaires telles que la date, le lieu, le type,le genre et les conditions de l'événement. Toute personne intéréssée devra suivant le genre de l'événement demander à participer ou direct participer à l'événement.

Informations complémentaires:

Pour gérer la base de donnée et le système d'authentification, j'ai utilisé firebase qui est pas mal pour les tests. Vous avez la possibilité d'utiliser une base de données SQL et d'accéder directement à la base de données via mysql mais ce n'est pas recommandé dans le cadre d'une application. Il est judicieux de passer par une API dans lequel il faudra simplement faire du requetage.

Conclusion:

Comme vous pourrez le constater il s'agit ici d'un exemplaire incomplet mais qui vous aidera fortement si vous cherchez à créer une application juste avec python et kivy. Il s'agit de la première version de P2B, qui actuellement a subi plusieurs mise à jour. 

Hésitez pas à m'en parler si vous voulez que je publie la dernière version.
