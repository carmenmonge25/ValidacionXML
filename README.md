# ValidacionXML
Autora: Carmen Monge Montes
Expresiones regulares utilizadas:
Email: [a-zA-Z0-9.+_\-*/=&^]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,} (Valida el correo con mayúsculas, minúsculas, números y una serie de caracteres para el usuario. Obliga a poner un @ y después letras en mayúsculas, minúsculas, números, puntos, guiones para el nombre del domio, que se debe poner mínimo uno. Y por último letras mayúsculas o minúsculas de una longitud mínima de dos para el dominio).
Teléfono: [6789][0-9]{8} (Al garantizar que los 9 dígitos empiecen por 6, 7, 8 o 9 estamos validando un número de teléfono español).
Código Postal: (0[1-9]|[1-4][0-9]|5[0-2])[0-9]{3} (Limita los códigos a las 52 provincias españolas, puediendo ser los dos primeros entre 01-52, por ello la distinción que se hace al principio, separando 01-09 o 10-49 o 50-52).
Nombre de Usuario: [a-z][a-zA-Z0-9_.]{5,30} (Obliga a iniciar en minúscula, permitiendo letras, números, guiones bajos y puntos, con una longitud mínima de 5 caracteres y máximo 30).
Contraseña: [a-zA-Z0-9!@#\$%\^&\*\(\)\-_\+=\.]{8,} (Se valida una contraseña de longitud mínima de 8 caracteres, permitiendo mayúsculas, minúsculas, números y una lista de caracteres)
