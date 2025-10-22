# Casino Royal Pluss

<p align="center">
  <img src="Logo.webp" alt="Royal Pluss Logo" width="300">
</p>
...
## 1. Fundamentos del sistema
Objetivos del sistema

El sistema Royal Pluss tiene como objetivo principal ofrecer una plataforma de casino online segura, confiable y accesible, donde los usuarios puedan disfrutar de una amplia variedad de juegos de azar como tragamonedas, póker, ruleta y blackjack.

Los objetivos específicos del sistema son:

  1.Proporcionar entretenimiento digital de calidad, garantizando una experiencia de usuario fluida, moderna y atractiva.
  
  2.Asegurar la protección y privacidad de los datos personales de los jugadores mediante sistemas avanzados de seguridad y cifrado.
  
  3.Cumplir con las normativas legales y licencias oficiales de juego online, garantizando la transparencia y equidad de cada partida.
  
  4.Facilitar el acceso multiplataforma, permitiendo que los usuarios jueguen desde dispositivos móviles y navegadores web.
  
  5.Fomentar la confianza del usuario, ofreciendo bonificaciones iniciales y soporte al cliente 24/7.
  
  6.Prevenir fraudes y accesos no autorizados mediante la implementación de protocolos de seguridad informática y verificación de identidad.
  
  7.Mantener y actualizar constantemente la plataforma, corrigiendo vulnerabilidades y evitando la aparición de versiones ilegales o copias no autorizadas.

## 2. Análisis y especificación de requisitiso funcionales y no funcionales
2.1 Requisitos Funcionales

El sistema desarrollado para la empresa permitirá las siguientes funcionalidades:

Registro y verificación de usuarios:

  -Validación mediante DNI.
  
  -Verificación de mayoría de edad.
  
  -Autenticación segura mediante correo electrónico y contraseña.

Juegos online disponibles:

  -Ruleta, póker, tragaperras y blackjack.
  
  -Todos los juegos integran generadores aleatorios certificados.

Sistema de bonificaciones:

  -Bono de bienvenida de 10 € al registrarse.
  
  -Bono adicional de 50 € por depósitos iguales o superiores a 100 €.
  
  -Gestión automática de bonificaciones.

Pagos y retiros:

  -Métodos admitidos: tarjeta bancaria, transferencia, PayPal, Bizum y criptomonedas.
  
  -Atención al cliente 24/7:
  
  -Chat en vivo y sistema de tickets de soporte.

Panel de administración:

  -Gestión de usuarios, promociones, estadísticas y seguridad.

Seguridad y control:

  -Bloqueo automático de cuentas sospechosas por fraude, minoría de edad o ludopatía.
  
  -Actualizaciones remotas para mejoras y parches de seguridad.
  
  -Cumplimiento de normativa legal vigente en materia de apuestas online.

2.2 Requisitos No Funcionales

Seguridad:
  -Protección de datos personales y financieros conforme a la legislación vigente (RGPD y normativas de juego online).
  
  Rendimiento:
  -Capacidad para soportar al menos 5.000 usuarios simultáneos sin interrupciones, con una disponibilidad mínima del 99,9 % del tiempo.
  
  Escalabilidad:
  -El sistema debe permitir la ampliación de usuarios, juegos y servicios sin afectar el rendimiento.
  
  Compatibilidad multiplataforma:
  -Funcionamiento en navegadores web y dispositivos móviles (Android/iOS).

Mantenibilidad:
  -Código modular y documentado que facilite actualizaciones y corrección de errores.
  
  Usabilidad:
  -Interfaz clara, intuitiva y accesible para usuarios de diferentes perfiles.
  
  Legalidad:
  -Cumplimiento de toda la normativa vigente sobre juego online y protección de datos personales.

2.3 Métodos para la Recogida de Requisitos

