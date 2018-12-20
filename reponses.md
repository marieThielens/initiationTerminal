1. Qu'est-ce qu'un terminal ? 

Le terminal est un outil intimidant aux premiers abords, mais au final se révèle pas compliqué. C’est une version texte de l’explorateur de fichiers : on peut ouvrir des dossiers, créer des fichiers, les lancer, les renommer, installer des programmes, et bien d’autres choses. On dit que c’est une CLI (Command Line Interface), comparée à la GUI (Graphical User Interface) de l’explorateur normal. Tout est fait via clavier, donc pas besoin de souris dans le terminal.

2. Comment lancer le terminal ? 

Sur Linux : `CTRL + ALT + T`
Sur macOS : `CMD + SPACE`, puis écrire Terminal (ou iTerm), Enter.

3. Quelle est la commande qui permet ? 
  - de naviguer entre les dossier ; `cd`
  - de savoir exactement où tu te trouves, dans quel dossier ? ; `pwd`
  - d'afficher le contenu d'un répertoire/ d'un dossier : `ls`
  - de créer un repertoire/dossier ; `mkdir nomdudossier`
  - de créer un fichier ; `touch nomdufichier`
  - d'ouvrir un éditeur de texte dans votre terminal ; `nano nomDuFichier`
  - de renommer ce fichier ; `cp fichier_à_copier lieu_de_destination`
  - de copier ce fihier dans un autre dossier ; `cp -i source destination`-i vous avertit si vous tentez d'écraser des fichiers existants 
  - de supprimer ce fichier ; `rm nomdufichier`
  - de supprimer un repertoire/dossier et son contenu ; `rmdir -r nomdufichier` (-r pour supprimer aussi son contenu)
  - de déplacer un fichier ou un repertoire/dossier d'un endroit à un autre ; `mv [fichier_à_déplacer] [lieu_de_destination] 
  
  4. Qu'est-ce que Vim ? 
  
Vim est un des éditeurs de texte les plus respectés au monde. Comme il passe uniquement par le terminal, il se marie extrêmement bien avec cet outil. Et comme vim utilise exclusivement le clavier, ses raccourcis permettent d’aller extrêmement vite. ICi nous voyons Vim pour la culture générale.

- Commande pour ouvrir vim sur un fichier ; `vim nomdufichier`
- commande pour quitter vim : `:q!`

## Sources

https://blog.thehackingproject.org/2018/08/08/decouvrir-le-terminal/
  
