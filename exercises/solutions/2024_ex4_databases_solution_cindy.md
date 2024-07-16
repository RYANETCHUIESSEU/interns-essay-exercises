

Une Base de Données : est une structure organisé permettant le stockage et la gestion efficace des données.
On distingue les bases de données:

                                    -relationelle (SQL,Oracle,My SQL,PostGre SQL)
                                    -No SQL:(Mongo DB)
                                    -BD Multimodele:Mark Logic,Arrango DB
                                    -New SQL

        BD Relationelle: sont des systeme de gestion de données qui fonctionne de manière structurée , avec des jointures et a partir des modele préetablie .
        Avantages:-sécurisé
        Inconvénient:- temps de latence considerable

                BD No SQL: sont des systeme de gestion de données qui fonctionne sans jointures   et sans modele préetablie .
        Avantages:-gestion de grande quantité de données
                  -faible temps de latence

        Inconvénient:- le cout

        
                    BD New SQL: sont des systeme de gestion de données qui fonctionne  a partir de la fonction ACID(Atomicité,Coherence,Isolation,Durabilité)  des bd relationelle et a partir de la capacité de gestion longue echelle de bd non relationelle.

        Avantages:-gestion de grande quantité de données
                  -faible temps de latence

        Inconvénient:- le cout
                        -complexe a l'usage


                        BD Multimodele: Systeme de gestion de données pouvant gérer plusieurs modele au sein d'un meme  systeme.
        avantages: - jointures entre les modéles
                    -possibilités de gerer plusieurs modeles
        Inconvénients:- cout

        Partie2:

        1-SELECT *
        FROM EMPLOYEE
        WHERE salary > 10000;

        2-SELECT employee_id,first_Name,manager_name

        3- 

        4-SELECT job_id,job_title,department_name
        FROM EMPLOYES
        INNER JOIN DEPARTEMENTS ON  e.department_id=d. department_id;

        5- SELECT *
        FROM EMPLOYEE 
        WHERE hire_date >=

        8- SELECT *
        FROM EMPLOYEES
        WHERE manager_id IS NULL;
        
            