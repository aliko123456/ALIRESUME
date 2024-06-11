<script>
  let isVisible = true;

  function toggleVisibility() {
    isVisible = !isVisible;
  }
</script>

{#if isVisible}
  <div on:dblclick={toggleVisibility}>
    <!DOCTYPE html>
    <html lang="fr">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CV Ali Koçak</title>
        <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    </head>
    <body class="bg-gray-100">
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

                <section>
                    <h2 class="text-xl font-bold mb-4">Skills</h2>
                    <h3 class="font-bold">Language</h3>
                    <div class="text-sm">Native in French and Turkish; full professional proficiency in English and German</div>
                    <h3 class="font-bold mt-4">Interests:</h3>
                    <div class="text-sm">Composing music, writing film scripts, playing basketball and gardening</div>
                </section>
            </main>
        </div>
    </body>
    </html>
  </div>
{/if}
