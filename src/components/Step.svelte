<script>
    export let step;
</script>

<a
    href={step.href}
    target="_blank"
    class="p-6 sm:p-8 md:p-10 flex flex-col gap-4 rounded-lg border border-solid border-yellow-500 text-center cursor-pointer group hover:border-yellow-600 duration-200 mx-auto w-full max-w-lg"
>
    <div class="bg-slate-950 flex justify-center items-center px-6 text-6xl md:text-7xl -mt-10 sm:-mt-12 md:-mt-14 lg:-mt-16 mx-auto duration-200" style="height: 100px;"> 
        <!-- Added height to ensure grid appears centered -->
      
    </div>
    <h3 class="font-medium text-2xl sm:text-3xl md:text-4xl"> <!-- Increased text size -->
        {step.name}
    </h3>
    <slot />
    <div class="flex-1 flex justify-between gap-4 items-end">
        <div
            class="ml-auto cursor-pointer hover:text-slate-950 duration-200 relative after:absolute after:top-0 after:h-0 after:right-full after:bg-white after:w-full after:h-full after:duration-200 hover:after:translate-x-full after:z-[-1] overflow-hidden"
        >
          
        </div>
    </div>
</a>
