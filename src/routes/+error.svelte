<script lang="ts">
    export let status: number;
</script>

<svelte:head>
    <title>{status} GoldSMP - Hiba</title>
</svelte:head>

<div class="min-h-screen flex flex-col items-center justify-center" style="background-color: #2e2e2e; color: white; padding: 20px; text-align: center;">
    <h1 class="text-3xl font-bold mb-4">Hiba {status}</h1>
    <p class="text-lg mb-8">Valami nem stimmel. Kérjük, térj vissza a kezdőlapra.</p>
    <img
        src={`https://http.cat/${status}`}
        alt={`HTTP ${status}`}
        class="max-w-md w-full rounded-lg shadow-lg mb-8"
        on:error={(e) => (e.target as HTMLImageElement).style.display = 'none'}
    />

    <a
        href="/"
        class="inline-block px-6 py-3 text-white rounded-lg shadow transition-transform transform hover:scale-105"
        style="
            background: linear-gradient(45deg, #ffd700, #ffcc00);
            border: none;
            color: black;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s, box-shadow 0.2s;
        "
        on:mouseover={(event) => ((event.target as HTMLElement).style.boxShadow = '0 6px 10px rgba(0, 0, 0, 0.2)')}
        on:mouseout={(event) => ((event.target as HTMLElement).style.boxShadow = '0 4px 6px rgba(0, 0, 0, 0.1)')}
        on:focus={(event) => ((event.target as HTMLElement).style.boxShadow = '0 6px 10px rgba(0, 0, 0, 0.2)')}
        on:blur={(event) => ((event.target as HTMLElement).style.boxShadow = '0 4px 6px rgba(0, 0, 0, 0.1)')}
    >
        Kezdőlap
    </a>
</div>
