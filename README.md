# Migration de Cassandra 3.x vers 4.x

## Nous allons voir comment monter de version un cluster Apache Cassandra de la version 3.x vers la version 4.x :

Pour simplifier ici, on effectuera une migration d'un cluster *à nœud unique*. Les clusters de production Cassandra ont toujours plusieurs nœuds. Par conséquent, les étapes comportent des notes décrivant le travail *supplémentaire* nécessaire à la mise à niveau des clusters *multi-nœuds*.

**Dans ce TP, nous allons :**
- Démarrer un cluster Cassandra 3.x à nœud unique
- Créer un schéma et y insérer des données
- Préparer le nœud pour la migration
- Installer Cassandra 4.x
- Démarrer Cassandra 4.x
- Vérifier que le nœud a été migré avec succès

_ Pour aller plus loin : [https://www.datastax.com/learn/whats-new-for-cassandra-4](https://www.datastax.com/learn/whats-new-for-cassandra-4) _

## Pour lancer notre TP :

[![Open in Gitpod](https://github.com/DataStax-Academy/katapod-shared-assets/blob/main/images/open-in-katapod.png)](https://gitpod.io/#https://github.com/DataStax-Academy/cassandra4-migrating-from-cassandra3/)
