Decorator
El patrón decorator permite añadir responsabilidades a objetos concretos de forma dinámica. 
Los decoradores ofrecen una alternativa más flexible que la herencia para extender las funcionalidades.

![patorn decorator](https://user-images.githubusercontent.com/42417223/52320159-bed7e380-299b-11e9-86d1-4c174d79ee35.jpg)

Component: define la interface de los objetos a los
que se les pueden adicionar responsabilidades dinámicamente.

ComponenteConcreteo: define el objeto al que se le puede adicionar una
responsabilidad.

Decorator: mantiene una referencia al objeto Component y define una
interface de acuerdo con la interface de Component.

DecoratorConcreto: adiciona la responsabilidad al Component.



Decorator propaga los mensajes a su objeto Component. Opcionalmente puede
realizar operaciones antes y después de enviar el mensaje.
