# Tabla Comparativa Final de Desempeño de Modelos (Conjunto de Prueba)

| Modelo                    | Accuracy | Precision | Recall | F1-score | AUC   |
| :------------------------ | :------- | :-------- | :----- | :------- | :---- |
| K-Nearest Neighbors (KNN) | 0.688    | 0.583     | 0.414  | 0.485    | 0.722 |
| Random Forest             | 0.942    | 0.957     | 0.875  | 0.914    | 0.951 |
| Deep Neural Network (DNN) | 0.828    | 0.714     | 0.855  | 0.778    | 0.920 |

---

### Conclusión Final

Después de evaluar los tres modelos en el conjunto de prueba, el **Random Forest** emerge como el modelo con el mejor rendimiento general.

- **Random Forest** no solo alcanzó la mayor precisión (Accuracy) con un **94.2%**, sino que también obtuvo el F1-score más alto (**0.914**), lo que indica un excelente equilibrio entre precisión y recall.
- La **DNN**, a pesar de su complejidad, tuvo un rendimiento inferior, especialmente en Precisión (0.714) y F1-score (0.778). Su alta sensibilidad (Recall de 0.855) se logró a costa de un número mayor de falsos positivos, una compensación explícitamente buscada durante su diseño (usando `class_weight` y un umbral de clasificación bajo).
- El modelo **KNN** demostró ser un modelo flojo, fue superado por la capacidad del Random Forest para manejar la complejidad de los datos.

**Recomendación Final:** Se recomienda el modelo **Random Forest** para su implementación en producción. Demostró ser el más robusto, equilibrado y con el mejor desempeño predictivo para este problema de clasificación, tal como se concluye en el propio notebook de análisis.
