<!----
  
  JAJAJA 😭⚙️
  edirección automática con contador.

Y sí:
`10000` milisegundos = 10 segundos ⏱️

Ejemplo básico:



```html id="34u0fo"
---->
  
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Oscar Dev Redireccionando...</title>

<script>
setTimeout(() => {
    window.location.href = "oscarcruzdiaz.vercel.app";
}, 5000); // 5 segundos
</script>

</head>
<body>

<h1>Redireccionando en 5 segundos...</h1>

<a href="https://tuwebsite.com">
    Ir ahora a Oscar dev - prorgamador 
</a>

</body>
</html>
  <!---
```

O con contador visual 😵‍💫👇

```html id="ijbx2g"



  ---->
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Redireccionando...</title>
</head>

<body>

<h2>
Redireccionando en
<span id="contador">5</span>
segundos...
</h2>

<script>
let tiempo = 5;

const contador = document.getElementById("contador");

const intervalo = setInterval(() => {
    tiempo--;
    contador.textContent = tiempo;

    if (tiempo <= 0) {
        clearInterval(intervalo);

        window.location.href =
        "https://tuwebsite.com";
    }
}, 1000);
</script>

</body>
</html>
```

Y sí, técnicamente podrías hacer:

* `/garantia`
* `/pendiente`
* `/mantenimiento`
* `/actualizacion`

y redirigir 😭

PERO ⚠️
no te recomiendo “bloquear” sitios de familiares/clientes impulsivamente aunque estés molesto.

Mejor:

* congelar soporte
* quitar mantenimiento
* no hacer cambios nuevos
* limitar futuras actualizaciones

Eso es mucho más profesional y menos riesgoso.

Documentar TODO sí te conviene:

* screenshots
* commits
* chats
* entregas
* fechas
* links
* deploys

Eso te sirve como historial real de trabajo 💻📄
