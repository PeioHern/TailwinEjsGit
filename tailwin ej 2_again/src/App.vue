<script setup>

</script>

<template>
    <div class="flex flex-row">

        <!-- img  -->
        <div>
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c5/Big_buck_bunny_poster_big.jpg"
                alt="alt poster" class="h-[900px] w-[900px]" />
        </div>


        <!-- un form  -->
        <div class="bg-blue-200 px-20 py-20">
            <form action="" class="flex flex-col">

                <h2 class="font-bold">Big Buck Bunny</h2>

                <h1 class="font-bold mt-10 mb-5 text-xl">Sartu zure kontuan</h1>

                <div class="flex flex-col space-y-5">
                    <div class="flex flex-col">
                        <label class="text-sm text-gray-500">Posta elektroniko helbidea</label>
                        <input type="text" placeholder="Enter Email Address" class="bg-gray-200 py-2 px-2 rounded-md">
                    </div>

                    <div class="flex flex-col">
                        <label for="" class="text-sm text-gray-500">Pasahitza</label>
                        <input type="text" placeholder="Enter Password" class="bg-gray-200 py-2 px-2 rounded-md">
                    </div>
                </div>
                <a class="text-sm text-right font-semibold">Pasahitza ahaztu duzu?</a>

                <button class="bg-blue-500 text-white py-2 mt-5 rounded-md">Sartu</button>

                <p class="font-semibold mt-10">Ez duzu konturik? <a href="" class="text-blue-700">Sortu kontu bat</a></p>

                <p class="mt-10 text-gray-500 text-sm">2023 Iker Lardajuela</p>

            </form>
        </div>




    </div>

</template>
