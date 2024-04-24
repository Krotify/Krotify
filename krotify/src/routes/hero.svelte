<!-- src/components/HeroSection.svelte -->
<script>
    // Any JavaScript specific to the hero section can go here
</script>

<section class="hero">
    <h1>Digitalize<br>Your Business</h1>
    <p>Level up your business by digitalized your business with us!</p>
    <button on:click={() => console.log('Learn more clicked')}>Learn More</button>
</section>

<style>
    .hero {
        padding: 0px 50px;
        padding-bottom: 80px;
        text-align: left;
        color: white;
        background-color: #009CFF;

    }
    .hero h1 {
        font-size: 6em;
        margin-bottom: 20px;
        font-weight: black;
    }
    .hero p {
        font-weight: lighter;
        margin-bottom: 30px;
        font-size: 25px;
    }
    .hero button {
        background-color: black;
        color: white;
        border: none;
        font-size: 20px;
        border-radius: 50px;
        padding: 15px 30px;
        font-weight: lighter;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }
    .hero button:hover {
        background-color: #333;
    }
</style>
