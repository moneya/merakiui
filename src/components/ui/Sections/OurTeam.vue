<template>
    <view-component :name="name" :code="code">
        <div class="py-6" slot="component">
            <section class="bg-white container mx-auto p-6">
                <h2 class="text-gray-800 font-medium capitalize text-xl md:text-2xl">Our Team</h2>

                <div class="flex items-center justify-center">
                    <div class="grid gap-8 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 mt-8">
                        <div class="max-w-xs w-full text-center">
                            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1493863641943-9b68992a8d07?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=739&q=80" alt="avatar"/>

                            <div class="mt-2">
                                <h3 class="text-lg font-medium text-gray-700">Ahmed Omer</h3>
                                <span class="mt-1 font-medium text-gray-600">CEO</span>
                            </div>
                        </div>

                        <div class="max-w-xs w-full text-center">
                            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1516756587022-7891ad56a8cd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80" alt="avatar"/>

                            <div class="mt-2">
                                <h3 class="text-lg font-medium text-gray-700">Jane Doe</h3>
                                <span class="mt-1 font-medium text-gray-600">Co-founder</span>
                            </div>
                        </div>

                        <div class="max-w-xs w-full text-center">
                            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1492562080023-ab3db95bfbce?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=731&q=80" alt="avatar"/>

                            <div class="mt-2">
                                <h3 class="text-lg font-medium text-gray-700">Steve Ben</h3>
                                <span class="mt-1 font-medium text-gray-600">UI/UX</span>
                            </div>
                        </div>

                        <div class="max-w-xs w-full text-center">
                            <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80" alt="avatar"/>

                            <div class="mt-2">
                                <h3 class="text-lg font-medium text-gray-700">Patterson Johnson</h3>
                                <span class="mt-1 font-medium text-gray-600">Software Engineer</span>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </view-component>
</template>

<script>
    export default {
        data() {
            return {
                name: 'Our Team',
                code: `
        <section class="bg-white container mx-auto p-6">
            <h2 class="text-gray-800 font-medium capitalize text-xl md:text-2xl">Our Team</h2>

            <div class="flex items-center justify-center">
                <div class="grid gap-8 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 mt-8">
                    <div class="max-w-xs w-full text-center">
                        <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1493863641943-9b68992a8d07?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=739&q=80" alt="avatar"/>

                        <div class="mt-2">
                            <h3 class="text-lg font-medium text-gray-700">Ahmed Omer</h3>
                            <span class="mt-1 font-medium text-gray-600">CEO</span>
                        </div>
                    </div>

                    <div class="max-w-xs w-full text-center">
                        <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1516756587022-7891ad56a8cd?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80" alt="avatar"/>

                        <div class="mt-2">
                            <h3 class="text-lg font-medium text-gray-700">Jane Doe</h3>
                            <span class="mt-1 font-medium text-gray-600">Co-founder</span>
                        </div>
                    </div>

                    <div class="max-w-xs w-full text-center">
                        <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1492562080023-ab3db95bfbce?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=731&q=80" alt="avatar"/>

                        <div class="mt-2">
                            <h3 class="text-lg font-medium text-gray-700">Steve Ben</h3>
                            <span class="mt-1 font-medium text-gray-600">UI/UX</span>
                        </div>
                    </div>

                    <div class="max-w-xs w-full text-center">
                        <img class="h-48 w-full object-cover object-center mx-auto rounded-lg" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80" alt="avatar"/>

                        <div class="mt-2">
                            <h3 class="text-lg font-medium text-gray-700">Patterson Johnson</h3>
                            <span class="mt-1 font-medium text-gray-600">Software Engineer</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>`
            }
        }
    }
</script>