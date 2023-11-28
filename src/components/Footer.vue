<template>
    <footer class="bg-gray-500 w-screen h-1/5 fixed bottom-0 shadow dark:bg-gray-800">
    <div class="w-full mx-auto max-w-screen-xl p-4 md:flex md:items-center md:justify-between">
        <div class="grid-cols-6 grid gap-14">
            <div class="entity hover:bg-gray-700" onclick="clickEntity()"/>
            <div class="relation hover:bg-gray-700"/>
            <div class="relation-line hover:bg-gray-700"/>
        </div>
    </div>
</footer>
</template>

<style scoped>
    .entity {
        width: 100px;
        height: 50px;
        border: 2px solid black;

    }

    .relation {
        width: 75px;
        height: 75px;
        transform: rotate(135deg) skew(20deg, 20deg);
        border: 2px solid black;
    }

    .relation-line {
        width: 50px;
        height: 1px;
        border: 2px solid black;
    }
</style>