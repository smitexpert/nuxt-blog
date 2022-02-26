<template>
    <div class="flex flex-wrap w-full bg-white p-8">
        <div class="w-1/3">
            <h4 class="text-2xl font-bold">Contact Me</h4>
            <div class="mt-8">
                <span class="font-light mr-4 text-sm">EMAIL:</span><span class="uppercase font-bold text-sm"><a href="#">smitexpert@gmail.com</a></span>
            </div>
            <div class="mt-8">
                <span class="font-light mr-4 text-sm">PHONE:</span><span class="uppercase font-bold text-sm"><a href="#">+880 199 4387 497</a></span>
            </div>
        </div>
        <div class="w-2/3">
            <h4 class="text-2xl font-bold">Get in touch</h4>
            <div class="mt-8">
                <p class="font-light">Don’t be shy to ask me a question.</p>
                <div class="w-full flex flex-wrap">
                    <div class="w-1/2 mt-4 px-2">
                        <input class="focus:outline-none text-sm font-light pb-2 border-b border-black w-full" placeholder="Name" />
                    </div>
                    <div class="w-1/2 mt-4 px-2">
                        <input class="focus:outline-none text-sm font-light pb-2 border-b border-black w-full" placeholder="Name" />
                    </div>
                </div>
                <div class="w-full flex flex-wrap">
                    <div class="w-full mt-4 px-2">
                        <textarea class="focus:outline-none text-sm font-light pb-2 border-b border-black w-full" placeholder="Question" rows="10"></textarea>
                    </div>
                </div>
                
                <div class="w-full flex flex-wrap">
                    <div class="w-full mt-4 px-2">
                        <button class="px-6 py-2 text-sm rounded-full text-gray-800 border border-black bg-white hover:bg-black hover:text-white">Send</button>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>