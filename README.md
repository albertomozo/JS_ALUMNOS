# JS_ALUMNOS - IKASLEAK

Sitio web que lee la información de los cursos que he impartido por años usando JSON para almacenar la información. 

## tecnologias
JS
HTML
CSS

## index.html

Muestra los cursos que estan alamcenados en cursos_YYYY.json. 

Por ejemplo el fichero cursos_2023.json  contiene la siguiente información.

```json 
{ "titulo" : "Cursos de Formación",
"año":2023,
"cursos" : ["IFCD65-FRONT_202302.json","IFCD54-BACK_202306.json","mf0493_202310.json", "IFCD0110_202312.json" 
]} 
``` 

La pagina muestra la lista de cursos con un enlace que nos redirige  a la página alumnos.html en la que le enviamos el nombre del json que contien la información de un curso en concreto


```json
{"curso":"IFCD0210_2024_03",
"fecha inicio" : "2024-03-16",
"fecha fin" : "2024-07-24",
"tutor":
    {"Nombre":"Alberto Mozo",
        "email" : "albertomozodocente@gmail.com",
        "linked" : "https://www.linkedin.com/in/alberto-mozo-avellaned-80615713/",
        "github" : "albertomozo"
       
    
    },
"alumnos" : [
        {
            "Nombre":"Alumno1",
            "email" : "Alumno1@gmail.com",
            "linked" : "https://www.linkedin.com/",
            "github" : "https://github.com",
            "inicio" : {    
                "html" : 1,
                "css" : 1,
                "JS" : 1,
                "Vue" : 3
            },
            "fin" : {     
                "html" : 4,
                "css" : 4,
                "JS" : 4,
                "Vue" : 4 
            }
        
        },
             {
            "Nombre":"Alumno2",
            "email" : "Alumno1@gmail.com",
            "linked" : "https://www.linkedin.com/",
            "github" : "https://github.com",
            "inicio" : {    
                "html" : 1,
                "css" : 1,
                "JS" : 1,
                "Vue" : 3
            },
            "fin" : {     
                "html" : 4,
                "css" : 4,
                "JS" : 4,
                "Vue" : 4 
            }
        
        }
    ]
}
 ```

 Tenmos 3 tipos de datos 

 ### curso 
 Obligatorio 
 - curso
 - fecha-inicio

### personas
Pueden ser tutores y alumnos, ambos tienen en comun los datos de persona

#### datos persona
nombre
email
linkedin
github
url
#### datos evolucion
Dependiendo de la formación impartida, colocamos las materias en  2 grupos inicio y fin para valorar los conocimientos iniciales y los finales.

Normalmente al comenzar cada curso, genero un cuestionario de inicio en el que solicto los datos a los alumnos al inicio de la formación.

AL terminar relleno los datos finales. 


 ## web 🌐   https://ikasleak.netlify.app



 