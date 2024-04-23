| code | designation | type | taille | remarque |
|:-----------------------|:-------------------------------------|:-------------------:|:-----------------:|:-----------------------------------|
|**id_riddle**                |identifiant d'une enigme                 |        N        |   \     |                               |
|order_riddle              |ordre dans une section                   |        N        |   \     |                               |
|name_riddle               |nom de l'enigme                          |       AN        |  100    |                               |
|difficulty_riddle         |difficulte de l'enigme                   |        N        |   1     | difficulte de 1 a 10          |
|solution1_riddle          |solution 1 de l'enigme                   |       AN        |   30    |                               |
|solution2_riddle          |solution 2 de l'enigme                   |       AN        |   30    |                               |
|solution3_riddle          |solution 3 de l'enigme                   |       AN        |   30    |                               |
|solved_X_times_riddle            |nombre de fois qu'une enigme est vali    |        N        |   \     |                               |
|creation_date_riddle      |date d'ajout de l'enigme                 | DATE JJ-MM-AAAA |   10    |                               |
|submit_by_riddle          |id_user de la personne qui la soumis     |        N        |   \     |                               |
|wording_riddle            |enonce de l'enigme                       |       AN        |  2000   |                               |
||||||
|**id_section**                |identifiant du volet                     |        N        |   \     |                               |
|name_section              |nom du volet                             |       AN        |   15    |                               |
|number_times_finished_section  |nombre de fois que le volet a ete fin    |        A        |   \     |                               |
||||||
|**id_type**                   |identifiant du type d'enigme             |        N        |   \     |                               |
|designation_type          |nom du type d'enigme                     |        A        |   20    |                               |
||||||
|**id_user**                   |identifiant utilisateur                  |        N        |   \     |                               |
|alias_user                |pseudo utilisateur                       |       AN        |   25    |                               |
|email_user                |email utilisateur                        |       AN        |   40    |                               |
|number_riddle_solved_user        |nombre d'enigme resolu                   |        N        |   \     |                               |
|creation_date_user        |date de creation du profil               | DATE JJ-MM-AAAA |   10    |                               |
|last_time_connected_user    |date de la derniere connexion            | DATE JJ-MM-AAAA |   10    |                               |
|number_riddle_submit_user |nombre d'enigme propose                  |        N        |   \     |                               |
|s1_lock_until_user        |date de deverouillage de la section      | DATE JJ-MM-AAAA | 10 |  |
|s2_lock_until_user        |date de deverouillage de la section      | DATE JJ-MM-AAAA | 10 |  |
|s3_lock_until_user        |date de deverouillage de la section      | DATE JJ-MM-AAAA | 10 |  |
|s4_lock_until_user        |date de deverouillage de la section      | DATE JJ-MM-AAAA | 10 |  |
