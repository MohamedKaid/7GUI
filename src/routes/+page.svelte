<script>
    let title = "Welcome to Your Library Project";
    let subtitle = "A place to build, experiment, and showcase your Svelte projects.";
</script>

<main class="flex flex-col items-center justify-center min-h-screen bg-gray-100 text-center p-6">
    <h1 class="text-4xl font-bold text-blue-600">{title}</h1>
    <p class="text-lg text-gray-700 mt-2">{subtitle}</p>

    <!-- Navigation Links -->
    <div class="mt-6 flex flex-col md:flex-row gap-4">
        <a href="/counter" 
            class="px-6 py-3 bg-blue-500 text-white text-lg font-semibold rounded-lg shadow-md hover:bg-blue-600 transition duration-300"
        >
            ➡ Counter
        </a>

        <a href="/tempconv" 
            class="px-6 py-3 bg-green-500 text-white text-lg font-semibold rounded-lg shadow-md hover:bg-green-600 transition duration-300"
        >
            🌡 Temperature Converter
        </a>
    </div>

    <!-- Documentation Link -->
    <p class="mt-6 text-gray-600">
        Need help? Check out the 
        <a href="https://svelte.dev/docs/kit" class="text-blue-500 underline hover:text-blue-700">SvelteKit Docs</a>.
    </p>
</main>
<div class="bg-blue-500 text-white text-center p-4">
    Tailwind is working! 🎉
</div>
