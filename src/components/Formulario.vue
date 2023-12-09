<script setup>

</script>

<template>
    <div class="md:w-1/2">
        <h2 class="font-black text-3xl text-center">Seguimiento de pacientes</h2>

        <p class="text-lg mt-5 text-center mb-10">
            Añade pacientes y
            <span class="text-indigo-600 font-bold">gestiónalos</span>
        </p>

        <form action="" class="bg-white shadow-md rounded-lg py-10 px-5 mb-10">
            <div class="mb-5">
                <label for="mascota" class="block text-gray-700 font-bold">
                    Nombre de la mascota
                </label>
                <input type="text" id="mascota" placeholder="Ej: Canela..." class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
            </div>

            <div class="mb-5">
                <label for="propietario" class="block text-gray-700 font-bold">
                    Nombre del propietario
                </label>
                <input type="text" id="propietario" placeholder="Ej: Fabián Martínez" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
            </div>

            <div class="mb-5">
                <label for="email" class="block text-gray-700 font-bold">
                    Correo electrónico de contacto
                </label>
                <input type="email" id="email" placeholder="Ej: email@email.com" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
            </div>

            <div class="mb-5">
                <label for="alta" class="block text-gray-700 font-bold">
                    Fecha de alta
                </label>
                <input type="date" id="alta" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md">
            </div>

            <div class="mb-5">
                <label for="sintomas" class="block text-gray-700 font-bold">
                    Síntomas de la mascota
                </label>
                <textarea id="sintomas" placeholder="Describe los síntomas de la mascota" class="border-2 w-full p-2 mt-2 placeholder-gray-400 rounded-md h-40"/>
            </div>
            <input type="submit" name="" id="" class="bg-indigo-600 w-full p-3 text-white font-bold hover:bg-indigo-500 cursor-pointer transition-colors" value="Registar paciente">
        </form>
    </div>
</template>