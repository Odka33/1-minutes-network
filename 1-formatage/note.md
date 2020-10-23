# 1-formatage

## Afficher les adresses IP destination.

'''
cat 1minute.json | awk '{print $1$2}' | grep "ip.dst"

'''

## Cependant le champ "ip.dst_host" reste présent dans le fichier.
