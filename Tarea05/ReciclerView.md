#                                             ReciclerView

El ReciclerView al igual que el Card View son ejemplos de un Widgets, los Widgets nos permiten accesar  
de manera muy rápida a los programas más usados, ademas nos brindan información acerca de los programas  
a los que pertenece. 

Como su nombre lo indica **esta clase se encarga de reciclar recursos**. Un ejemplo de ellos es cuando tenemos  
una lista, la cual es tan granade que no cabe en nuestra pantalla, y es necesario que se vaya actualizando,  
en este caso una ReciclerView permite reciclar targetas para mostrar la informacion mas actual e ir eliminando  
la información mas antigua. A continuación en la **Figura 1** se muestra un ejemplo.  

![Titulo][ReciclerView.gif "Figura 1. Ejemplo de ReciclerView."]


El ReciclerView esta conformado por 5 clases:

* Adapter
* ViewHolder
* LayoutManager
* ItemDecoration
* ItemAnimator

**Adapter**  
Esta clase se encarga de crear las Views necesarias para cada elemento del RecyclerView, además, está muy unida al  
ViewHolder.

**ViewHolder**  
Podriamos considerarlo como el cache de las vistas, el cual reutiliza las vistas en lugar de crear mas.

**LayoutManager**  
Se encarga deL layout de todas las vistas del ReciclerView.

**ItemDecoration**  
Nos permite modificar los elemntos del ReciclerView.

**ItemAnimator**  
Se encarga como su nombre lo dice de animar el ReciclerView, añadiendo o eliminando elementos.


