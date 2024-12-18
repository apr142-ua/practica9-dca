# practica9-dca
GIT obligatorio para la práctica 9 de DCA

# BISECT
    1. Inicio del bisectado:
    Se marcó un commit como defectuoso (git bisect bad) y uno funcional como referencia (git bisect good <hash>).

    2. Pruebas iterativas:
    Git seleccionó commits intermedios para probar si eran buenos o malos (git bisect bad/git bisect good).

    3. Identificación del fallo:
    El proceso identificó el commit defectuoso: Introducido un fallo intencionado.

    4. Revertir el fallo:
    Se revirtió el commit problemático con git revert <hash> y se generó un nuevo commit de corrección.

    5. Finalización:
    Se ejecutó git bisect reset para volver al estado original.

# HOOK:
He configurado HOOK para que cada vez que se haga un commit ejecute un "test". Si archivo.txt no contiene TODO lanza un error.
![image](https://github.com/user-attachments/assets/76850b8c-8db3-4798-8f5d-5e009ee18a00)
