<script>
    import { base } from "$app/paths";
    import ExpandingHr from "../../lib/common/ExpandingHR.svelte";
    import PageWrapper from "../../lib/common/PageWrapper.svelte";
    import StatBox from "../../lib/common/StatBox.svelte";
    import Header from "../../lib/layout/Header.svelte";
</script>
<Header/>
<PageWrapper>
    <h1 class="text-3xl font-semibold">CENTERSTAGE</h1>
    <ExpandingHr --width=10em/>

    <h2 class="text-xl">Season Statistics</h2><br>
    <div class="flex flex-col md:flex-row w-full h-full md:w-2/3 justify-evenly align-middle content-center items-center">
        <StatBox number=70.56 truncateDecimals=2 duration=3000 statisticName="<small>(Top 81%)</small>">OPR</StatBox>
        <div class="md:hidden"><ExpandingHr --width=15em/></div>
        <div class="w-0 h-16 hidden md:block border-white border-l-[2px]"></div>
        <StatBox number=2 truncateDecimals=0 duration=3000 statisticName="<small>teams in the world with Differential Swerve</small>">One of</StatBox>
        <div class="md:hidden"><ExpandingHr --width=15em/></div>
        <div class="w-0 h-16 hidden md:block border-white border-l-[2px]"></div>
        <StatBox number=82 truncateDecimals=0 duration=3000 statisticName="<small> Point Autonomous</small>">Our</StatBox>
    </div><br>
    <p>Our 2023-2024 CENTERSTAGE campaign went through two major iterations, dozens of subsystem iterations, and many different minor tweaks and
     changes before becoming the robot you see today.</p><br>
    <h2 class="text-2xl font-semibold">Version 1</h2>
    <img src="{base}/centerstage/csv1.jpg" class="max-h-[30em] mt-4" alt="The first iteration of the EV robot."><br>
    <p>Version 1 featured an active intake transferring into a bucket on a set of tilting slides. It also included Differential Swerve.</p>
    <h2 class="text-2xl font-semibold mt-4">Version 2</h2>
    <img src="{base}/evcsrobo.png" class="max-h-[30em] mt-4" alt="The second iteration of the EV robot.">
    <p>Version 2 featured a passive intake on a very long (approx 5ft) tilting extension. It also included Differential Swerve.</p>
</PageWrapper>
