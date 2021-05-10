# Azure

Azure es una plataforma de servicios en la nube para ayudar a crear soluciones dependiendo de las
necesidades de su empresa. Es por esto que cuenta con una gran variedad de servicios. Algunos 
ejemplos son Redes, Almacenamiento, Móvil, Bases de datos.

![image](https://user-images.githubusercontent.com/83619479/117604574-6021e700-b11b-11eb-84bf-abbda260ba26.png)

# La Nube


![image](https://tynmedia.com/tynmag/wp-content/uploads/sites/3/2019/06/El-futuro-empresarial-est%C3%A1-en-la-nube-e1560566724502.png)

Es una prestacion de servicios informaticos a traves de internet, estos servicios incluyen servidores,
almacenamiento, bases de datos, redes, software, análisis e inteligencia.

# Modelos de servicio de la nube

Infraestructure as a service (IaaS)

    Este modelo de servicio en la nube es el más cercano a la gestión de servidores físicos. El proveedor de la nube mantiene
    el hardware actualizado, pero el mantenimiento del sistema operativo y la configuración de la red se dejan al inquilino 
    de la nube.
      
Platform as a service (PaaS)
      
    En este modelo de servicio en la nube, el proveedor de la nube administra las máquinas virtuales y los recursos de red, y
    el inquilino de la nube implementa sus aplicaciones en el entorno de alojamiento administrado.
      
Software as a service (SaaS)

    En este modelo de servicio en la nube, el proveedor de la nube gestiona todos los aspectos del entorno de la aplicación,
    como máquinas virtuales, recursos de red, almacenamiento de datos y aplicaciones. El inquilino de la nube solo necesita
    proporcionar sus datos a la aplicación administrada por el proveedor de la nube.

En la siguiente imagen se puede obervar cómo se delegan las responsabilidades de los diferentes servicios en la nube con el proveedor y el que obtiene los servicios
![image](https://user-images.githubusercontent.com/83619479/117605150-b0e60f80-b11c-11eb-9fb7-e318cb15d3db.png)

Una de las ventajas de la nube es que solamente pagas por lo que utilizas, por lo cual se aprovecha al 100% todo lo que estés pagando. De esta manera tu empresa no invierte en algo como un servidor compelto que no estarían utilizando.


# Tipos de nubes

Hay tres modelos de implementación en la nube: nube pública, nube privada y nube híbrida.

Nube pública

    Los servicios se ofrecen a través de la Internet pública y están disponibles para cualquier persona que desee adquirirlos. 
    Los recursos en la nube, como los servidores y el almacenamiento, son propiedad y están operados por un proveedor de 
    servicios en la nube externo y se entregan a través de Internet.
    
Nube privada

    Los recursos informáticos son utilizados exclusivamente por usuarios de una empresa u organización. Una nube privada se 
    puede ubicar físicamente en el centro de datos en el sitio de su organización. 
    
Nube híbrida

    Este entorno informático combina una nube pública y una nube privada al permitir que los datos y las aplicaciones se 
    compartan entre ellos.
    
# Estructura organizativa para los recursos en Azure

La estructura organizativa para los recursos en Azure tiene 4 niveles: management groups (grupos de administración), 
subscriptions (subscripciones), resource groups (grupos de recursos), y resources (recursos).

![image](https://user-images.githubusercontent.com/83619479/117606457-834e9580-b11f-11eb-9971-4f969861c74d.png)

Grupos de administración: 

    Estos grupos son los que se encargan administrar el acceso, las políticas y el cumplimiento de varias 
    suscripciones. Todas las suscripciones en un grupo de administración heredan automáticamente las 
    condiciones aplicadas al grupo de administración.
            
Suscripciones     

    Una suscripción agrupa las cuentas de usuario y los recursos que han sido creados por esas cuentas de 
    usuario. Para cada suscripción, existen límites o cuotas en la cantidad de recursos que puede crear y 
    usar. Las organizaciones pueden usar suscripciones para administrar los costos y los recursos que 
    crean los usuarios, equipos o proyectos.

Grupos de recursos
            
    Los recursos se combinan en grupos de recursos, que actúan como un contenedor en el que se implementan 
    y administran recursos de Azure, como aplicaciones web, bases de datos y cuentas de almacenamiento.
            
Recursos
 
    Los recursos son instancias de servicios que el usuario crea como: máquinas virtuales, almacenamiento 
    o bases de datos.
            
![image](https://user-images.githubusercontent.com/83619479/117606811-48992d00-b120-11eb-9399-a02874c47cd1.png)

Toda la información recuperada fue obtenida por medio de: https://docs.microsoft.com/en-us/learn/browse/ 
