<script >
</script>
<template>
<div class="d-flex justify-content-center align-items-center vh-100">
  <div class="w-50 p-4 border rounded shadow">
    <div class="mb-3">
      <label for="nombre" class="form-label">Nombre y Apellido</label>
      <input type="text" class="form-control" id="nombre" placeholder="Ingrese tu nombre y apellido completo">
    </div>
    <div class="mb-3">
      <label for="email" class="form-label">Email</label>
      <input type="email" class="form-control" id="email" placeholder="Ingrese tu correo electrónico">
    </div>
    <div class="mb-3">
      <label for="motivo" class="form-label">¿Por qué quieres trabajar en BMW?</label>
      <textarea class="form-control" id="motivo" rows="3"></textarea>
    </div>
    <button type="submit" class="btn btn-primary w-100">Enviar formulario</button>
  </div>
</div>

</template>
<style>
.form-label {
  color: rgb(126, 79, 126);
  font-size: 1.2em;
  font-weight: bold;
}
</style>