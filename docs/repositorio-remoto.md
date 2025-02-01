## ¿Como crear un repositorio remoto en GitHub y sincronizarlo con el repositorio local?

### 1. Crear un repositorio en GitHub

1. **Inicia sesión en GitHub**: Ve a GitHub y accede con tu cuenta.
2. **Crear un nuevo repositorio**: Haz clic en el icono de tu perfil en la esquina superior derecha y selecciona "Your repositories".Luego, haz clic en "New" para crear un nuevo repositorio y rellena la informacion necesaria. 

### 2. **Inicializar tu repositorio local**
        
1. Abre la terminal (o Git Bash en Windows).
    
2. Ve al directorio de tu proyecto local

    ![1](/images/1..jpeg)

3. Si aun no has iniciado un repositorio local, lo puedes hacer asi:

    ![2](/images/2..jpeg)

Esto crea un repositorio vacio en tu carpeta de proyecto 

4. Agrega tus archivos y haz el primer commit:

    ![3](/images/3..jpeg)

### 3. **Conectar el repositorio local y el remoto**

1. Obtener la URL del repositorio remoto: Una vez que creas el repositorio en GitHub, verás la URL del repositorio, algo así como https://github.com/tu_usuario/tu_repositorio.git.
    
2. Añadir el repositorio remoto: En la terminal, ejecuta el siguiente comando para vincular tu repositorio local con el remoto:

    ![4](/images/4..jpeg)

### 4. **Realiza los cambios**

1. Edita el archivo: añadiendo los cambios que deseen 

2. Verificar cambios, esto para corroborar que si se haya registrado un cambio

   ![11](/images/11..jpeg)

3. Agregar los cambios a el area de Stagging: si agregas o modificas archivos, usa git add para incluirlos en el siguiente commit:

   ![12](/images/12..jpeg)

4. Hacer commit de los cambios: 

    ![13](/images/13..jpeg)

### 5. **Subir tu codigo al repositorio remoto**

1. Esto subirá tu código al repositorio remoto de GitHub.

  ![6](/images/6..jpeg)

### 6. **Clonar un repositorio existente (opcional)**

1. Si ya tienes un repositorio remoto en GitHub y quieres clonarlo en tu máquina local:

![10](/images/10..jpeg)

<font color="#ADD8E6">

## **Lo has logrado ahora puedes guardar tu proyecto en la nube y desarrollarlo local**

