<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">Dashboard</h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white dark:bg-gray-800 overflow-hidden shadow-sm sm:rounded-lg">
                    <div class="p-6 text-gray-900 dark:text-gray-100">You're logged in!</div><br> 
                    <div class="materia1">
                        <h2>INGLES</h2>
                        <p>En un mundo cada vez más globalizado, hablar inglés es más que una capacidad para mejorar el currículum o una ventaja competitiva adicional: es una necesidad para poder comunicarse y acceder al mercado laboral. Al mismo tiempo, abre las puertas a más experiencias, por ejemplo, de tipo cultural.</p>
                        <br>
                        <a href="https://cdn.memegenerator.es/imagenes/memes/full/12/13/12137427.jpg"> <button>Inscribirme</button></a>
                    </div>
                    <div class="materia2">
                        <h2>MATEMATICAS</h2>
                        <p>¿Qué son las matematicas?
Las matemáticas se pueden definir como “la ciencia que estudia las relaciones entre cantidades, magnitudes y propiedades, y las operaciones lógicas mediante las cuales se pueden deducir cantidades, magnitudes y propiedades desconocidas”</p>
                        <br>
                       <a href="https://cdn.memegenerator.es/imagenes/memes/full/12/13/12137427.jpg"> <button>Inscribirme</button></a>
                    </div>
                    <div class="materia3">
                        <h2>PROGRAMACION</h2>
                        <p>La programación es la actividad que se enfoca en organizar un conjunto de datos ordenados a seguir para ser ciertas cosas, esta definición puede utilizarse en muchos contextos. Pero en el área de informática la programación es fundamental para la relación entre ordenadores y los usuarios</p>
                        <br>
                        <a href="https://cdn.memegenerator.es/imagenes/memes/full/12/13/12137427.jpg"> <button>Inscribirme</button></a>
                    </div>
                     <br><br>
                     
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
