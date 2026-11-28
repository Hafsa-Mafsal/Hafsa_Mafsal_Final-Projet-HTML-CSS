# Hafsa_Mafsal_Final-Projet-HTML-CSS
✨Description de projet
TOGETHER est une community en ligne cree pour offrir aux femmes et aux jeunes filles un espace securise où elles peuvent s'exprimer librement, partager leurs experiences, se soutenir mutuellement et sensibiliser à la violence basee sur le genre.

💻Technologie utilise

- HTML5 
- CSS + TAILWIND 
- Daisyui
- GIT & GITHUB

🌐l'installation
Pour l'installation et utilisaion de mon projet vous devez:

Clone d'abord le projet dans vote PC 

- git clone https://github.com/Hafsa-Mafsal/Hafsa_Mafsal_Final-Projet-HTML-CSS.git


Puis installer les technologies que j'ai utilise:
J'ai utilise un component header de DAISYUI 

- link: https://daisyui.com/

pour utilise ce compnent vous devez soit install CLI 
mais je propose just d'utilise CDN en a 2 link 
- 1er link dans etre ecrire dans head : <link href="https://cdn.jsdelivr.net/npm/daisyui@5" rel="stylesheet" type="text/css" />

- 2eme link avant la fermeture de body directement : <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

et pour le style j'ai style mon site avec 2 defferent methode 
css dans une section de post de page community 
- link de page html ./public/pages/community.html
- link de page css ./public/css/input.css


et la 2eme methode ou j'ai style les autres pages et sections et TAILWIND 
pour utilise ce compnent vous devez soit utilise CDN
mais je propose d'install CLI 
pou l'installation suivie les etapes suivant:

1er:
Install tailwindcss and @tailwindcss/cli via npm.

ouvre le Terminal est ecris la commende
- npm install tailwindcss @tailwindcss/cli


2eme:
pour mon projet tailwind deja import dans input.css


3eme:
Run the CLI tool to scan your source files for classes and build your CSS.

ouvre le Terminal est ecris la commende

- npx @tailwindcss/cli -i ./public/css/input.css -o ./public/css/output.css --watch


4eme:
output.css est deja linke dans tout les pages html avec le lien 
<link href="./output.css" rel="stylesheet">
