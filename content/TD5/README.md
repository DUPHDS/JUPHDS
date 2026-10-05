# TD5 : Programmation orientée objet

**Exercice 1 :**

Nous voulons créer une ferme virtuelle avec des animaux et des fonctions qui vous permettent de découvrir la ferme.

    1. Créez une classe Ferme qui doit être initialisée avec le nom de la ferme et qui crée automatiquement une liste vide pour stocker les animaux.
    2. Créez une variable qui s'initialise à 0 lors de la création et compte le nombre d'animaux.
    3. Créez une classe Animal qui s'initialise avec le nom et l'âge de l'animal.
    4. Ajoutez une méthode str pour afficher le nom et l'âge de l'animal.
    5. Ajoutez la méthode add animal à la classe Ferme.
    6. Ajoutez la méthode str à la classe Ferme, affichant le nom de la ferme, le nombre d'animaux et chaque animal.
    7. Ajoutez deux classes, Mouton et Canard, qui héritent de Animal et ont une fonction cry, qui renvoie le cri de l'animal, et une fonction str, qui renvoie la même chose que la classe animal, mais avec le cri du mouton et du canard.

**Exercice 2 :**

Nous étudions les données relatives aux patients admis en 2021 dans deux hôpitaux de Bordeaux. Le fichier « patients.csv » contient les données relatives aux patients et le fichier « visites.csv » contient les données relatives aux visites des patients (dans ce fichier, ID est l'identifiant du patient concerné par la visite ; dans la question 4, vous verrez que l'identifiant de la visite sera généré automatiquement).

    1. Créez une classe Hospital prenant comme paramètres l'emplacement de l'hôpital, un répertoire de ses patients et un répertoire des visites de ses patients. Ajoutez les fonctions : 
        a. add_patient ajoute le patient au répertoire.
        b. remove_patient supprime le patient du répertoire.
        c. add_visit ajoute une visite à l'hôpital.
        d. get_patient_id qui renvoie le patient correspondant à l'identifiant donné.
        e. get_visites_patient qui renvoie les visites d'un patient par identifiant.
        f. get_visite_by_date qui renvoie les visites qui ont eu lieu un certain jour.
        g. str of hospital doit afficher l'emplacement de l'hôpital et le nombre de patients.
        h. len doit afficher le nombre de patients dans l'hôpital. 
    2. Créez une classe Patient prenant comme paramètres l'identifiant du patient, sa date de naissance, une liste de visites et son sexe. Ajoutez les fonctions :
    3. add_visit, qui ajoute une visite au patient.
    4. str of Patient, qui affiche l'identifiant du patient, sa date de naissance et son sexe.
    5. Ouvrez le fichier « patients.csv » en mode lecture et, pour chaque ligne, créez un patient et ajoutez-le à un répertoire de patients.
    6. Créez une classe Visites qui prend en entrée un patient, un hôpital, le motif de la visite, la date et qui possède un identifiant. L'identifiant de la visite doit augmenter à chaque fois qu'un objet Visit est créé.
    7. Créez une classe VisiteUrgente, qui est une sous-classe de Visites. Ces visites comportent 4 données supplémentaires permettant d'évaluer l'état du patient : s'il saigne, sa fréquence cardiaque, sa tension artérielle et s'il est conscient à son arrivée aux urgences. (0 pour Non et 1 pour Oui)
    8. À partir du fichier « visits.csv », créez des hôpitaux et des visites associés aux patients. Les hôpitaux doivent contenir uniquement les patients et les visites qui ont eu lieu dans cet hôpital.
    9. Affichez le nombre de patients pour chaque sexe.
    10. Affichez le nombre de visites pour chaque motif pour chaque hôpital.
