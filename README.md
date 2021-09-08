# Git Commands

- Git checkout:

    Para cambiarse a un NUEVO branch (crea el branch al que se cambia):

              git checkout -b nombre_del_nuevo_branch
    Para cambiarse a un branch existente:
              
              git checkout nombre_del_branch_a_cambiarse
    

- Git Branch :
     Para crear un nuevo branch local:
     
              git branch nombre_del_brach
     Para listar los branch locales:
              
              git branch
     Para listar los branch remotos:
              
              git branch -r
     Para listar todos los branch :
              
              git branch -a
     Para eliminar un branch local :
            
              git branch -d nombre_del_branch_a_eliminar
     Para eliminar un brach del repositorio remoto:
            
             git push origin --delete nombre_del_branch_a_eliminar
            
     
               
                     
- Git Switch:
     Para swichear a un branch:
            
            git switch nombre_del_branch
     Para swichear a un NUEVO branch:
            
            git switch -c nombre_del_nuevo_branch
            
            
