<template>
    <view-component :name="name" :code="code">
        <div class="px-3 py-6" slot="component">
            <div class="max-w-xs mx-auto bg-white shadow-lg rounded-lg overflow-hidden">
                <div class="px-4 py-2">
                    <h1 class="text-gray-900 font-bold text-3xl uppercase">NIKE AIR</h1>
                    <p class="text-gray-600 text-sm mt-1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi quos quidem sequi illum facere recusandae voluptatibus</p>
                </div>

                <img class="h-48 w-full object-cover mt-2" src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=320&q=80" alt="NIKE AIR">

                <div class="flex items-center justify-between px-4 py-2 bg-gray-900">
                    <h1 class="text-white font-bold text-lg">$129</h1>
                    <button class="px-2 py-1 bg-white text-xs text-gray-900 font-semibold rounded uppercase hover:bg-gray-200 focus:bg-gray-400">Add to cart</button>
                </div>
            </div>
        </div>
    </view-component>
</template>

<script>
    export default {
        data() {
            return {
                name: 'Product',
                code: `
        <div class="max-w-xs mx-auto bg-white shadow-lg rounded-lg overflow-hidden">
            <div class="px-4 py-2">
                <h1 class="text-gray-900 font-bold text-3xl uppercase">NIKE AIR</h1>
                <p class="text-gray-600 text-sm mt-1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi quos quidem sequi illum facere recusandae voluptatibus</p>
            </div>

            <img class="h-48 w-full object-cover mt-2" src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=320&q=80" alt="NIKE AIR">

            <div class="flex items-center justify-between px-4 py-2 bg-gray-900">
                <h1 class="text-white font-bold text-lg">$129</h1>
                <button class="px-2 py-1 bg-white text-xs text-gray-900 font-semibold rounded uppercase hover:bg-gray-200 focus:bg-gray-400">Add to cart</button>
            </div>
        </div>`,
            }
        }
    }
</script>
