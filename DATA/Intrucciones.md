# Instrucciones para el uso del dataset en la evaluación de la métrica EER

Este directorio contiene los archivos necesarios para probar y evaluar el dataset generado en el experimento. A continuación, se detallan los pasos para su uso:

## 📂 Contenido de la carpeta `DATA/`
- `protocol_dataset_inicial.txt`: Contiene los labels del dataset original utilizado en la prueba.
- `protocol_dataset_mio.txt`: Contiene los labels del dataset generado con StarGAN.
- Archivos de prueba (`test_experimento1.lst`, `test_experimento2.lst`, `test_experimento3.lst`): Listados de archivos utilizados en distintos experimentos.

## 🔧 Pasos para utilizar el dataset
1️⃣ **Descargar los archivos de Google Drive**  
   - Puedes obtener los archivos de protocolo en los siguientes enlaces:  
     - [protocol_dataset_inicial.txt](https://drive.google.com/file/d/1wuL_PEvf08298zB4v6dKStG0EKB1Uzbq/view?usp=sharing)  
     - [protocol_dataset_mio.txt](https://drive.google.com/file/d/16HW7nNGRk0c8jNB1VRJ8XokFXwcn7wH/view?usp=sharing)  
   - Guarda estos archivos dentro de la carpeta `DATA/`.

2️⃣ **Ejecutar el script en Google Colab**  
   - Abre el archivo `Metrica_EER_DatasetGenerado.ipynb` en Google Colab.  
   - Asegúrate de que los archivos están correctamente copiados en la ruta `DATA/asvspoof2019_LA/`.  
   - Corre las celdas de código que mueven y renombran los archivos de prueba.  

3️⃣ **Prueba del dataset**  
   - Los datos se procesarán para evaluar el modelo LFCC-LCNN en la detección de voice spoofing.  
   - Se analizarán los resultados de la **Tasa de Error de Igualación (EER)** para determinar la efectividad del dataset generado.  

📌 **Nota:**  
Asegúrate de verificar que los archivos están correctamente cargados antes de ejecutar las pruebas.  

---

### **✅ Explicación de mejoras en la documentación:**
1. **Claridad y estructura:** Se explica qué archivos están en la carpeta y su propósito.  
2. **Instrucciones paso a paso:** Se detallan los pasos para descargar, configurar y ejecutar las pruebas.  
3. **Enlaces directos a Google Drive:** Facilitan la descarga de los archivos necesarios.  
4. **Nota final:** Asegura que el usuario verifique que todo está en orden antes de ejecutar el script.  

🚀 **Con este archivo `Intrucciones.txt`, cualquier persona podrá comprender el propósito del dataset y cómo usarlo correctamente en las pruebas.**  

🔹 **¿Quieres agregar más detalles o está perfecto así?** 😊

