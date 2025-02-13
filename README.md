# Copia-MetricaEER

El siguiente codigo es una copia del repositorio, adaptado a un dataset propio , el cual se encuentra en el link https://github.com/Ruframapi/HABLA

## Pasos Realizados
1. **Carga de Datos**
   
    El dataset se encuentra en el siguiente repositorio [https://computacion.unl.edu.ec/share/page/context/shared/folder-details?nodeRef=workspace://SpacesStore/4108f431-fd07-40d0-ba0b-4e0c7a57cb06](https://computacion.unl.edu.ec/share/page/context/shared/folder-details?nodeRef=workspace://SpacesStore/e9b51759-b032-4b9c-83aa-2905c0fd1e18), pero se puede acceder mediante una solicitud a https://computacion.unl.edu.ec/suplantacion-de-voz
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

   #Archivo que contiene las configuraciones necesarias
   # Respositorio que contiene los archivos !git clone https://github.com/josuesauca/Copia-MetricaEER
   !unzip ./drive/MyDrive/archivo123.zip
   

