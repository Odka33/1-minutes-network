# 2-formatage

## Supprimer le champ "ip.dest_host" et sa ligne sur chaque ligne du fichier

'''
cat ip_dest.txt | sed '/ip.dst_host/d'

'''

Effet positif de la command qui à supprimer les lignes vide du fichier.
