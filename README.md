# Examen final : Intégration PHP/MySQL et gestion de contenu
## Travail strictement individuel 
>[note 0 à toutes les personnes impliquées dans un plagiat]
---
### Utilisez comme point de départ les fichiers de code distribués dans ce dépôt.
---

## Étapes à suivre
1. *Clonez* le dépôt sur votre machine locale dans un emplacement **approprié**

2. Créez un `alias` dans la configuration de votre serveur Web, ou déposez simplement le dossier de code de l'atelier à la `racine` des documents de votre serveur Web (`Document Root`)

3. En partant du script `SQL` distribué, créez la base de données sur votre serveur. Ajustez au besoin la configuration dans le document `config-temp/21b-h23-memo.cfg.php` (ne déplacez pas ce fichier)

4. Testez le site Web avant de commencer la production de votre solution

5. Complétez le code d'affichage (`vue` : fichier `index.php`) ainsi que le code `controleur` (fichier `memo-controleur.lib.php`) et `modele` (fichier `memo-modele.lib.php`) de l'unique *module* à considérer (*memo*) ; la liste des fonctionnalités demandées suit

6. Produisez les fonctionnalités requises par l'interactivité de votre application (notez que ce prototype n'est pas réaliste puisqu'on ne tient pas compte de l'utilisateur connecté dans cette évaluation) : 
    1. Ajout d'une tâche (par défaut une nouvelle tâche est *non-complétée*)
    2. Affichage de toutes les tâches (suivez le gabarit HTML fourni : aucune modification HTML/CSS n'est requise)
    3. Modification de l'état d'une tâche : la même action fait basculer la tâche de *complétée* à *non-complétée* et vice-versa
    4. Suppression d'une tâche 
    5. Suppression de toutes les tâches complétées
    6. Affichage du nombre de tâches *actives* (c'est à dire *non-complétées*)
    7. [OPTIONNEL - POINTS BONIS] Filtrer l'affichage des tâches

7. Synchronisez votre solution complétée avec le dépôt GitHub qui vous a été assigné lorsque vous avez accepté le travail (c'est le dépôt distant (*remote*) déjà défini dans votre projet)

>Désolé, aucune remise tardive ne pourra être acceptée ! Lorsque je quitte le local, les remises sont finales. Vérifiez donc deux fois plutôt qu'une que vous avez bien synchronisé (`push`) vos fichiers de solutions dans le dépôt GitHub assigné.

### Gardez une copie personnelle de votre travail : le dépôt de remise sur `582-21B` pourra être supprimé une fois la correction complétée et les notes publiées.