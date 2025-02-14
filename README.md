# Tickets-TicoV2
**⚙️ | Sistemas de tickets:**
> Esta nueva versión trae la posibilidad de tener hasta 2 sistemas de tickets.

> Esta nueva funcionalidad se activa simplemente usando tu **prefijo seguido del número del sistema (1 o 2)**
> Ejemplo: !tickets 1 (mensaje a mostrar en el menú (opcional))
> Esto activará el sistema de tickets 1
> Ejemplo 2: !tickets 2 (mensaje a mostrar en el menú (opcional))

**📖 | Información**
> Acá tienes la información sobre este sistema

> **🗣️ | Palabras clave:**
Este sistema cuenta con 3 Palabras claves, las cual son: **{tagg-user}, {tagg-rol} y {razon}**. ¿Para que sirven y donde se pueden usar?

> Estas palabras claves sirven para poder etiquetar al usuario que abre el ticket **{tagg-user}**, para poder etiquetar al rol de staff **{tagg-rol}** y para colocar la razón por la cual fué abierto el ticket **{razon}** en cualquier parte de tu mensaje de bienvenida, estan creadas para darle una mejor estetica a tus tickets 😎.

> Estas palabras claves solo funcionan en los mensajes de bienvenida de los tickets y en la parte de "Titulo y Descripción"

> **__Ejemplos de uso:__**

> - Bienvenido al ticket **{tagg-user}**
> - **Resultado:** Bienvenido al ticket @Tico#

> - **{tagg-rol}**, atiende de buena manera
> - **Resultado:** @RolStaff, atiende de buena manera

> - Razón del ticket: **{razon}**
> - **Resultado:** Razón del ticket: Necesito ayuda

**❌ | Bloquear-desbloquear usuarios:**
> Con esta función podrás bloquear a usuarios para que no puedan abrir tickets. Para esos usuarios que mal usan los tickets

**📂 | Categoria Global de los tickets:**
> Configura la categoría donde se abrirán los tickets creados

**📂 | Categoria personalizable para cada panel:**
> Configura una categoria única donde se abrirán los tickets para cada panel.

> Se puede configurar una categoría para cada panel, si en dado caso no se ha configurado alguna, el sistema creará el ticket en la categoría global de los tickets

**🛠️ | Rol staff:**
> Con esta función indicarás cual es el rol de staff, el cual podrá ver los tickets, atender, cerrar y/o bloquear usuarios del sistema de tickets. Puedes configurar hasta 10 roles de staff

**🔧 | Restricción por rol:**
> En esta función podrás configurar los roles que podrán abrir ticket en un panel en específico, es decir; si configuras el rol @boosters, esto quiere decir que solo los que tiene este rol podrán abrir ticket en el panel que se configuró el rol, a los demás que intenten abrir ticket y no tengan el rol o les permitidos les arrojará error de que el panel tiene restricción por rol y que no cuenta con el rol o roles especificados

> Se puede configurar 3 roles como máximo para cada panel

**🎫 | Limite de tickets:**
> Esto tiene con función limitar la cantidad de tickets abiertos que un usuario puede tener a la misma vez.

> Si colocas que el limite es de 2, quiere decir que los usuarios podrán abrir un máximo de 2 tickets, no más.

> Puedes colocar un limite global, esto quiere decir que tiene en cuenta los tickets abiertos de todos los paneles, si está configurado para solo 3 tickets globalmente y el usuario tiene abierto 1 ticket en 3 paneles diferentes, al intentar abrir otro no le dejará.

> También puedes colocar un limite por panel, esto quiere decir que tiene en cuenta los tickets abiertos en un solo panel, si esta configurado para solo 1 ticket por panel y el usuario intenta abrir un ticket en el panel de "Soporte(obviamente el nombre depende de como los configures)" teniendo uno ya abierto, no le dejará abrir otro más, pero si le permitirá abrir ticket en otro panel que no tenga abierto.

> Ahora también puedes colocar un limite global del sistema, este limite tiene encuenta todos los tickets actualmente abiertos en el sistema de tickets, si lo configuras oara solo 10, solo podrán haber 10 tickets abiertos como máximo.

> **Si lo que deseas es desactivar alguno de estos 2 sistemas, solo coloca el número __"0"__**

**🪪 | Nombre de los tickets**
> Con esta función podrás elegir con que nombre quieres que se creen los canales de los tickets. Está función cuenta con 4 palabras claves para personalizar a un más este apartado 😎.

> **{emoji-panel}** para que se muestre el emoji del panel (Ejemplo: 🆘)
**{name-panel}** para que se muestre el nombre del panel (Ejemplo: Soporte)
**{name-user}** para que se muestre el nombre del usuario que abrió el ticket (Ejemplo: Tico#)
**{numero-ticket}** para mostrar el número del ticket (Ejemplo: si hay 3 tickets y se abre uno más se mostrará el número 4)
  
> **__Ejemplos de uso:__**

> - **{emoji-panel}-{name-user}**
> - **Resultado:** 🆘-Tico#

> - Ticket-**{numero-ticket}**
> - **Resultado:** Ticket-6

> - Ticket de **{name-panel}**
> - **Resultado:** Ticket-de-Soporte]

**🔒 | ¿Quienes podrán cerrar los tickets?:**
> Con esta función podrás configurar quienes tendrán permitido cerrar y eliminar los tickets, puedes configurar si solo el staff o todos. Si configuras que todos, el staff y el dueño del ticket podrán cerralo y eliminarlo

** ⌨️ | Usar botones o menú:**
> Con esta nueva función podrás configurar si usar botones o menú para tu sistema de tickets.

> Puedes configurar esto individualmente para cada uno de los 2 sistemas de tickets

**✅ | Agregar panel**
> Está función es para agregar un nuevo panel a tus tickets tipo "Soporte, Alianza, Compras, etc..." con un máximo de 5 paneles, cada panel también es personalizable 😎. Al crear un nuevo panel se te pedirá indicar a que sistema de tickets quieres agregarlo, si al **ticket-1** o **ticket-2**.

> Para editar cada panel solo usa el comando para configurar los tickets y en el menú te saldrá los paneles que tienes creados, solo seleccionas el que deseas editar y sigues las instruciones

**⛔ | Eliminar panel:**
> Con está función función podrás borrar el panel que deseas, solo debes de seleccionar está opción e indicar el nombre del panel

**📋 | Canal de logs (registros):**
> Al activar está función automáticamente se enviará el registro de los tickets en canal especificado. Se enviará cuando un ticket es abierto, cerrado, reclamado, se retirar la reclamación, se valora la atención recibida y/o se reabre un ticket.

> De igual manera podrás configurar un canal de transcripciones, el cuál será el canal donde se enviarán los tickets cuando Sean eliminados junto con la transcripción del mismo.

> También se enviará un MD al dueño del ticket cuando su ticket fué cerrado (solo sí tiene los MD habilitados)


**IMPORTANTE:** 
> Recuerda que por cualquier modificación pierdes el derecho de recibir soporte
