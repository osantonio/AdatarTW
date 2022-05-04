<template>
    <div>
        <nav class="flex flex-row items-center justify-between px-5 h-12 bg-gray-50">
            <div class="hidden md:">
                    <menulogo />
                </div>
            <div class="flex flex-row quicksand text-lg">
                <h1>Logo</h1>
            </div>

            <div class="quicksand text-white flex justify-center text-center text-gray-600 text-xs">
                <ul class="px-2">hombre</ul>
                <ul class="px-2">mujer</ul>
                <ul class="px-2">cosas</ul>
                <ul class="px-2">tienda</ul>
                <ul class="px-2 text-red-600">sale</ul>
            </div>

            <div class="flex flex-row">
                <div class="px-2">
                    <account />
                </div>
                <div class="px-2">
                    <search />
                </div>
                <div class="px-2">
                    <bag />
                </div>           
                
            </div>
        </nav>
    </div>
</template>

<style>
.quicksand{
    font-family: 'Quicksand', sans-serif;
}
</style>