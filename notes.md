# Notes
## Se connecter au serveur 
```
ssh eservant@bio4g-login-seqoia.bioinfo.aphp.fr
ssh bio4g-rseq-01
```
## Manipuler les fichiers
C'est un tout petit serveur, avec très peu de RAM (512 Mo). Il faut donc définir ces variables lorsqu'on fait des calculs en dehors du cluster sur le serveur: 

```
export TMPDIR=/scratch/recherche/$USER/tmp
export TEMP=/scratch/recherche/$USER/tmp
export TMP_DIR=/scratch/recherche/$USER/tmp
export TMP=/scratch/recherche/$USER/tmp
```

## Jupyter 
<https://gitlab-bioinfo.aphp.fr/Sequoia/Recherche/-/wikis/jupyter>
- le même serveur avec peu de RAM ? 
- Comment lancer de grosses requetes sur jupyter alors ? 

## Le data lake 
