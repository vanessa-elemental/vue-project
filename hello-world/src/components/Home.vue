<template>
<div class="min-h-screen flex py-12 px-4 sm:px-6 lg:px-8">
  <div class="max-w-md w-full space-y-8 px-5">
    <div>
      <h2 class="text-center text-3xl font-extrabold">KALE CAPITAL</h2>
      <h2 class="mt-20 text-center text-xl font-extrabold kale-title">
        ¡Hola!
      </h2>
      <p class=" px-1 mt-2 text-center text-sm kale-title">
        Te han invitado a Kale Capital.<br> Un fondo de inversión en criptomonedas que elimina el riesgo y la volatidad de las criptomonedas. 
      </p>
    </div>
    <form class="mt-10 space-y-3" action="#" method="POST">
        <input type="hidden" name="remember" value="true">
        <div>
            <input id="email-address" name="email" type="email" autocomplete="email" required class="relative block w-full text-muted text-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:z-10 sm:text-sm" placeholder="nuno@elemental.black">
        </div>
        <div>
            <input id="password" name="password" type="password" autocomplete="current-password" required class="relative block w-full text-muted text-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:z-10 sm:text-sm" placeholder="Password">
        </div>
        <div>
            <input id="repeated-password" name="repeated-password" type="password" autocomplete="repeated-password" required class="relative block w-full text-muted text-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:z-10 sm:text-sm" placeholder="Repite tu password">
        </div>
      <div>
        <button type="submit" class="group relative w-full flex justify-center py-2 px-4 text-sm font-medium text-white hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
          Registrar
        </button>
      </div>


    </form>

    <div>
        <h2 class="text-center font-medium font-extrabold kale-title">
        Ya tengo cuenta
        </h2>
    </div>

  </div>
</div>
</template>

<script>
export default {
  name: 'Home', 
  props: {
    msg: String
  }
}
</script>



<style scoped>
    .kale-title {
        color: #617D8A;
    }

    .kale-register-input::before {
        background: 
    }
</style>