# Genetic Algorithm

### Paramètre du script

<p> Dans le fichier « src.Metier.Parametre_simulation.py », vous pourrez trouver toutes les constantes qui paramètre la simulation :
<ul>
<li>-h, --help : affiche l'aide du script</li>
<li>-a, --affine <n>: run a learning session with n sessions and print the model</li>
<li>-p, --polynome <n> : run a learning session with n sessions and print the model</li>
<li>-c, --checking <affine> or <polynome> : print a graph with model and reality</li>
</ul>
</p>

### Run du script

<p>Pour lancer la simulation, il faut ouvrir une console depuis le dossier genetic_algorithm puis lancer la commande :</p>

<pre><code>pip install matplotlib</code></pre>

<p> Une fois la librairie installée, on peut lancer le script :<p>

<pre><code>Python main.py --parameter </code></pre>

### Affichage console et graphe

Pendant l’exécution du script, l'affichage de la progression se fait par la console. A la fin de l'execution du script,
on affiche l'équation calculer par le reseau neuronal.