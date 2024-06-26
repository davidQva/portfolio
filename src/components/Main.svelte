<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "Java 2d Puzzle",
            icon: "fa-solid fa-puzzle-piece",
            description:
                "A Project in AOOP Advanced Object Oriented Programming course. The game is developed in Java and is a tile based puzzle game. We managed to cranck in 5 desginpatterns MVC, Observer, Strategy, Prototype and Memento Pattern Overengineering at its finsets, this gave us a solid 5! and One of the best reports from the course.",
        },
        {
            name: "OpenCV and Robotarm",
            icon: "fa-solid fa-video",
            description:
                "Augment your datasets with our filters and dataset manipulations to ensure your models are trained on the highest quality datasets (coming soon).",
        },
        {
            name: "GreenHouse Project",
            icon: "fa-solid fa-cloud-sun",
            description:
                "Test for model robustness with customized test profiles and receive exhaustive reporting on the performance and potential vulnerabilities of your model.",
        },
        {
            name: "Event Stream Monitor",
            icon: "fa-solid fa-pie-chart",
            description:
                "Test for model robustness with customized test profiles and receive exhaustive reporting on the performance and potential vulnerabilities of your model.",
        },
    ];

    let benefits = [
        {
            metric: "10x",
            name: "Innovative Problem Solver",
            description:
                "With a strong background in Computer Science, I excel at developing and implementing effective solutions. My expertise in tackling complex challenges ensures that projects are both innovative and reliable.",
        },
        {
            name: "Meticulous Implementer",
            description:
                "My goal is to translat ideas into tangible results. My attention to detail and efficiency ensure high-quality outcomes, consistently delivering projects on time and to the highest standards.",
        },
        {
            name: "Collaborative Team Player",
            description:
                "I foster a collaborative atmosphere where diverse perspectives thrive. My ability to coordinate efforts, facilitate discussions, and promote cohesion makes me a valuable addition to any organization seeking a dynamic team player dedicated to mutual success.",
        },
    ];
</script>

<main class="flex flex-col flex-1 p-4">
    <section
        id="introPage"
        class="grid grid-cols-1 lg:grid-cols-2 gap-12 py-8 sm:py-14"
    >
        <div
            class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
        >
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Hi! I'm <span class="poppins text-violet-400">David</span>
                Qvarnström <br />Computer scientist <br />
                <span class="poppins text-violet-400">software engineer</span>
            </h2>
            <p class="text-base sm:text-lg md:text-xl">
                My <span class="text-violet-400">favorite tech</span> includes Java
                Javascript Python Node.js Sveltekit CSS C C++ PostgreSQL ClickHouse
            </p>
            <a href="#contact">
                <button
                    class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
                >
                    <div
                        class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                    />
                    <h4 class="relative z-9">Get in touch &rarr;</h4>
                </button></a
            >
        </div>
        <div class="relative grid place-items-center">
            <img
                class="relative object-cover z-[2] max-h-[90vh]"
                src={"/images/IMG_3184.png"}
                alt="Profile image"
            />
        </div>
    </section>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-large sm:text-xl md:text-2xl">
                A few of my creative endeavors.
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                Curious to <span class="poppins text-violet-400">see</span> my projects?
            </h3>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-10">
            <a href="https://github.com/davidQva/aoop-project" target="_blank">
                <Step step={steps[0]}>
                    <p>
                        A Project in AOOP(Advanced Object Oriented Programming)
                        course. The game is developed in Java and is a tile
                        based puzzle game. We managed to cranck in 5
                        desginpatterns <strong class="text-violet-400"
                            >MVC, Observer, Strategy, Prototype and Memento
                            Pattern</strong
                        > Overengineering at its finsets, this gave us a solid 5!
                        and "One of the best reports" from the course.
                    </p>
                </Step>
            </a>
            <Step step={steps[1]}>
                <p>
                    Using a camera and a robot arm connected to a Raspberry Pi
                    to sort cubes from a conveyor belt. Leveraging <strong
                        class="text-violet-400"
                        >Python, OpenCV and Dobot
                    </strong>, we create an integrated system capable of taking
                    orders from a website and automatically collecting the cubes
                    from the belt.
                </p></Step
            >
            <Step step={steps[2]}>
                <p>
                    A system to monitor and control greenhouse temperature.
                    Created with IAR IDE and coded in <strong
                        class="text-violet-400"
                        >C
                    </strong>, the software logs temperature every minute,
                    manages light exposure, and provides real-time alerts. It
                    uses linked lists for data management and includes a fast
                    mode for testing. The LCD user interface, navigated via a
                    numeric keypad, allows users to configure settings and view
                    logged data.
                </p>
            </Step>
            <Step step={steps[3]}>
                <p>
                    Bachelor's thesis project involves a module for streaming
                    data from an event-driven system to a <strong
                        class="text-violet-400">ClickHouse database</strong
                    >. It's tailored for integration with the
                    <strong class="text-violet-400">SvelteKit </strong>
                    framework, featuring a
                    <strong class="text-violet-400">Node.js </strong>
                    backend and a SvelteKit frontend with
                    <strong class="text-violet-400"
                        >Javascript and CSS
                    </strong>.
                    <strong> Currently under development. </strong>
                </p>
            </Step>
        </div>
    </section>
    <section
        id="about"
        class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
    >
        <div
            class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
        >
            <h6 class="text-large sm:text-xl md:text-2xl">
                Want to know more?
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                A bit <span class="poppins text-violet-400">about</span> me.
            </h3>
        </div>
        <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
            I am a. . .
        </p>
        <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
            {#each benefits as benefit, index}
                <div class="flex gap-6 sm:gap-8">
                    <p
                        class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                    >
                        0{index + 1}
                    </p>
                    <div class="flex flex-col gap-6 sm:gap-8">
                        <h3 class="text-2xl sm:text-3xl md:text-5xl">
                            {benefit.name}
                        </h3>
                        <p>{benefit.description}</p>
                    </div>
                </div>
            {/each}
        </div>
        <h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
            The <span class="text-violet-400">Formaly Educated</span> Solutionist
        </h5>
    </section>
</main>
