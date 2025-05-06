# Parcial-II
para el POST del usuario http://localhost:3000/usuario (Aquí se prueba la información del usuario)

{ "nombre": "David Martinez", "credito": 135, "costoEnvio": 4.5, "enviosDisponibles": 30 } //Body en el thunder

para el GET del usuario http://localhost:3000/usuario/6819270264a8a86fabb3e81c/creditos // para ver cuantos creditos tiene el cliente ingresado

para el POST http://localhost:3000/envios // para ingresar el envío

{ "usuarioId": "6819270264a8a86fabb3e81c", // en esa iD se toma la que se da en el post del usuario "nombre": "David Martinez", "direccion": "Ciudad pacifica", "telefono": "60575497", "referencia": "Frente al colegio ceceess", "observacion": "Frágil", "producto": { "descripcion": "Laptop Gamer", "peso": 2.5, "bultos": 1, "fecha_entrega": "2025-05-10" } } //Body en el thunder

para el GET de envíos http://localhost:3000/envios/681928cc64a8a86fabb3e82e // --- envíos/ID, depende de la ID

para el DELETE de envíos http://localhost:3000/envios/ID //La id depende de la que de en el post ejemplo : "681928cc64a8a86fabb3e82e" esta me dio a mi, puede probar con esa le deberia de funcionar. El retraso es para eliminar los envíos y hacer reembolsos al usuario.
