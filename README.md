qdroid  
======  
  
QCM Technique Android  
=====================  
  
1ère Partie - Connaissances Java  
--------------------------------  
  
### Level 1/5 ###
  
1) Parmi les propositions si dessous quels sont les « modifiers » de visibilité d’une classe Java:    
[ ]Protected    
[ ]Package avec le mot clé package    
[ ] Package sans mot clé package    
[ ] static    
  
2) Lequel de ces mots n’est pas un mot clé réservé en java    
[ ] synchronize    
[ ] volatile    
[ ] try    
[ ] finally    
  
### Level 2/5 ###
3) Soit la méthode public void operation(int a, int b), la(les)quelle(s) méthodes ne sont pas des méthodes polymorphiques de celle proposée.    
[ ] public int operation(int a)    
[ ] public String operation(int a)    
[ ] private operation(int a, int b)    
[ ] public String operation(String s)    
  
4)  Le mot clé final sert à :    
[ ] Empêcher une classe d’être dérivé.    
[ ] Empêcher une classe d’être collecté par Garbage Collector.    
[ ] Empêcher une méthode d’être surchargé.    
[ ] Empêcher une variable d’être collectée par Garbarge Collector.    
  
  
### Level 3/5 ###
5) Quel est le principal avantage des namespaces (package) hormis le fait de regrouper des fonctionnalités en module    
[ ] Avoir des classes de même nom dans un programme entier.    
[ ] Pouvoir implémenter le pattern Abstract Factory facilement.    
[ ] Faciliter l’obfuscation du code des classes issues du même namespace.    
[ ] Cacher une méthode ou une propriété d'une classe en dehors de son package.    
  
6) Quand est ce qu’est appelée la méthode finalize() d’une classe Java?    
[ ] Juste après l’appel du constructeur de la classe.    
[ ] Juste avant la destruction d’un objet.    
[ ] Juste avant que le Garbage collector collecte la mémoire de la classe.    
[ ] Juste après que le Garbage collector collecte la mémoire de la classe.    
  
### Level 4/5 ###
7) Qu’est ce que l’intercession en Java :    
[ ] La capacité d'un programme à examiner son propre état    
[ ] La capacité d'un programme à modifier son propre état d'exécution ou d'altérer sa propre interprétation ou signification    
[ ] La capacité d’un programme à interagir avec un autre programme via l’exposition d’object de type COM    
[ ] La capacité à un programme de permettre l'appel, l'exécution et le renvoi du résultat d'une méthode exécutée dans une machine virtuelle différente de celle de l'objet l'appelant    
  
8) Le mot transient    
[ ] n’est pas un mot clé standard Java    
[ ] sert à déclarer une variable comme étant thread-safe    
[ ] sert à déclarer une variable comme ne pouvant pas être découverte par reflexivité    
[ ] sert à déclarer une variable comme  n’étant pas sérializable    
  
  
### Level 5/5 ###
9) Une weakHashedMap :    
[ ] est thread-safe    
[ ] implemente pas l’interface Map    
[ ] à ses entrees vidées si les clés associés ne sont plus utilisées    
[ ] est synchronisé    
  
10) Les interfaces optionnelles :    
[ ] n’existent pas.    
[ ] existe en java7 mais pas utilisable sur Android.    
[ ] existe en java8 mais pas utilisable sur Android.    
[ ] existera en java9 et sera porté dans Android Open Source Project via OpenJDK.    
  
  
2ème Partie - Connaissances Android  
-----------------------------------  
  
### Level 1/5 ###
  
11) Qu’est qu’une Activity ?    
[ ] Le model d’une vue    
[ ] Le controller d’une vue    
[ ] Une classe qui herite de Context    
[ ] Une classe qui herite de Application    
  
12) Où se déclare une Activity?    
[ ] Dans info.plist    
[ ] Dans proguard.txt    
[ ] Dans Build.gradle    
[ ] Dans AndroidManifest.xml    
  
13) la classe Application    
[ ] Peut être sous classé.    
[ ] Hérite d’Activity    
[ ] Est présente de partout dans une app android    
[ ] Est instanciée juste apès la main activity    
  
14) Comment s’appelle la méthode pour attacher une vue à une activity    
[ ] setContentView    
[ ] attachView    
[ ] attachContentView    
[ ] setAttachedView    
  
15) Quels sont le ou les bons cycles de vie d’une activity    
[ ] OnCreate – onResume – onRestore – onStop – onDestroy    
[ ] onCreate – onResume - onSaveInstanceState - onDestroy     
[ ] onCreate – onStart – onResume - onPause - onDestroy    
[ ] onCreate – onPause – onResume – onStop – onDestroy    
  
16) Qu’est que ViewSwitcher ?    
[ ] Une composant qui cache via une API spécifique son contenu et le reaffiche via le meme appel    
[ ] Un composant qui cache un sous composant et en affiche un autre et vice versa    
[ ] Une surclasse de ButtonSwitcher    
[ ] Une surclasse de ImageViewSwitcher    
  
### Level 2/5 ###
17) Qu'est-ce qu'un fragment ?    
[ ] Une popup sur une activity    
[ ] Un morceau d’interface utilisateur rattaché à une activity.    
[ ] Un morceau de base de donnée SQLite    
[ ] Une vue externalisé d’un layout vers un layout « standalone »    
  
18) Où se declare la sous classe de la classe Application :    
[ ] Dans l’attribut name de la balise application du fichier AndroidManifest.xml    
[ ] Dans l’attribut application de la main activity du fichier AndroidManifest.xml    
[ ] Dans l’attibut applicationClassName de la main activity du fichier AndroidManifest.xml    
[ ] Elle est déclarée automatiquement si une classe étends de Application dans le package principal    
  
