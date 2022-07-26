# README

vite_rails est une gem qui permet d'avoir un "rechargement à chaud" de la page après une modification d'un fichier.
Fini le temps de faire un refresh manuel (F5), vite_rails vous permet de le faire automatiquement.
Vite est capable de gérer les différents langages de programmation (Ruby, Javascript, Python, PHP, etc.)

Ici, vous pouvez voir un exemple de fonctionnement de vite_rails.
Commentez et enregistrez l'intégralité du fichier app/frontend/entrypoints/application.css pour voir le résultat.
Le style disparaitra après la modification du fichier.
Voilà la force de vite_rails.

L'utilisation d'un plugin de vite_rails est simple.
Ici, le plugin est: [vite-plugin-full-reload]
Essayez de modifier le fichier app/views/home/index.html et vous verrez le résultat.

Prérequis:

$> ruby -v
ruby 3.1.0p0
$> bundle -v
Bundler version 2.3.18
$> foreman -v
0.87.2
$> npm -v
8.11.0
