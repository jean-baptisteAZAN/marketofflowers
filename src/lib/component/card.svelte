<script>
    export let img = '';
    export let title = '';
    export let description = '';
</script>

<div class="mb-4 h-[43rem] border-solid border-2 rounded-xl w-[90%] flex flex-col items-center  transition-all hover:bg-[#F0F0F0] border-[#F0F0F0] hover:scale-105  duration-600">
    <div class="h-[50%] w-full ">
        <img src="{img}" class="object-cover w-full rounded-xl h-[100%]" alt="each images here is related to the description"/>
    </div>
    <div class="px-8 h-[50%] flex flex-col items-center justify-center">
        <h5 class="text-center mt-3 mb-2 text-xl font-bold tracking-tight text-gray-900 dark:text-white font-roboto px-10 ">{title}</h5>
        <p class="text-center mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight font-roboto px-10">{@html description}</p>
    </div>
</div>