19) A partir du ou desquels de ces objets on ne peut pas recuperer le context de l’application :  
[ ] Une activity  
[ ] Une view  
[ ] Un service  
[ ] Une intent  
  
20) Qu’est ce nine patch  
[ ] Une image redimensionnable  
[ ] Un système d’execution de requêtes SQL  
[ ] Un moyen d’inserer du text au bord d’une imageView  
[ ] Une protection contre l’injection dynamique de code java au runtime  
  
21) Dans quel dossier de l’architecture Android range-t-on les fichiers ressources html, js, css, les polices additionnelles, etc… :  
[ ] : ressources  
[ ] : res  
[ ] : assets  
[ ] : values  
  
22) Qu’est qu’un « adapter » ? (0,5pt)  
[ ] La composant service du controller dans le pattern ideal MVC  
[ ] Le composant model du controller dans le pattern ideal MVC  
[ ] Le composant entité d’une table SQLLite du model dans le pattern ideal MVC  
[ ] Le composant issu du model à adapter en fonction d’une cardview, listView ou listActivity    
  
### Level 3/5 ###
23) De quelle composant hérite directement une CardView :  
[ ] Framelayout  
[ ] RelativeLayout  
[ ] ViewGroup  
[ ] ImageView  
  
24) Quel est le ratio à appliquer à une ressource xxhdpi pour la passer au format hdpi.   
[ ] 2  
[ ] 0.75  
[ ] 0.5  
[ ] 1.5  
  
  
25) Quelle(s) est(sont) la ou les difference(s) entre une ListView et une RecyclerView  
[ ] RecyclerView impose d’utiliser une cardview en template d’une cellule  
[ ] RecyclerView impose d’implementer le pattern ViewHolder  
[ ] ListView ne propose pas de mecanisme de reutilisation de view  
[ ] RecyclerView ne permet pas nativement de faire des templates pour des headers et footers de liste.  
  
26) Parmis ces composants graphiques, lesquel n’est pas issu d'une support library  :  
[ ] NestedScrollView  
[ ] CoordinatorLayout  
[ ] RecyclerView  
[ ] ViewAnimator  
  
27) Quel fonctionnalité n’est pas présente dans Proguard  
[ ] Minificateur de code  
[ ] Obfuscateur de code  
[ ] Optimisateur de code  
[ ] Debugging avancé de code  
  
28)  Quels sont les formats de bibliothèques supportés par Android :  
[ ] .so  
[ ] .a  
[ ] .jar  
[ ] .aar  
  
###Level 4/5 ###
29) Quel(s) composant(s) graphiques peuvent affichés en dehors de l’application (lorsqu’elle est en background)  
[ ] Toast  
[ ] AlertDialog  
[ ] ProgressDialog  
[ ] DialogFragment  
  
30) Un IntentService :  
[ ] Herite de service  
[ ] S’execute par default dans le main thread  
[ ] Herite de Context  
[ ] Peut se redemarrer lorsqu’il est tué.  
  
31) Un service   
[ ] S’execute par défault dans le main thread  
[ ] Peut se redémarrer lorsqu’il est tué.  
[ ] Peut être démarrer plusieurs fois  
[ ] ne s’arrête jamais tout seul  
  
32) Comment un service peut notifier l’ui qu’une tache a fini d’être traitée ?  
[ ] le service peut lancer un broadcast d’intent  
[ ] le service peut lancer un évènement via Bus ou EventBus  
[ ] le service peut démarrer une lancer une intent implicite  
[ ] le service peut notifier par listener au composant qui l’ecoute  
  
33) Quel language de script est utilisé par Gradle afin de décrire les tâches de build d'une application ?  
[ ] Gradlew  
[ ] Python  
[ ] Groovy  
[ ] Kotlin  
  
34) Parmis ces 4 outils, lequel ne fait pas partie du sdk Android  
[ ] ddms  
[ ] android  
[ ] monkeytester  
[ ] draw9patch  
  
  
###Level 5/5 ###
35) Qu’est ce qu’un Looper  
[ ] L’implementation du design pattern Iterator pour les thread en queue  
[ ] Une boucle de message dans un thread  
[ ] Un planificateur de taches recurrentes  
[ ] Le nom de la queue pour gerer l’ordonnancement des threads  
  
36) Si une app en background n’est pas remise au premier plan, va rentrer en sleep mode. Comment la reveiller ?  
[ ] En utilisant les API AlarmManager   
[ ] En utilisant les API LocationManager   
[ ] En utilisation les API Looper   
[ ] En utilisant les API Handler  
  
37) Qu'est-ce qu'InstantRun ?  
[ ] L’api Android6 qui permet de lancer une activity plus rapidement(cycle de vie de l’activity raccourci)  
[ ] Une fonctionnalité d’Android studio 2.0 qui permet d’eviter la recompilation d’une app si seul le code de la vue a été modifiée  
[ ] L’API Android 6.0 qui permet d’envoye des notifications instantanées a n’importe quel activity  
[ ] Une fonctionalité d’Android studio 2.0 qui permet de deployer une app sur le playstore directement depuis l’IDE.  
  
38) Qu’est ce qu’AltBeacon :  
[ ] Un nouveau set d’API dans Android6 pour le BluetoothLE.  
[ ] Une bibliothèque compatible iBeacon développé par les laboratoires de Google  
[ ] Une bibliothèque compatible iBeacon et Eddystone développé par Estimote  
[ ] Une bibliothèque compatible iBeacon et Eddystone développé par RadiusNetworks  
  
39) Citez l’intrus  
[ ] RetroFit  
[ ] Picasso  
[ ] EventBus  
[ ] okhttp  
  
40) Citez l'intrus  
[ ] Jake Wharton  
[ ] Chet Haase  
[ ] Chris Banes  
[ ] Romain Guy  
