<script>
</script>

<section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
    <!--   <div
        class="bg-slate-950 grid place-items-center px-4 text-5xl md:text-6xl -mt-10 sm:-mt-12 md:-mt-14 lg:-mt-16 mx-auto duration-200 bg-transparent"
    >
        <i class="fa-solid fa-solid fa-person-digging" />
    </div> -->
    <h3 class="font-medium text-xl sm:text-2xl md:text-3xl"></h3>

    Metabytes, a company based in Lahlom, commissioned this project to develop
    an intuitive dashboard for visualizing business processes using event data.
    The primary goal was to create a tool that offers a clear, real-time
    overview of workflows and key metrics, helping businesses quickly identify
    process bottlenecks. The solution was powered by ClickHouse, a
    high-performance columnar database, to efficiently manage and analyze the
    event data. The frontend dashboard was built using SvelteKit, combined with
    a RESTful API to dynamically present the entire business process from start
    to finish. To ensure an optimal user experience, we employed a user-centered
    design approach, tailoring the interface to meet specific user needs. The
    prototype successfully met all initial requirements and received an
    impressive System Usability Scale (SUS) score of 80.5, highlighting its
    effectiveness and ease of use. While the project achieved its objectives,
    further opportunities for improvement include better handling of dynamic
    process changes and enhancing security features. This project demonstrates
    the powerful potential of visualizing business processes through event data,
    driving efficiency and transparency for businesses.
    <div class="flex-1 flex justify-betweeen gap-4 items-end"></div>

    <div class="relative grid place-items-center">
        <img
            class="relative object-cover z-[2] max-h-[90vh]"
            src={"/images/Screenshot.png"}
            alt="Profile image"
        />
    </div>

    <p>
        <b class="pr-2">Reference -> LinkedIn:</b>
        <a
            href="https://www.linkedin.com/in/magnuslasses"
            target="_blank"
            class="text-violet-400"
        >
            Magnus Lasses
            <sup>
                <span class="text-xs scale-75 pl-0.5">
                    <i
                        class="fa-solid fa-arrow-up-right-from-square text-xs scale-[75%]"
                    ></i>
                </span>
            </sup>
        </a>
    </p>

    <a href="/">
        <button
            class="ml-auto rounded-full bg-slate-900 text-violet-400 px-3 sm:px-4 hover:bg-slate-800 cursor-pointer aspect-square grid place-items-center fixed bottom-20 left-20 duration-200 flex p-10 z-[10]"
        >
            <i class="fa-solid">go back</i>
        </button>
    </a>
</section>
