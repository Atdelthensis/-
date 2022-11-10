<template>
    <div>
        <div class="">
        <h1><button class="mr-2 mt-1 px-4 py-2 font-semibold text-sm bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500 text-white rounded-md shadow-sm ease-in-out duration-150">
                <router-link to="/">Home</router-link></button>
                <button class="mt-1 px-4 py-2 font-semibold text-sm bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500 text-white rounded-md shadow-sm ease-in-out duration-150">
                <router-link to="/Profile"> Profile</router-link></button>
            </h1>
        </div>
        <div>
            <slot></slot>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<Style>

</Style>