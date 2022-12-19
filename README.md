# repositoriodepruebas
 hacemos un cambio en un archivo(agregar,borrar contenido)(borrar un archivo)etc
 
 -->archivo ---> con cambios (tracked)// no se puede agregar a un commit en esta instancia
 
 una vez que ya terminamos lo tenemos que cambiar de estado al stage es decir pasarlo a un estado que me 
 permite agregarlo a un commit
 con un git add//  -- > git add {va a agregar todos los cambios que haga en el stage
                        o git add <ruta del archivo>}
  El git ADD va a agregar los archivos en el stage
  ///cambia el estado del archivo///
  
  Ahora el archivo esta en stage y se puede subir un commit
  
  
 Lo agregamos a un commit con el comando ---> git commit -m <aca un mensaje>
  Todo lo que este en satge al momento de ejecutarlo va a estar dentro del commit 
  
  Ahora una vez este el commit nos falta enviarlo al repositorio remoto
  git push origin <nombre> -- > se actualizaen remoto
  
  
  Comandos
  git branch - listado de branch
  git branch -a <nombre de la rama> // borrado (previene borrar si hay cambios)
  gir branch -D <nombre> // borrado forzado
  git branch -a // listado branch remoto
  git branch -m <nuevonombre> // cambiar el nombre de la rama actual
 
  git clone // clona un repositorio remoto en mi maquina local
  
  git push // subir cambios de mi maquina al repositorio remoto
  git pull -git fetch // actualiza nuestri repositorio o maquina local
  git push origin <nombre > // publicar 
  git push origin --delete <rama >// borra la rama remota
  
  git checkout --> cambiar de rama
  git chechkout -b <nombre> // crear la rama y moverse a ella