Para la obtención de los requisitos del sistema se utilizaron los siguientes métodos:

  -Entrevistas con jugadores y expertos del sector para identificar necesidades y restricciones legales.
  
  -Casos de uso para representar gráficamente las interacciones entre el sistema y los usuarios.
  
  -Sesiones de brainstorming con el equipo de desarrollo para generar ideas funcionales.
  
  -Prototipos del sistema para recibir retroalimentación temprana.
  
  -Reuniones de planificación con todo el equipo (programadores, jefes y socios) para acordar decisiones conjuntas.

2.4 Modelo de Ciclo de Vida del Proyecto

El modelo seleccionado es el Modelo en Espiral, ya que permite un desarrollo iterativo y seguro, ideal para un sistema de apuestas online que requiere mejoras continuas y evaluación constante de riesgos.

Fases principales:

  -Planificación: definición de requisitos técnicos, legales y de juegos.
  
  -Análisis de riesgos: detección de posibles fraudes, ciberataques o fallos.
  
  -Desarrollo y validación: creación de versiones funcionales y pruebas de seguridad.
  
  -Revisión con usuarios: recogida de opiniones y mejoras mediante actualizaciones.
  2.5 Historias de Usuario

Historia de Usuario 1 – Registro y Bonificación:

Como usuario nuevo, quiero registrarme y verificar mi identidad para entrar al casino y recibir mi bono de bienvenida de 10 €.
Criterios de aceptación:

  -El sistema valida la mayoría de edad.
  
  -Tras completar el registro, se otorgan automáticamente los 10 € de regalo.

Historia de Usuario 2 – Depósito y Bono Extra:

Como usuario registrado, quiero realizar un depósito de al menos 100 € para recibir un bono extra de 50 €.
Criterios de aceptación:

  -El sistema verifica el importe del depósito.
  
  -Se añaden automáticamente 50 € al saldo del usuario.

## 3. Diseño
  El diseño de la interfaz se basará en una estética elegante con tonos dorados y negros, transmitiendo una sensación de lujo y exclusividad.
  La página principal mostrará el logotipo de Royal Pluss, un menú superior con acceso a los distintos juegos (póker, ruleta, tragamonedas, blackjack) y un área central con banners promocionales y bonificaciones.
  Se priorizará una experiencia limpia, fácil de navegar y adaptable a móviles (diseño responsive).
  El sistema se desarrollará bajo una arquitectura cliente-servidor.
  
    Frontend: desarrollado con HTML5, CSS3 y JavaScript para la versión web, priorizando compatibilidad móvil.
    
    Backend: se implementará con Node.js y Express, encargándose de gestionar los datos de usuarios, autenticación y pagos.
    
    Base de datos: MySQL para el almacenamiento de información de jugadores, juegos y transacciones.
    
    Seguridad: se aplicará cifrado SSL y verificación de identidad mediante DNI digital para cumplir las normas de juego responsable.


## 4. Implementación
/**
 * Clase Hola
 *
 *
 * @author Raul
 * @version 1.0
 */
public class Hola
{ // Esta función hace una condición; si se cumple pasa, sino se dirige al else.
     
    public static void main(String[] args) 
    {
        System.out.println("Hola mundo");

        if (true) 
        {
            System.out.println("Condición verdadera");
        } 
        else 
        {
            System.out.println("Condición falsa");
        }
    }
}
<br>
/**
 * Clase para calcular el área de un círculo.
 * 
 * Esta clase contiene un método estático para calcular el área de un círculo 
 * a partir de su radio usando la constante PI.
 *
 * @author Raul
 * @version 1.0
 */
public class Area
{
    /** Valor de Pi. */
    private static final double PI = 3.1416;

    /** 
     * Calcula el área de un círculo.
     *
     * @param radio Radio del círculo.
     * @return El área calculada.
     */
    public static double calcularArea(double radio) 
    {
        return PI * radio * radio;
    }

    /** 
     * Método principal de ejecución.
     *
     * @param args Argumentos de línea de comandos (no se utilizan).
     */
    public static void main(String[] args)
    {
        double area = calcularArea(5);
        System.out.println("El área es: " + area);
    }
}

