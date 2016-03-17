# Apache vs Nginx
Nginx se basa en una arquitectura orientada a eventos. Apache se basa en una arquitectura basada en procesos.

Es interesante observar que Apache en su primera versión no estaba teniendo la arquitectura multitarea. Más tarde se añadió Apache MPM (módulo multi-procesamiento) para lograrlo.

Nginx no crea un nuevo proceso para una nueva solicitud. Apache crea un nuevo proceso para cada solicitud.

En Nginx, el consumo de memoria es muy bajo para servir páginas estáticas. Pero, la naturaleza de Apache de crear nuevos procesos para cada petición aumenta el consumo de memoria.

Varios resultados de evaluación comparativa indica que, en comparación con Apache, Nginx es extremadamente rápido para servir páginas estáticas.

Desarrollo Nginx no comenzó hasta 2002. Pero Apache versión inicial fue en 1995.

En la difícil situación configuraciones, en comparación con Nginx, Apache puede ser configurado fácilmente ya que viene con muchas características de configuración para cubrir toda la gama de requisitos.

Cuando se compara con Nginx, Apache tiene una excelente documentación.

En general, Nginx tiene menos componentes para agregar más características. Pero Apache tiene un montón de características y proporciona mucha más funcionalidad que Nginx.

Nginx no son compatibles con sistemas operativos como OpenVMS y IBMi. Pero Apache soporta mucho más amplia gama de sistemas operativos.

Nginx sólo viene con las características básicas que se requieren para un servidor web, es ligero en comparación a Apache.

El rendimiento y la escalabilidad de Nginx no es completamente dependiente de los recursos de hardware, mientras que el rendimiento y la escalabilidad de Apache depende de los recursos de hardware subyacentes como la memoria y la CPU.