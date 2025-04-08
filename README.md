

📊 Clustering Jerárquico con el Dataset de Iris

Este proyecto implementa distintas técnicas de clustering jerárquico utilizando el popular dataset Iris, aplicando diferentes métodos de enlace y visualizando los resultados mediante dendrogramas y reducción de dimensionalidad con PCA.
👥 Autor

    David Ricardo Jiménez Núñez

    

📁 Contenido

    Carga y preprocesamiento del dataset Iris

    Normalización de los datos con StandardScaler

    Construcción de dendrogramas con distintos métodos de enlace:

        single

        complete

        average

        ward

    Determinación de clusters usando corte en dendrograma

    Visualización de los clusters con reducción de dimensiones (PCA)

🔧 Requisitos

Este proyecto fue desarrollado en Google Colab y utiliza las siguientes bibliotecas de Python:

numpy
matplotlib
seaborn
scipy
scikit-learn

Puedes instalarlas con:

pip install numpy matplotlib seaborn scipy scikit-learn

▶️ Cómo ejecutar

    Clona este repositorio:

    git clone https://github.com/tu-usuario/tu-repo.git
    cd tu-repo

    Ejecuta el notebook en Google Colab o Jupyter Notebook.

También puedes acceder al notebook directamente desde Colab:
🔗 Abrir en Google Colab
📈 Resultados

El notebook genera:

    4 dendrogramas con diferentes métodos de enlace.

    Un gráfico de dispersión (PCA) que muestra los clusters finales determinados con el método ward.

📚 Referencias

    Scikit-learn - Iris dataset

    Documentación de scipy.cluster.hierarchy

    Guía de clustering jerárquico

📝 Licencia

Este proyecto es solo para fines educativos.