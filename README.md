# Tickets-TicoV2

**📖 | Información**
> Acá tienes la información sobre este sistema
**🗣️ | Palabras clave:**
Este sistema cuenta con 3 Palabras claves, las cual son: **{tagg-user}, {tagg-rol} y {razon}**. ¿Para que sirven y donde se pueden usar?

> Estas palabras claves sirven para poder etiquetar al usuario que abre el ticket **{tagg-user}**, para poder etiquetar al rol de staff **{tagg-rol}** y para colocar la razón por la cual fué abierto el ticket **{razon}** en cualquier parte de tu mensaje de bienvenida, estan creadas para darle una mejor estetica a tus tickets 😎.

> Estas palabras claves solo funcionan en los mensajes de bienvenida de los tickets y en la parte de "Titulo y Descripción"

**__Ejemplos de uso:__**

> - Bienvenido al ticket **{tagg-user}**
> - **Resultado:** Bienvenido al ticket @Tico#

> - **{tagg-rol}**, atiende de buena manera
> - **Resultado:** @RolStaff, atiende de buena manera

> - Razón del ticket: **{razon}**
> - **Resultado:** Razón del ticket: Necesito ayuda

**❌ | Bloquear-desbloquear usuarios:**
> Con esta función podrás bloquear a usuarios para que no puedan abrir tickets. Para esos usuarios que mal usan los tickets

**🛠️ | Rol staff:**
> Con esta función indicarás cual es el rol de staff, el cual podrá ver los tickets, atender, cerrar y/o bloquear usuarios del sistema de tickets. Puedes configurar hasta 10 roles de staff

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
> - **Resultado:** 🆘-$displayName[$authorID]

> - Ticket-**{numero-ticket}**
> - **Resultado:** Ticket-6

> - Ticket de **{name-panel}**
> - **Resultado:** Ticket-de-Soporte]

**✅ | Agregar panel**
> Está función es para agregar un nuevo panel a tus tickets tipo "Soporte, Alianza, Compras, etc..." con un máximo de 5 paneles, cada panel también es personalizable 😎. Al crear un nuevo panel se te pedirá indicar a que sistema de tickets quieres agregarlo, si al **ticket-1** o **ticket-2**.

> Para editar cada panel solo usa el comando para configurar los tickets y en el menú te saldrá los paneles que tienes creados, solo seleccionas el que deseas editar y sigues las instruciones

**⛔ | Eliminar panel:**
> Con está función función podrás borrar el panel que deseas, solo debes de seleccionar está opción e indicar el nombre del panel]
$addField[📋 | Canal de logs (registros);
Al activar está función automáticamente se enviará el registro de los tickets en canal especificado. Se enviará cuando un ticket es abierto, cerrado, reclamado, se retirar la reclamación, se valora la atención recibida y/o se reabre un ticket. 

De igual manera podrás configurar un canal de transcripciones, el cuál será el canal donde se enviarán los tickets cuando Sean eliminados junto con la transcripción del mismo.

También se enviará un MD al dueño del ticket cuando su ticket fué cerrado (solo sí tiene los MD habilitados)]
$footer[Tickets Tico v2]
$footerIcon[$serverIcon]
$color[6e00ff]
