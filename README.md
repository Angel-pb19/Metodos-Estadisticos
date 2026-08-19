# Metodos-Estadisticos
Curso  MET.ES semestre Agosto-Diciembre 2026


WAOS

## Semana 2

## 12/08/2026 Inicio de la materia
+ Preparar area de trabajo
+ Crear cuenta en Github
+ Crear el primer repositorio
+ Motidifcar el archivo

## 12/08/2026 Segunda clase

+Activar credenciales 
+Modificar el archivo
+Sincronizar datos
+fghhgf


##19/08/2026 Tercera clase

+Archivo excel

#importar datos ----
#Usar la funcion "read.csv" para importar datos en excel. 

Obs <- read.csv("ejemplo_2.csv", header = TRUE)

#Declarar columna de tratamiento como un factor y sus niveles
#se utilizo la funcion "as.factor".

Obs$Tratamiento <-as.factor(Obs$Tratamiento)
Obs$Tratamiento

#Grafca----

#Boxplot de los dato

boxplot(Obs$IE ~ Obs$Tratamiento)





