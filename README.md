# Seguimiento de Pacientes - React + TypeScript + Vite + Zustand
*📓 [Español](#inicio)*
*📓 [English](#start)*

### <a id="inicio" />
Esta es una aplicacion web construida con TypeScript, React y Vite en la que aparte, se utiliza Zustand, una libreria que se utilizara para manejar el estado global de la aplicación. Este proyecto permite agregar datos de una mascota para hacer un seguimiento de pacientes que han ingresado a una veterinaria. Como se mencionaba, se usa store de Zustand para almacenar el estado global de la aplicación y contiene toda la lógica para realizar acciones tales como agregar, editar o eliminar paciente. Para hacer más dinámico el proyecto se utiliza también React-Toastify para mostrar alertas al momento de realizar una acción.

Algunas de las cosas que se aprendieron con este proyecto son:

### <a  /> useReducer
Se toma un enfoque un tanto diferente a las otras versiones del proyecto ya que se gestiona el estado del carrito en el reducer. Con los reducers se puede agrupar la lógica para que cuando se dispare (dispatch) una acción en alguna parte del proyecto se envien ciertos datos (payload) en caso de necesitarse y sean recibidos tanto dispatch como payload en el reducer y se ejecute código asignado a cada acción.

### <a  /> LocalStorage
Se utilizó localStorage para almacenar los datos de los productos agregados al carrito

### <a  /> Modularidad y Reutilización de Componentes
La reutilización de componentes en este proyecto fue esencialmente necesaria para mostrar los productos y los productos dentro del carrito, evitando código duplicado.

### <a  /> Custom Hooks
Dentro del custom hook, se encuentra la lógica para agregar, eliminar o aumentar la cantidad de elementos agregados al carrito. De igual manera se encuentran varios hooks como useEffect para la parte del localStorage, useMemo para states derivados  y useState para el carrito

### <a  /> Optimización del Rendimiento (Performance)
Además de utilizar componentes, mediante el uso de operadores ternarios, se establece si se renderiza un componente o no, lo que puede mejorar el rendimiento de las aplicaciones web.

### <a  /> Tipado Estricto con TypeScript
Se definieron tipos para los props de los componentes y funciones

### <a  /> Validación de Formularios
Se configuraron los forms de manera que se verifique si el usuario ingresa valores válidos.

### <a  /> Helpers
Se crearon funciones especificas para el formato de fecha y moneda mostrada en la interfaz (formatCurrency y formatDate)

### <a  /> Context
El uso de context en el proyecto sirvió para compartir datos y funciones entre distintos componentes sin necesidad de pasar props "manualmente"

### <a  /> Framework CSS
Se utilizó Bootstrap para manejar los estilos de la página

*📷[Screenshots](#screenshots)*

# Patient Tracker - React + TypeScript + Vite + Zustand

### <a id="start" />

This is a web application built with TypeScript, React, and Vite. Zustand, a library used to manage the application's global state. This project allows you to add pet data to track patients who have entered a veterinary clinic. As mentioned, Zustand's store is used to store the application's global state and contains all the logic to perform actions such as adding, editing, or deleting patients. To make the project more dynamic, React-Toastify is used to display alerts when an action is performed.

Some of the things learned with this project are:

### <a /> useReducer
This takes a slightly different approach than other versions of the project, as the cart state is managed in the reducer. With reducers, you can group logic so that when an action is triggered (dispatch) in some part of the project, certain data (payload) is sent if needed and both dispatch and payload are received in the reducer and code assigned to each action is executed.
### <a  /> LocalStorage
LocalStorage was used to store data for products added to the cart.

### <a  /> Modularity and Components Reusability
Reusing components in this project was essential to display the products and items within the cart, avoiding duplicate code.

### <a  /> Custom Hooks
Inside the custom hook is the logic for adding, removing, or increasing the number of items added to the cart. There are also several hooks, such as useEffect for the localStorage section, useMemo for derived states, and useState for the cart.

### <a  /> Performance Optimization
In addition to using components, by using ternary operators, you can set whether a component is rendered or not, which can improve the performance of web applications.

### <a  /> Strict Typing with TypeScript
Types were defined for component and function props

### <a  /> Form Validation
Forms have been configured to check whether the user enters valid values.

### <a  /> Helpers
Specific functions were created for the date and currency format displayed in the interface (formatCurrency and formatDate)

### <a  /> Context
Using context in this project made it easier to share data and functions between different components without having to pass props "manually"

### <a  /> Framework CSS
Bootstrap was used to handle the page styles

---
### <a id="screenshots" /> 
# Screenshots
![Interfaz](https://github.com/ReploidGI0/patient-tracking/blob/main/images/veterinaria1.PNG "Interfaz")
![Interfaz](https://github.com/ReploidGI0/patient-tracking/blob/main/images/veterinaria2.PNG "Interfaz")
![Interfaz](https://github.com/ReploidGI0/patient-tracking/blob/main/images/veterinaria3.PNG "Interfaz")
![Interfaz](https://github.com/ReploidGI0/patient-tracking/blob/main/images/veterinaria4.PNG "Interfaz")
![Interfaz](https://github.com/ReploidGI0/patient-tracking/blob/main/images/veterinaria5.PNG "Interfaz")
![Interfaz](https://github.com/ReploidGI0/patient-tracking/blob/main/images/veterinaria6.PNG "Interfaz")
![Interfaz](https://github.com/ReploidGI0/patient-tracking/blob/main/images/veterinaria7.PNG "Interfaz")
