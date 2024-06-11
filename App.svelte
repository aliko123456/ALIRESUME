<script>
  import Experience from './Experience.svelte';
</script>

<main class="bg-gray-100">
  <div class="container mx-auto flex max-w-4xl p-5">
    <aside class="w-1/4 bg-blue-700 p-5 text-white">
      <h2 class="text-2xl">Pli Poçak</h2>
      <img src="A.jpg" alt="Photo de Ali Koçak" class="w-48 h-auto my-4">
      <p class="text-sm mb-4">"As a student with a passion for corporate finance, I have solid experience in financial auditing at KPMG and as a junior consultant at Valeo"</p>
      <ul class="list-none p-0">
        <li class="mb-2"><a href="mailto:ali.kocak@essec.edu" class="text-white text-sm">ali.kocak@essec.edu</a></li>
        <li><a href="https://www.linkedin.com/in/ali-ko%C3%A7ak-2b07b618a/" class="text-white text-sm">https://www.linkedin.com/in/ali-ko%C3%A7ak-2b07b618a/</a></li>
      </ul>
    </aside>

    <main class="w-3/4 p-5">
      <Experience />
    </main>
  </div>
</main>
