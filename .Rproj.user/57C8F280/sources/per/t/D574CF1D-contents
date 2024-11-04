###   LISTAS

# Ej

### 1. Crea una lista que contenga al menos cuatro tipos diferentes de datos
# (incluyendo al menos un vector, una matriz, y un data frame). Luego,
# escribe código para acceder a cada uno de estos elementos por su índice.

num_de_comidas <- list(
  numero = 5,
  vector = c(1:10),
  matriz = matrix(c(1:10), nrow = 2),
  data_frame = data.frame(sexo = c("Masculino", "Femenino", "Masculino", "Femenino"), 
                          edad = c(28,34,29,32), peso = c(55,76,58,64))
)
num_de_comidas

num_de_comidas[[2]]

### 2. Almacena datos de producción en experimentos de fermentación.
# • Crea una lista fermentacion con 4 elementos, cada uno representando un
#  experimento de fermentación.
# • Cada elemento debe ser una lista con: Cepa, Condición, Producción Etanol.
# • Encuentra la condición con la mayor producción de etanol.

fermentacion <- list(
  list(Cepa = "NA234DA1", Condicion = "Sin O", prod_etanol = 12.36),
  list(Cepa = "NA234DA2", Condicion = "Bajo", prod_etanol = 6.13),
  list(Cepa = "NA234DA3", Condicion = "Medio", prod_etanol = 2.80),
  list(Cepa = "NA234DA4", Condicion = "Alto", prod_etanol = 1.25)
)

str(fermentacion)

cepa_etanol <- max(sapply(fermentacion, function(x) x$prod_etanol))
cepa_etanol

### 3. Mantén un registro de ensayos clínicos en una lista.
# • Crea una lista ensayos_clinicos con 3 elementos, cada uno representando
#  un ensayo clínico.
# • Cada elemento debe ser una lista con: Nombre, Fase, NúmeroPacientes.
# • Calcula el total de pacientes involucrados en todos los ensayos clínicos.

ensayos_clinicos <- list(
  list(Nombre = "Lupe", Fase = "1", num_pacients = 15),
  list(Nombre = "Andy", Fase = "2", num_pacients = 20),
  list(Nombre = "Luis", Fase = "3", num_pacients = 15)
)

pacientes_totales <- sum(sapply(ensayos_clinicos, function(x) x$num_pacients))
pacientes_totales

###  4. Añade un nuevo elemento a la compleja_lista que sea otra lista 
#  conteniendo información relevante a un experimento microbiológico 
# (p.ej., fechas, resultados de crecimiento, tipo de medio de cultivo). 
# Accede a un elemento específico dentro de esta lista anidada.

compleja_lista <- list(
  dia = c(1:30),
  colonias = c(sample(80:200),10),
  matriz = matrix(c(1:10), nrow = 2),
  data_frame = data.frame(medio = c("LAS", "DSY", "LSD", "WER", "YPD"))
)


compleja_lista
