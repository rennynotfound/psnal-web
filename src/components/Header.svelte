<script>
    export let y;   
    let tabs = [
        {name: 'renLin();', link: '#home', scrollY: 0},
        {name: 'about', link: '#about', scrollY: 320},
        {name: 'projects', link: '#projects', scrollY: 1000},
        {name: 'research', link: '#research', scrollY: 2000},
    ];

    function refreshPage() {
        location.reload();
    }

    function scrollToPosition(scrollY) {
        window.scrollTo({
            top: scrollY,
            behavior: 'smooth'
        });
    }
</script>

<header class={'z-[10] top-0 duration-200 px-6 flex items-center justify-between border border-solid' + (y > 0 ? ' py-4 bg-neutral-900 border-transparent' : ' py-6 bg-transparent border-transparent')}>
    <!-- Left-aligned renLin(); with refresh functionality -->
    <div class="flex items-center">
        <a href={tabs[0].link} class="flex items-center" on:click|preventDefault={refreshPage}>
            <p class="py-2 px-4 text-lg font-bold rounded-lg text-green-400 bg-transparent hover:text-green-300 transition duration-200 tracking-wide">
                {tabs[0].name}
            </p>
        </a>
    </div>
    
    <!-- Center-aligned tabs with customizable scroll distances -->
    <div class="flex items-center gap-4 mx-auto">
        {#each tabs.slice(1) as tab}
            <a href={tab.link} class="flex items-center" on:click|preventDefault={() => scrollToPosition(tab.scrollY)}>
                <p class="py-2 px-4 text-lg rounded-lg bg-neutral-800 text-white hover:text-green-300 transition duration-200">
                    {tab.name}
                </p>
            </a>
        {/each}
    </div>

    <!-- Right-aligned placeholder for centering -->
    <div class="flex items-center invisible">
        <p class="py-2 px-4 text-lg font-bold rounded-lg tracking-wide">
            {tabs[0].name}
        </p>
    </div>
</header>
