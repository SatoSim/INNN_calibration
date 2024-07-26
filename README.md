​​Ciudad de México, México
24/07/24
Satoshi Simental Murakami
Reporte biblioteca para análisis de película radiocrómica 

El siguiente programa tiene como propósito eficientar el análisis de película radiocrómica, al automatizar el cálculo de respuesta promedio en los canales rojo, verde y azul. Con esta información, el programa genera una curva de calibración para cada canal y una estimación de la incertidumbre de las mediciones. 

El programa fue escrito utilizando el lenguaje de programación Python. Hace uso de bibliotecas externas como lmfit para crear ajustes de funciones y otras como pyplot y seaborn para propósitos de exhibición de gráficos. 

El código está disponible en un repositorio de GitHub con el siguiente link. https://github.com/SatoSim/INNN_calibration
En caso de utilizar Google Colab, no es necesario instalar ninguna librería externa. Además, es posible montar google drive para poder acceder a las imágenes. En caso de utilizar otro IDE, es necesario tener acceso local a las imágenes e instalar las librerías pertinentes desde una terminal. 

Matplotlib - pip3 install matplotlib
Lmfit - pip3 install lmfit
OpenCv - pip3 install opencv-python
Sklearn - pip3 install scikit-learn
Seaborn - pip3 install seaborn

El programa tiene como objetivo minimizar la intervención del usuario en los cálculos, a pesar de esto, el programa está segmentado en bloques donde el usuario puede corroborar que el análisis está siendo realizado correctamente. Adicionalmente, está diseñado para recibir como input un folder que contenga todas las imágenes del lote a analizar, y es capaz de distinguir los recuadros de película en cualquier orden. Por estas razones, el usuario puede escanear los recuadros de película radiocrómica en cualquier orientación y en cualquier disposición. Únicamente, se recomienda procurar un visible espaciamiento entre cada uno de los recuadros. 