<br>
/**
 * Clase que realiza operaciones matemáticas simples.
 * 
 * Esta clase proporciona métodos estáticos para realizar operaciones básicas
 * como suma, resta, multiplicación y división entre dos números enteros.
 * 
 * <p>Ejemplo de uso:</p>
 * <pre>
 * int resultado = OperacionesMatematicas.sumar(5, 3);
 * System.out.println("Resultado: " + resultado);
 * </pre>
 *
 * @author Raul
 * @version 1.0
 */
 <br>
public class OperacionesMatematicas 
{
    /**
     * Suma dos números enteros.
     *
     * @param a Primer número.
     * @param b Segundo número.
     * @return La suma de ambos números.
     */
    public static int sumar(int a, int b) 
    {
        return a + b;
    }

    /**
     * Resta dos números enteros.
     *
     * @param a Primer número.
     * @param b Segundo número.
     * @return La diferencia entre ambos números.
     */
    public static int restar(int a, int b) 
    {
        return a - b;
    }

    /**
     * Multiplica dos números enteros.
     *
     * @param a Primer número.
     * @param b Segundo número.
     * @return El producto de ambos números.
     */
    public static int multiplicar(int a, int b)
    {
        return a * b;
    }

    /**
     * Divide dos números enteros.
     * 
     * Si el divisor es cero, muestra un mensaje y devuelve 0.
     *
     * @param a Dividendo.
     * @param b Divisor.
     * @return El cociente de la división, o 0 si el divisor es cero.
     */
    public static int dividir(int a, int b)  
    {
        if (b == 0)
        {
            System.out.println("No se puede dividir por cero");
            return 0;
        }
        return a / b;
    }

    /**
     * Método principal para comprobar las operaciones.
     *
     * @param args Argumentos de línea de comandos (no utilizados).
     */
    public static void main(String[] args) 
    {
        System.out.println("Suma: " + sumar(5, 3));
        System.out.println("Resta: " + restar(8, 2));
        System.out.println("Multiplicación: " + multiplicar(4, 6));
        System.out.println("División: " + dividir(9, 3));
    }
}

<br>
package com.mycompany.mavenproject2;

/**
 * Clase que realiza operaciones básicas de una calculadora.
 * 
 * Esta clase incluye métodos para sumar, restar, multiplicar y dividir
 * dos números enteros. Además, contiene un método principal para ejecutar
 * pruebas simples de las operaciones.
 *
 * <p>Ejemplo de uso:</p>
 * <pre>
 * Mavenproject2 calc = new Mavenproject2();
 * System.out.println("Suma: " + calc.sumar(10, 5));
 * </pre>


 <br>
 * @author Raul
 * @version 1.0

 */
public class Mavenproject2
{
    /**
     * Suma dos números enteros.
     *
     * @param x Primer número.
     * @param y Segundo número.
     * @return La suma de ambos números.
     */
    public int sumar(int x, int y) 
    {
        return x + y;
    }
        
    /**
     * Resta dos números enteros.
     *
     * @param x Primer número.
     * @param y Segundo número.
     * @return La diferencia entre ambos números.
     */
    public int restar(int x, int y) 
    {
        return x - y;
    }

    /**
     * Multiplica dos números enteros.
     *
     * @param x Primer número.
     * @param y Segundo número.
     * @return El producto de ambos números.
     */
    public int multiplicar(int x, int y)
    {
        return x * y;
    }

    /**
     * Divide dos números enteros.
     * 
     * Si el divisor es cero, muestra un mensaje de error y devuelve 0.
     *
     * @param x Dividendo.
     * @param y Divisor.
     * @return El resultado de la división, o 0 si el divisor es cero.
     */
    public int dividir(int x, int y)
    {
        if (y == 0)
        {
            System.out.println("Error: división por cero");
            return 0;
        }
        return x / y;
    }

