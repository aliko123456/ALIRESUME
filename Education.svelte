<script>
  let isMoved = false;

  function moveLeft() {
    isMoved = !isMoved;
  }
</script>

<div class="{isMoved ? 'translate-x-10' : ''}" on:click={moveLeft}>
  <section class="mb-10">
    <h2 class="text-xl font-bold mb-4">Education</h2>
    <div class="mb-4">
        <h3 class="font-bold">ESSEC Business School</h3>
        <span class="text-sm">Cergy</span>
        <p class="text-sm italic">Master in Management</p>
        <ul class="list-disc ml-5 mt-2">
            <li>Relevant Coursework: Corporate Finance, Accounting</li>
        </ul>
    </div>
    <div class="mb-4">
        <h3 class="font-bold">Intégrale Prépa</h3>
        <span class="text-sm">Paris</span>
        <p class="text-sm italic">Economic and Commercial Preparatory Class, scientific option</p>
        <ul class="list-disc ml-5 mt-2">
            <li>Relevant Coursework: Mathematics, Geopolitics, Humanities</li>
        </ul>
    </div>
    <div class="mb-4">
        <h3 class="font-bold">Lycée Charles Peguy</h3>
        <span class="text-sm">Orléans</span>
        <p class="text-sm italic">French Scientific Baccalaureate, graduated with highest honors</p>
    </div>
  </section>
</div>
