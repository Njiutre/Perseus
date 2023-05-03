# Perseus
Projet Perseus

## Lancé le projet 

Pour lancer le projet, vous devez taper dans un terminal les commandes suivantes depuis le dossier src: 
      - make 
      - gcc -O0 -g -W -Wall -Wextra -mtune=native  -march=native  -std=c99  EnvoieDataFileMessage.c FileDeMessage.c FilsSauvegarde.c FilsTransmission.c   
        FilsCentrale.c ReceptionDataFileMessage.c Structure.c VariableGlobale.c OBC.c ./sbgECom/out/libsbg.a  -o OBC 

