<script>
    const datas = [
        {
            "id":"1",
            "name":"Personality Matchmaking With Multi Armed Bandits",
            "tag":"Research",
            "desc":"Personality based matchmaking with MAB concept",
            "link":"https:google.com"
        }
    ]
</script>
<section class="about">
    <p style="color: #009CFF;">Latest research and syllabus.</p>    
    <h1>From us, free for us!</h1>
</section>
    <div style="padding: 50px;">
        <div class="card-container">
            {#each datas as item}
                <div class="card">
                    <h2>{item.name}</h2>
                    <span class="type">{item.tag}</span>
                    <p>{item.desc}</p>
                    <a href="{item.link}" class="btn">Learn More</a>
                </div>
            {/each}
        </div>
    </div>

<style>
    .type {
        padding: 5px 10px;
        background-color: white;
        border-radius: 5px;
    }
    .btn {
        padding: 5px 10px;
        background-color: rgb(33, 33, 33);
        text-decoration: none;
        color: white;
        border-radius: 5px;
    }
    .about {
        text-align: center;
        margin-top: 100px;
    }
    .about h1 {
        font-size: 3.5em;
        margin-top: 0;
        margin-bottom: 20px;
        font-weight: bolder;
    }
    .about p {
        font-weight: 400;
        margin-bottom: 0;
        padding: 0;
        font-size: 20px;
    }
    .card-container {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        padding: 20px;
        justify-content: center;
    }
    .card {
        background: #009CFF;
        padding: 20px;
        width: 300px; /* Adjust width as needed */
        box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .card p{
        color: white;
        line-height: 20px;
    }
    .card h2{
        color: white;
    }
</style>
