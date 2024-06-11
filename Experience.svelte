<script>
  let isRed = false;

  function toggleColor() {
    isRed = !isRed;
  }
</script>

<div class="{isRed ? 'text-red-500' : ''}" on:click={toggleColor}>
  <section class="mb-10">
    <h2 class="text-xl font-bold mb-4">Experience</h2>
    <div class="mb-4">
        <h3 class="font-bold">KPMG</h3>
        <span class="text-sm">La Défense</span>
        <div class="text-sm italic mt-1">Financial audit <span class="block">Sept 2023 - March 2024</span></div>
        <ul class="list-disc ml-5 mt-2">
            <li>Implemented new accounting standards, including ESEF, IFRS 15 (revenue recognition), and IFRS 16 (lease contracts)</li>
            <li>Identified XBRL tags in financial statements of large-scale clients using databases</li>
            <li>Collaborated closely with the finance leadership of major corporations</li>
            <li>Reviewed clients' financial statements to guide them in standardization</li>
        </ul>
    </div>

    <div class="mb-4">
        <h3 class="font-bold">Valeo</h3>
        <span class="text-sm">Cergy</span>
        <div class="text-sm italic mt-1">Junior Consultant <span class="block">Dec 2022 - July 2023</span></div>
        <ul class="list-disc ml-5 mt-2">
            <li>Conducted a confidential project centered on formulating Valeo's product development strategy</li>
            <li>Investigated market trends and performed analysis on demand and competition</li>
            <li>Designing and budgeting the product and presenting a synthesized report to the client</li>
            <li>Administered quantitative and qualitative studies, including focus groups and interviews</li>
        </ul>
    </div>

    <div class="mb-4">
        <h3 class="font-bold">ESSEC Africa Society</h3>
        <span class="text-sm">Cergy</span>
        <div class="text-sm italic mt-1">Head of Partnerships <span class="block">Dec 2022 - July 2023</span></div>
        <ul class="list-disc ml-5 mt-2">
            <li>Management and planning of multiple association events</li>           
            <li>Organization of business meetings focused on the African continent, as well as economic and financial roundtable discussions</li>
            <li>Solicitation of companies for a professional trip to Africa</li>
        </ul>
    </div>
  </section>
</div>
