<template>
    <view-component :name="name" :code="code">
        <div class="px-3 py-8 flex items-center justify-center" slot="component">
            <button class="flex items-center py-2 px-4 capitalize tracking-wide bg-gray-800 text-white font-medium rounded hover:bg-gray-700 focus:outline-none focus:bg-gray-700">
                Primary
            </button>
        </div>
    </view-component>
</template>

<script>
    export default {
        data() {
            return {
                name: 'Primary',
                code: `
        <button class="flex items-center py-2 px-4 capitalize tracking-wide bg-gray-800 text-white font-medium rounded hover:bg-gray-700 focus:outline-none focus:bg-gray-700">
            Primary
        </button>`
            }
        }
    }
</script>
