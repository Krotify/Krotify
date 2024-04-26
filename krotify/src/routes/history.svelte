<section class="history">
    <p>How were we created?</p>    
    <h1>Our history!</h1>
</section>

<div class="timeline">
    <div class="container">
        <div class="date">2019</div>
        <div class="content">
            <h2>Egg hatched!</h2>
            <p>Web & graphic design journey started on 2019.</p>
        </div>
    </div>
    <div class="container">
        <div class="date">2020</div>
        <div class="content">
            <h2>+1 New product</h2>
            <p>Started making custom applications on 2020!</p>
        </div>
    </div>
    <div class="container">
        <div class="date">2022</div>
        <div class="content">
            <h2>Rebrand</h2>
            <p>Ubitoes (Krotify's legacy name) rebranded this year!</p>
        </div>
        <div class="content">
            <h2>+2 products</h2>
            <p>Started doing IT Consultation & Training this year!</p>
        </div>
    </div>
    <div class="container">
        <div class="date">2024</div>
        <div class="content">
            <h2>Team gathered!</h2>
            <p>No more doing all of this all alone, the power of friendship has been acquired.</p>
        </div>
    </div>
</div>

<style>
    body {
        font-family: Arial, sans-serif;
    }
    .timeline {
        max-width: 800px;
        margin: 0 auto;
    }
    .container {
        background-color: white;
        border-radius: 8px;
        padding: 20px;
        margin-bottom: 20px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .date {
        color: #009CFF;
        font-size: 1.2em;
        font-weight: bold;
        margin-bottom: 5px;
    }
    .content h2 {
        color: #333;
        font-size: 20px;
        margin-top: 5px;
        margin-bottom: 10px;
    }
    .content p {
        color: #737373;
        font-size: 18px;
    }

    /* Responsive Design */
    @media screen and (max-width: 600px) {
        .timeline {
            max-width: 100%;
        }
        .container {
            padding: 15px;
        }
        .date {
            font-size: 1em;
        }
    }
    
    .history {
        text-align: center;
        margin-top: 100px;
    }
    .history h1 {
        font-size: 3.5em;
        margin-top: 0;
        margin-bottom: 20px;
        font-weight: bolder;
    }
    .history p {
        font-weight: 400;
        margin-bottom: 0;
        padding: 0;
        font-size: 20px;
    }
    .history button {
        background-color: black;
        color: white;
        border: none;
        padding: 10px 20px;
        font-weight: 600;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }
    .about button:hover {
        background-color: #333;
    }
</style>