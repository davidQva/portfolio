<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "Java 2d Puzzle",
            icon: "fa-solid fa-puzzle-piece",
            description:
                "Smoljames Store is a a merchanising store created with Next.js, Commerce.js & Stripe! Commerce.js is a CMS for managing project and Stripe is used for all transaction handling.",
        },
        {
            name: "Event-Stream Analyzer",
            icon: "fa-solid fa-chart-pie",
            description:
                "Augment your datasets with our filters and dataset manipulations to ensure your models are trained on the highest quality datasets (coming soon).",
        },
        {
            name: "GreenHouse Project",
            icon: "fa-solid fa-cloud-sun",
            description:
                "Test for model robustness with customized test profiles and receive exhaustive reporting on the performance and potential vulnerabilities of your model.",
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
            <button
                class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
            >
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                />
                <h4 class="relative z-9">Get in touch &rarr;</h4>
            </button>
        </div>
        <div class="relative grid place-items-center">
            <img
                class="relative object-cover z-[2] max-h-[30vh]"
                src={"/images/profile.png"}
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

        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
            <Step step={steps[0]}>
                <p>
                    A Project in AOOP(Advanced Object Oriented Programming)
                    course. The game is developed in Java and is a tile based
                    puzzle game. We managed to cranck in 5 desginpatterns <strong
                        class="text-violet-400"
                        >MVC, Observer, Strategy, Prototype and Memento Pattern</strong
                    > Overengineering at its finsets, this gave us a solid 5! and
                    "One of the best reports" from the course.
                </p>
            </Step>
            <Step step={steps[1]}>
                <p></p></Step
            >
            <Step step={steps[2]}>
                <p></p>
            </Step>
        </div>
    </section>
</main>
