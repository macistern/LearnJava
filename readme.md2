Ejercicio:
Imagina que estás desarrollando un simulador de un juego de combate. El jugador puede estar en diferentes estados durante el juego, como "Normal", "Envenenado" y "Aturdido". Cada estado tiene un comportamiento diferente que afecta las acciones del jugador. Implementa el patrón de diseño State para gestionar los diferentes estados del jugador y su comportamiento asociado.

Pasos sugeridos para resolver el ejercicio:

Crea una clase base llamada PlayerState que represente el estado del jugador. Esta clase debería tener un método handle_input que se llamará cuando el jugador reciba una entrada (por ejemplo, un comando del usuario).

Define una clase derivada para cada estado específico del jugador, como NormalState, PoisonedState y StunnedState. Cada clase derivada debe implementar el método handle_input de manera diferente para reflejar el comportamiento único del estado.

En la clase principal del jugador, crea una variable de instancia llamada current_state que se inicialice con una instancia de NormalState (estado normal) por defecto.

Implementa métodos en la clase principal del jugador para cambiar el estado actual. Por ejemplo, podrías tener métodos como setNormalState, setPoisonedState y setStunnedState, que cambiarán el valor de current_state a la instancia correspondiente de cada estado.

En el método handle_input de la clase principal del jugador, simplemente delega la llamada al método handle_input del estado actual (current_state).

Prueba el simulador del juego enviando diferentes comandos al jugador y observa cómo el comportamiento cambia según el estado actual.


A esto agregale: El playerState tiene que ser una propiedad de una clase llamada "Player" (jugador) Player tiene que tener, en sus propiedades a que tipo de daño corresponde (normal, Poison, y Blunt)

Player tiene que tener un metodo que sea "Attack" y que se le pueda pasar por parametro a que player ataca, dependiendo del tipo de ataque, el player que es atacado puede cambiar de estado.

Ejemplo si el tipo de ataque es poison el player atacado queda envenenado (PoisonState). Si es blunt queda en estado inmovilizado (StunnedState) y si es normal el estado queda normal.
