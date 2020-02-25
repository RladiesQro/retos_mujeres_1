# retos_mujeres_1
## R-Ladies_Qro <- retos(dataset, by = mujeres)

R_Retos con base de datos de mujeres quienes trabajan con datos. Es esta reunión nos plantearemos preguntas y cuyo reto será contestarlas con los datos de estas dos bases_de_datos. 

- La primera base de datos es de los eventos de RLadies que se han trabajado en datos-de-miercoles. Estos datos fueron extraídos de la plataforma Meetup; el primer dataset contiene la información de cada grupo o "capítulo" y el segundo, los datos de todos los eventos que han organizado a la fecha (26/06/2019). https://github.com/cienciadedatos/datos-de-miercoles/blob/master/datos/2019/2019-06-26/README.md

### Para acceder a este dataset
```
# install_packages("readr")
capitulos_rladies <- readr::read_csv("https://raw.githubusercontent.com/cienciadedatos/datos-de-miercoles/master/datos/2019/2019-06-26/capitulos_rladies.csv")
eventos_rladies <- readr::read_csv("https://raw.githubusercontent.com/cienciadedatos/datos-de-miercoles/master/datos/2019/2019-06-26/eventos_rladies.csv")
```

- La segunda base de datos es sobre los salarios de las mujeres como profesionistas, dataset previamente trabajado en _tidytuesday_ https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-03-05. Mujeres en la fuerza laboral: datos de la Oficina de Estadísticas Laborales y la Oficina del Censo sobre las mujeres en la fuerza laboral. Existen datos históricos sobre las ganancias de las mujeres y la situación laboral, así como información detallada sobre la ocupación específica y las ganancias de 2013-2016.

Trabajaremos con los datos ya limpios y arreglados:
````
jobs_gender <- readr::read_csv("https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-03-05/jobs_gender.csv")
earnings_female <- readr::read_csv("https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-03-05/earnings_female.csv") 
employed_gender <- readr::read_csv("https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-03-05/employed_gender.csv") 
```



