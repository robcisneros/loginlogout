Aplicación que esconde páginas si no estas logeado.
Uso de useEffect para obtener los valores de las key en localStorage. Este hook se ejecuta
al renderizar incialmente el componente donde vive y también cuando una de sus variables
es modificada o con el uso de un temporizador.

Hacemos uso del useContext ya que hay información que es de importancia 
para muchos componentes, siendo específicos, con el uso del user name y 
desplegar ya sea login o logout dependiendo del valor de useState.
Recordar que hay que envolver a index.js con el provider.

También hacemos uso de useReducer el cual es muy similar a manejar estados, con este
hook se pueden manipular un estado más complejo y para esto existen las acciones
que se mandan a llamar con dispatch.