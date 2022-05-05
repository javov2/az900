# Describir los componentes principales de la arquitectura de Azure

## Objetivos de aprendizaje

Después de completar este módulo, usted será capaz de describir los beneficios y el uso de:

- Regiones de Azure, pares de regiones y zonas de disponibilidad.
- Recursos de Azure, grupos de recursos y Azure Resource Manager.
- Las suscripciones de Azure y los grupos de gestión.

![top-down hierarchy](images/2022-05-02-15-54-11.png)

- Recursos: instancias de servicios
- Grupos de recursos: recursos que se combinan, actúan como un contenedor lógico. Por ejemplo, todos estos recursos forman parte de dev, stage, prod.
- Suscripciones: agrupa las cuentas de usuario y los recursos que se han creado para esas cuentas de usuario. Existen límites o cuotas de recursos. Las organizaciones pueden utilizar las suscripciones para gestionar los costes y los recursos que se crean.
- Grupos de gestión: ayudan a gestionar el acceso, la política y el cumplimiento de varias suscripciones.

### Regiones de Azure

![Regiones de Azure
](images/2022-05-02-16-06-06.png)

- Servicios zonales: Anclan el recurso a una zona específica (por ejemplo, VMs, discos gestionados, direcciones IP).
- Servicios redundantes por zonas: La plataforma se replica automáticamente entre zonas (por ejemplo, almacenamiento redundante por zonas, base de datos SQL.
- Servicios no regionales: Los servicios están siempre disponibles desde las geografías de Azure y son resistentes a las interrupciones en toda la zona, así como a las interrupciones en toda la región.

#### Pares de regiones

Son regiones de Azure interconectadas, de modo que una es la reserva de la otra.
Por ejemplo: Oeste de EEUU y Este de EEUU.

## Grupos de recursos Azure

- Agrupación lógica
  - Ciclo de vida
  - Autorización

- Etiquetas

### Azure Resource Manager

![Administrador de recursos de Azure
](images/2022-05-02-16-18-38.png)

## Azure Subscriptions

Una suscripción de Azure es una unidad lógica de servicios de Azure que se vincula a una cuenta de Azure, que es una identidad en Azure Active Directory (Azure AD) o en un directorio en el que confía Azure AD.

Hay dos tipos de límites de suscripción que puede utilizar:

- Límite de facturación
- Límite de control de acceso

![Personalizar la facturación para satisfacer sus necesidades
](images/2022-05-02-17-06-59.png)

## Grupos de gestión de Azure

### Jerarquía de grupos de gestión y suscripciones

![Jerarquía de grupos de gestión y suscripciones
](images/2022-05-02-17-11-13.png)
