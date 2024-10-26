<main class='flex flex-col flex-1 p-4'>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <div class="text-center">
        <h6 class="font-medium text-gray-100 text-2xl sm:text-3xl md:text-2xl mb-2">
            <br><br><br><br>Hello World,
        </h6>
    </div>

    <div class="text-center">   
        <h1 class="font-semibold text-7xl sm:text-10xl md:text-[5rem] mb-4">
            I'm <span class="poppins text-green-300">Ren</span>.
        </h1>
    </div>

    <div class="container flex justify-center items-center text-center">
        <h1><span class="auto-type text-green-300 font-medium"></span></h1>
    </div>
    

    <div class="text-center">
        <h6 class="font-medium text-gray-100 text-2xl sm:text-2xl md:text-2xl mb-2">
            <br>Welcome to my website! <span class="wave">👋🏻</span>
        </h6>
    </div>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

    <script>
        var typed = new Typed('.auto-type', {
            strings: ['Game Developer', 'Web Developer', 'AI/ML Programmer'],
            typeSpeed: 150,
            backSpeed: 170,
            loop: true,
        });
    </script>

    <div class="flex flex-col items-left text-left font-medium md:text-[3rem] text-yellow-200">
        <br><br><br><br><br>01<br />
        <div class="text-white">
            <br>About Me<span class="text-yellow-200">.</span><br /><br />
        </div>
    </div>

    <div class="box border-2 border-yellow-200 rounded-lg p-6 mb-8 w-full mx-auto">
        <p class="text-center text-white font-medium m-1 tracking-wide">
            Before starting WebDev, I learned to program in <span class="text-yellow-300">C#</span> to use Unity in middle school, as I gained an interest in making video games.
            <br /><br />Since then, I have learned how to run, develop, and maintain simple websites using <span class="text-orange-500">HTML</span> <span class="text-blue-500">CSS</span> and <span class="text-red-500">Javascript</span>. Most of my WebDev projects, including this one, are made with <span class="text-green-500">SvelteKit</span> and <span class="text-violet-500">TailwindCSS</span>
            <br /><br /> In my freshman & sophomore years, I created apps that were either useful to me or my fellow classmates. Additionally, I have joined professors from various universities to assist in research and writing <span class="text-red-300">AI/ML</span> algorithms. Learn more about them <span class="text-green-300">BELOW</span>.
        </p>
    </div>

    <div class="flex flex-col items-left text-left font-medium md:text-[3rem] text-blue-400">
        <br><br><br><br><br><br>02<br />
        <div class="text-white">
            <br>Projects<span class="text-blue-400">.</span><br /><br />
        </div>
    </div>
    
    <!-- Container for Projects -->
    <div class="flex flex-col md:flex-row md:space-x-4 space-y-4 md:space-y-0">
        <!-- Personal Website (now first) -->
        <div class="box border-4 border-gray-700 rounded-lg p-2 md:w-[30%]">
            <div class="text-center">
                <div class="bg-white rounded p-1 mx-auto mb-2">
                    <img src="https://i.ibb.co/0FV8H60/Screenshot-2024-10-25-212917.png" class="rounded">
                </div>
                <span class="text-3xl font-medium text-blue-300">Personal Website</span>
                <p class="text-gray-200 mb-2 poppins font-normal" style="letter-spacing: 1px;"> My first fully self-coded website using Javascript, HTML, and CSS!</p>
                <span class="text-blue-300   font-medium">SvelteKit, TailwindCSS</span>
            </div>
        </div>
    
        <!-- Clean It Up Project -->
        <a href="https://renqwerty.itch.io/clean-up-time" target="_blank" class="box border-4 border-gray-700 rounded-lg p-2 md:w-[30%]">
            <p class="text-center text-gray-200 font-normal m-1 tracking-wide poppins" style="letter-spacing: 1px;">
                <img src="https://img.itch.zone/aW1hZ2UvMTQxOTY3NC84MjY4MjI0LmdpZg==/original/Bi1qR7.gif" class="mx-auto mb-2 rounded">
                <span class="text-3xl font-medium text-blue-300">Clean It Up!</span>
                <br> A speedrunning game I created and published on itch.io for fun during the process of learning how to develop video games. With limited time on the clock, the player attempts to clean up all the items in the room and place them in their designated areas to win.
                <br><span class="text-blue-300 font-medium">Unity Game Engine, C#, Itch.IO</span>
                <br> <span class ="text-gray-400">click to open app!</span>
            </p>
        </a>
    
        <!-- LexCalc Project -->
        <a href="https://sites.google.com/lexingtonma.org/lexcalc" target="_blank" class="box border-4 border-gray-700 rounded-lg p-2 md:w-[30%]">
            <div class="text-center">
                <div class="bg-beige rounded p-2 mx-auto mb-2">
                    <img src="https://ibb.co/cDk4jC1"><img src="https://i.ibb.co/MMZFmGs/Screenshot-2024-02-03-10-01-05-AM-removebg-preview-1-1.png" class="rounded">
                </div>
                <span class="text-3xl font-medium text-blue-300">LexCalc</span>
                <br>
                <p class="text-gray-200 mb-2 poppins font-normal" style="letter-spacing: 1px;">
                    A simple calculator app designed specifically for students in LHS. The LHS Math Department grades math assessments on a 9-point scale, which could make it harder for students to calculate by themselves. This app takes weights and rounding into consideration when calculating students' final grades. The app has 200+ student users monthly.
                </p>
                <span class="text-blue-300 font-medium">Javascript, Google Sites</span>
                <br>
                <span class="text-gray-400">click to open app!</span>
            </div>
        </a>
    </div>
    
    <div class="flex flex-col items-left text-left font-medium md:text-[3rem] text-red-400 mb-8">  <!-- Added margin-bottom for spacing -->
        <br><br><br><br><br><br>03<br />
        <div class="text-white">
            <br>Research<span class="text-red-400">.</span><br />
        </div>
    </div>
    
    <!-- Container for Research Projects -->
    <div class="flex flex-col md:flex-row md:space-x-4 space-y-4 md:space-y-0">
        <!-- Mass General Health Project -->
        <div class="box border-4 border-gray-700 rounded-lg p-2 md:w-[30%]">
            <div class="text-center">
                <span class="text-3xl font-medium text-red-200">Mass General Health</span> 
                <br>
                <p class="text-gray-200 mb-2 poppins font-normal" style="letter-spacing: 1px;">
                    A collaborative research project working with professors and medical doctors from Harvard/UMB. Collecting real data from hospital patients and creating AI algorithms/models to predict and classify activities being performed, which then are used to quantify pain measurement in patients after surgeries to observe the results of the surgery. The final research paper will be finished and submitted to IEEE for judging during the fall of 2025.
                </p>
                <br><span class="text-red-200 font-medium">VSCode, Unity, AI Models, Accelerometers</span>
            </div>
        </div>
    
        <!-- Energy Expenditure Project -->
        <div class="box border-4 border-gray-700 rounded-lg p-2 md:w-[30%]">
            <p class="text-center text-gray-200 font-normal m-1 tracking-wide poppins" style="letter-spacing: 1px;">
                <span class="text-3xl font-medium text-red-200">Energy Expenditure</span>
                <br> A collaborative government-funded research project among many credible professors from interdisciplinary fields, such as CS and Exercise Physiology. The goal is to measure energy expenditure during physical activities in both adults and youth using activity monitors, such as gyroscopes. We will develop machine learning algorithms to classify activity types and predict energy expenditure based on data collected from gyroscope sensors worn at different locations on the body. These algorithms will have direct benefits to those examining dose-response relationships between sedentary behaviors, physical activity, and health outcomes in adults, in the physical activity and public health fields.
                <br><br><span class="text-red-200 font-medium">Gyroscopes, accelerometers, VSCode, AI Models, Transformers Models</span>
            </p>
        </div>
    </div>
    
            </main>