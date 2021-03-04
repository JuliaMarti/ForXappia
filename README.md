# For Xappia

Ejercicio resuelto exitosamente para acceder a un trabajo de Salesforce en Xappia, sin conocimiento previo del lenguaje y con tiempo límite de 3 días.

Tutoriales:
Los tres tutoriales son para que los utilices de guía para poder resolver el ejercicio, no es necesario que realices los retos al finalizar cada uno.   
 https: // comienzo del sendero. salesforce.com/ content / learn /  modules / apex_database? trail_  id = force_com_dev_beginner  
https: // comienzo del sendero. salesforce.com/ contenido / aprender /  módulos / apex_integration_  servicios / apex_integration_  rest_ llamadas     
https: // comienzo del sendero. salesforce.com/ content / learn /  modules / lex_dev_lc_basics

## Ahora sí el ejercicio:
Deberás hacerlo en un Entorno Dev.

Se necesita hacer un Componente Lightning de tipo formulario para crear contactos. Este formulario debe tener un buscador que al introducir un número y hacer click en un botón Buscar, hace una llamada a SWAPI (La API de personajes de Star Wars). 

Si el número de personaje coincide con alguno existente, los campos se deben auto completar con los que se reciben por la API. Cuando todos los campos están completos debe haber un botón Guardar que permita crear un Contacto con los datos de este formulario.  

## Requisitos:
- El ejercicio debe resolverse con un Lightning Component (Aura Framework)
- La llamada al servicio debe hacerse en el controller APEX.
- Los campos que debe tener el formulario son: Nombre, Altura, Género, Color de cabello, Color de ojos, URL, Planeta y Número de Personaje. Si alguno de estos campos no existe en el contacto standard de Salesforce, deben crearse.
- Los campos que traen información no pueden ser modificados por el usuario pero si algún campo se recibe vacío (Know o N/A), se debe poder completar por el usuario. 
- Para poder guardar el personaje, tuvo que haber sido traído desde SWAPI. 
- Se espera: un feedback al guardar el personaje / una validación al intentar guardarlo más de una vez / feedback de personaje no existente. 

## Recomendaciones:
- El acceso al formulario debe ser sencillo.  
- El aspecto visual es importante. El componente debe ser uniforme con el estilo de Salesforce y debe tener una experiencia de usuario agradable.
- Entender bien cómo funciona la comunicación entre el Controller Apex y el Lightning Component.
- No confundir Lightning Component con Lightning Web Component. Ver Aura Framework.

## Datos técnicos:
-Se debe consumir el endpoint  https://swapi.dev 