    /**
     * Método principal para ejecutar la calculadora.
     *
     * @param args Argumentos de línea de comandos (no utilizados).
     */
    public static void main(String[] args)
    {
        Mavenproject2 c = new Mavenproject2();

        System.out.println("Suma: " + c.sumar(10, 5));
        System.out.println("Resta: " + c.restar(10, 5));
        System.out.println("Multiplicación: " + c.multiplicar(10, 5));
        System.out.println("División: " + c.dividir(10, 5));
    }
}

<br>


## 5. Plan de pruebas del sistema<br>

UNIDAD 01. ACTIVIDADES 06<br>
Antes de comenzar, analiza los tipos de tests que existen en este enlace.<br>
Ejercicio 01: Diseñando las pruebas de tus casos de uso<br>
En este ejercicio deberás detallar DOS casos de uso de tu software (ya deberías tenerlos<br>
creados) y tendrás que diseñar DOS pruebas por cada uno de tus casos de uso que aseguren<br>
que se cumplen esos requisitos funcionales.<br>
Para ello, deberás especificar el tipo de prueba (unitaria, negativa, aceptación, etc.), datos de<br>
entrada, acción a realizar y resultado esperado.<br>
Ejemplo ilustrativo:<br>
Caso de uso: Registrar usuario<br>
Requisito funcional: El sistema debe permitir a un usuario registrarse y validar que no exista otra<br>
cuenta con el mismo correo.<br>
Pruebas propuestas:<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario introduce un correo<br>
nuevo y datos válidos<br>
El sistema registra al usuario<br>
y envía correo de verificación<br>
Funcional / Negativa Usuario introduce un correo<br>
ya registrado<br>
El sistema muestra un<br>
mensaje de error indicando<br>
que el correo ya existe<br>
Ejercicio 02: Diseñando las pruebas de distintos casos de uso ficticios<br>
Caso de uso 1: Registrar usuario<br>
Requisito funcional: El sistema debe permitir a un nuevo usuario crear una cuenta,<br>
validando que el correo no exista y enviando un correo de verificación para activar el perfil.<br>
Tipo Acción / entrada Resultado esperado<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario crea cuenta con<br>
correo válido<br>
Cuenta creada y correo de<br>
verificación enviado<br>
Funcional / Negativa Correo ya existente Mensaje de error “correo ya<br>
registrado”<br>
Caso de uso 2: Iniciar sesión con autenticación segura<br>
Requisito funcional: El sistema debe autenticar a los usuarios mediante correo y contraseña<br>
cifrada, y ofrecer la opción de inicio de sesión con Google o Microsoft.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario inicia sesion con<br>
google<br>
Acceso correcto y datos<br>
Funcional / Negativa Contraseña incorrecta Error”credenciales invalidas”<br>
Caso de uso 3: Cerrar sesión en todos los dispositivos<br>
Requisito funcional: El sistema debe permitir al usuario cerrar su sesión activa en todos los<br>
dispositivos desde el panel de seguridad.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario hace clic en “Cerrar<br>
sesión en todos los<br>
dispositivos”<br>
Todas las sesiones se cierran<br>
Funcional / Negativa Verificación del usuario en<br>
otro dispositivo<br>
Usuario ya no tiene acceso<br>
sin volver a iniciar sesión<br>
Caso de uso 4: Recuperar contraseña mediante enlace temporal<br>
Requisito funcional: El sistema debe permitir restablecer la contraseña enviando un enlace<br>
temporal al correo del usuario, con caducidad de 15 minutos.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario solicita recuperación<br>
de contraseña<br>
Enlace temporal enviado<br>
(expira en 15 minutos)<br>
Funcional / Negativa Usuario usa enlace expirado Mensaje: “El enlace ha<br>
caducado, solicita uno nuevo”<br>
Caso de uso 5: Actualizar perfil profesional<br>
Requisito funcional: El sistema debe permitir editar los datos personales y profesionales<br>
(nombre, foto, puesto, redes sociales), guardando cambios en tiempo real.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario cambia nombre y<br>
foto<br>
Cambios guardados en<br>
tiempo real<br>
Funcional / Negativa Sube una imagen no<br>
permitida (por ejemplo, .exe)<br>
Mensaje: “Formato no<br>
permitido”<br>
Caso de uso 6: Subir archivos y documentos al proyecto<br>
Requisito funcional: El sistema debe permitir al usuario subir archivos (PDF, imágenes o<br>
CSV) de hasta 10 MB, validando el formato y guardándolos en la nube con versión<br>
automática.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario sube archivo PDF de
5 MB<br>
Archivo subido con éxito<br>
Funcional / Negativa Archivo de 20 MB Error: “El archivo supera el
límite de 10 MB”<br>
Caso de uso 7: Buscar oportunidades o proyectos activos<br>
Requisito funcional: El sistema debe permitir realizar búsquedas filtradas por palabra clave,<br>
cliente o estado del proyecto, mostrando resultados relevantes en menos de 2 segundos.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario busca “marketing” Resultados mostrados en < 2<br>
segundos<br>
Funcional / Negativa Búsqueda con caracteres no<br>
válidos<br>
Mensaje: “Entrada inválida”<br>
Caso de uso 8: Generar informe de rendimiento mensual<br>
Requisito funcional: El sistema debe permitir generar informes en PDF o Excel con métricas<br>
actualizadas (usuarios activos, ventas, incidencias), y ofrecer la descarga inmediata.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario elige formato PDF y<br>
hace clic en “Generar”<br>
Informe generado y descarga<br>
disponible
Funcional / Negativa Error en datos o métricas<br>
faltantes
Mensaje: “No se puede<br>
generar el informe por datos<br>
incompletos”
Caso de uso 9: Enviar notificaciones automáticas de eventos<br>
Requisito funcional: El sistema debe enviar notificaciones por correo o dentro de la<br>
aplicación cuando ocurran eventos relevantes (nuevo comentario, tarea asignada,<br>
renovación próxima).<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Nuevo comentario en<br>
proyecto<br>
Se envía notificación al<br>
usuario asignado<br>
Funcional / Negativa Usuario con notificaciones<br>
desactivadas<br>
No se envía aviso<br>
Caso de uso 10: Gestionar roles y permisos de usuario (rol administrador)<br>
Requisito funcional: El sistema debe permitir al administrador asignar, modificar o revocar<br>
roles y permisos, registrando todas las acciones en el log de auditoría.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Admin cambia de rol de<br>
usuario a “editor”<br>
Cambio guardado y<br>
registrado en el log<br>
Funcional / Negativa Usuario sin permisos intenta<br>
cambiar roles<br>
Error: “Acceso denegado”<br>
Caso de uso 11: Validar métricas financieras (caso tipo SaaS empresarial)<br>
Requisito funcional: El sistema debe comparar los ingresos mensuales actuales con los<br>
históricos (MRR, ARR) y marcar automáticamente anomalías o diferencias significativas.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Sistema compara MRR actual<br>
vs histórico<br>
Detecta diferencias y las<br>
marca como anomalías<br>
Funcional / Negativa Datos financieros incompletos Mensaje: “Datos insuficientes<br>
para análisis”<br>
Caso de uso 12: Eliminar cuenta y todos los datos personales<br>
Requisito funcional: El sistema debe permitir al usuario eliminar su cuenta de forma<br>
permanente, asegurando la eliminación completa de los datos conforme al RGPD.<br>
Tipo de prueba Entrada / acción Resultado<br>
Funcional Usuario confirma eliminación Cuenta y datos borrados<br>
según RGPD<br>
Funcional / Negativa Usuario intenta volver a<br>
acceder<br>
Acceso denegado, cuenta no
existe
<br>

### 5.1. Pruebas de aceptación
Nada por aquí 

## 7. Los diccionarios de datos

No hagas nada por aquí
