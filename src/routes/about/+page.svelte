<script>
    import ExpandingHr from "../../lib/common/ExpandingHR.svelte";
    import Header from "../../lib/layout/Header.svelte";
    import PageWrapper from "../../lib/common/PageWrapper.svelte";

</script>
<Header></Header>

<PageWrapper>
    <h1 class="text-3xl font-semibold">Meet the Team</h1>
    <ExpandingHr --width=10em/>
    We are an 8 person FTC team from Bellevue, Washington. Here's everyone on the team!<br>
    <!-- make this section look prettier later -->

    <b class="mt-4 text-xl">Mechanical</b>
    <ul>

        <li>Erwin, 12th Grade - Co-Captain</li>
        <li>Allen, 12th Grade - Co-Captain</li>
    </ul>

    <b class="mt-4  text-xl">Programming</b>
    <ul>
        <li>Ted, 10th grade</li>
        <li>Quincy, 12th Grade</li>
        <li>Micheal, 12th Grade</li>
    </ul>

    <b class="mt-4 text-xl">Outreach</b>
    <ul>
        <li>Vedika, 12th Grade - Co-Captain</li>
        <li>Kireeti, 12th Grade - Co-Captain</li>
    </ul>

    <h1 class="text-3xl font-semibold mt-4">Upcoming Events</h1>
    <ExpandingHr --width=10em/>
    <li><span class="text-evorange">8/2/25 - Catch us at SeaFair @ Genesee Park</span></li>
    <li><span class="text-evorange">8/13/25 - We will be meeting with U.S Congressman Adam Smith to propose STEM events and legislation in the district</span></li>
    <li><span class="text-evorange">9/3/25 - We will be @ The UN UNICEF Executive Board Meeting</span></li>
    <li><span class="text-evorange">10/6/25 - We will be presenting @ Issaquah Salmon Days!</span></li>
    <li><span class="text-evorange">Stay Updated For More!</span></li>


    <h1 class="text-3xl font-semibold mt-4">Past Results</h1>
    <ExpandingHr --width=10em/>

    <h2 class="text-xl font-bold">2024-2025 INTO THE DEEP</h2>
    <ul>
        <li><b span class="text-evyellow">Top 64</b> at FIRST World Championship</li>
        <br>
        <li><b span class="text-evyellow">World Championship Qualifier</b> at Washington State Championship</li>
        <li><span class="text-evorange">Dean's List Finalist (Kireeti Kompella)</span> at Washington State Championship</li>
        <li><span class="text-evyellow">Winning Alliance 1st Pick</span> at Washington State Championship</li>
        <li><span class="text-evorange">Think Award Winner</span> at Washington State Championship</li>
        <br>
        <li><b class="text-evyellow">Inspire Award 3rd Place</b> at Capek Semifinal</li>
        <li><b class="text-evorange">Winning Alliance 1st Pick</b> at Capek Semifinal</li>
        <br>
        <li><b class="text-evorange">Inspire Award 1st Place</b> at Feynman Interleague</li>
        <li><span class="text-evorange">Winning Alliance Captain</span> at Feynman Interleague</li>
    </ul>

    <h2 class="text-xl font-bold">2023-2024 CENTERSTAGE</h2>
    <ul>
        <li><span class="text-evyellow">Semifinalist Alliance 2nd Pick</span> at Washington State Championship</li>
        <li><span class="text-evorange">Motivate Award 2nd Place</span> at Washington State Championship</li>
        <br>
        <li><b class="text-evyellow">Winning Alliance 1st Pick</b> at Pastuer Interleague</li>
        <li><b class="text-evorange">Inspire Award 2nd Place</b> at Pasteur Interleague</li>
        <li><b class="text-evorange">Motivate Award Winner</b> at Pasteur Interleague</li>
        <li><span class="text-evorange">Control Award 3rd Place</span> at Pasteur Interleague</li>
    </ul>

    <h2 class="text-xl font-bold mt-4">2022-2023 POWERPLAY</h2>
    <ul>
        <li><span class="text-evyellow">Semifinalist Alliance 1st Pick</span> at Washington State Championship</li>
        <br>
        <li><span class="text-evyellow">Finalist Alliance 1st Pick</span> at Pastuer Interleague</li>
        <li><b class="text-evorange">Inspire Award Winner</b> at Pasteur Interleague</li>
        <li><span class="text-evorange">Think Award 2nd Place</span> at Pasteur Interleague</li>
        <li><span class="text-evorange">Motivate Award 3rd Place</span> at Pasteur Interleague</li>
    </ul>
</PageWrapper>
