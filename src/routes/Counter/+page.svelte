<script>
    let count = 0;
</script>

<main class="flex flex-col items-center justify-center min-h-screen bg-gray-100">
    <div class="p-6 bg-white shadow-lg rounded-lg">
        <button 
            on:click={() => count++} 
            class="px-6 py-3 bg-blue-500 text-white text-lg font-semibold rounded-lg shadow-md hover:bg-blue-600 transition duration-300"
        >
            Clicks: {count}
        </button>
    </div>
</main>
