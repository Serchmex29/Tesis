# Tesis: Análisis y Clasificación de Materiales Tipo Perovskitas para Celdas Solares usando Machine Learning

Este repositorio contiene el conjunto de datos, el código fuente y los resultados experimentales asociados a la tesis de licenciatura titulada:

**“Análisis y Clasificación de Materiales Tipo Perovskitas para Celdas Solares usando Machine Learning”**

## 📌 Objetivo del proyecto

Desarrollar un modelo de clasificación supervisada basado en el algoritmo **K-Nearest Neighbors (KNN)** para predecir la formabilidad estructural de compuestos tipo perovskita **ABX₃**, a partir de parámetros como el factor de tolerancia y el factor octaédrico.

---

## 📊 Descripción del conjunto de datos

- **Archivo:** `perovskite_dataset.csv`
- **Observaciones:** 576 combinaciones ABX₃.
- **Variables:**  
  - Radios iónicos de A, B y X  
  - Factor de tolerancia `t`  
  - Factor octaédrico `μ`  
  - Etiqueta binaria de formabilidad (1 = forma perovskita, 0 = no forma)

---

## 🤖 Modelo de Machine Learning

- Algoritmo: K-Nearest Neighbors (KNN)
- Proceso:
  - Normalización de variables
  - Partición entrenamiento / prueba
  - Selección de hiperparámetro **k** mediante validación cruzada
- Métrica principal: Tasa de error de clasificación

---

## 📚 Citación

Si utilizas este repositorio para fines académicos o de investigación, por favor cita la tesis original:

> Sergio Fernández Porras, *Análisis y Clasificación de Materiales Tipo Perovskitas para Celdas Solares usando Machine Learning*, Benemérita Universidad Autónoma de Puebla, 2025.

---

## ⚖️ Licencia

Este proyecto se distribuye bajo la licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

