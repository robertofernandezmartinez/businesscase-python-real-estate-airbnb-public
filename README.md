# Caso de negocio - Python - Identificación de oportunidades de inversión inmobiliaria en una capital europea

## *(Este es sólo un resumen del proyecto. Para ver los archivos del proyecto, pedir acceso: https://www.linkedin.com/in/robertofernandezmartinez/)*

Cliente: Empresa inmobiliaria que hace inversiones en grandes ciudades comprando inmuebles para posteriormente alquilarlos como apartamentos turísticos.

La dirección ha tomado la decisión de invertir en Madrid, y nos ha encargado analizar los datos que el líder del sector AirBnb hace públicos para intentar encontrar los tipos de inmuebles que tienen mayor potencial comercial para alquier turístico.

Como entregable principal esperan la tipología (o tipologías) de inmuebles que el equipo de valoraciones debe buscar entre las oportunidades existentes en la ciudad y los principales barrios o zonas geográficas en las que focalizarse.

Para cumplir con el objetivo aplicamos la metodología de Discovery, técnicas de Business Analytics aprendidas y técnicas de analítica avanzada.

Aunque este caso concreto esté centrado en el alquiler turístico, el mismo tipo de aproximación se puede usar en casos que tengan un alto componente de "ubicación":

- apertura y cierre de tiendas
- reducción de capacidad instalada
- expansión de franquicias
- ...

## OBJETIVO

Localizar el perfil (o perfiles) de inmuebles que maximizan el potencial comercial en el mercado del alquiler turístico y las principales zonas donde buscarlos.

## PALANCAS

Tras hablar con el equipo de valoraciones nos dicen que las palancas que tienen más impacto en la rentabilidad de este tipo de inversiones son:

- Precio alquiler: cuanto más se pueda cobrar por noche mayor es la rentabilidad
- Ocupación: en general, cuantos más días al año se pueda alquilar un inmueble mayor es su rentabilidad
- Precio inmueble: cuanto más barato se pueda adquirir la propiedad mayor es la rentabilidad

## KPIs

- Ocupación: número de días anuales que el inmueble se pueda alquilar
- Precio del alquiler: precio por noche en euros según Airbnb
- Precio de un inmueble: número de metros cuadrados * precio medio del m2 en su zona, aplicando un 25% de descuento sobre el precio oficial por la fuerza de negociación del equipo de compras.

## ENTIDADES Y DATOS

Las entidades relevantes para nuestro objetivo y de las que podemos disponer de datos son:

- Inmuebles
- Propietarios
- Distritos

## PREGUNTAS SEMILLA

Sobre el precio del alquiler:

- Precio medio, rango de precios, precios por distritos y barrios
- Ranking de distritos y barrios por precio medio de alquiler
- Qué factores determinan el precio del alquiler (más allá de la localización)
- Relación entre el tamaño del inmueble y el precio por el que se puede alquilar
- Cómo influye la competencia (num inmuebles disponibles por barrio) sobre el precio del alquiler
- Variación de precios por tipo de alquiler (piso completo, habitación privada, habitación compartida)

Sobre la ocupación:

- Ocupación media total, por distritos, y por barrios
- Cómo de probable es cada nivel de ocupación en cada distrito
- Cual es el ranking de distritos y barrios por ocupación
- Qué factores determinan el precio del alquiler (más allá de la localización)
- Relación entre el tamaño del inmueble y su grado de ocupación
- Cómo influye la competencia (num inmuebles disponibles por barrio) sobre la ocupación

Sobre el precio de compra:

- Ranking de precio por m2 por distrito
- Ranking de precio del inmueble por distrito
- Relación entre el precio del inmueble y el precio del alquiler por distrito
- Relación entre el precio del inmueble y la ocupación por distrito
