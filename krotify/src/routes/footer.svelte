<hr>
<div class="foo-content">
    <div class="flex-container">
        <div class="card">
            <img src="favicon.png"/>
            <h2>Krotify</h2>
            <p>+62 813-7905-8918</p>
            <p>contact@krotify.com</p>

        </div>
        <div class="card">
            <h2>Links</h2>
            <ul>
                <li>About</li>
                <li>Research</li>
                <li>Newsletter</li>
                <li>Contact</li>
            </ul>
        </div>
        <div class="card">
            <h2>Socials</h2>
        </div>
    </div>
</div>
<div class="foo">
    © Copyright 2024 Krotify.com All Rights Reserved.
</div>

<style>
    .foo-content{
        padding: 20px;
    }
    .foo-content p{
        font-size: 15px;
    }
    .foo-content li{
        margin: 10px 0;
        font-size: 15px;
    }
    ul {
  position: relative;
  list-style: none;
}

li::before {
  content: '>';
  position: absolute;
  left: 0;
}
    .foo-content h2{
        font-size: 20px;
    }
    .foo{
        background-color:#000000;
        color: white;
        padding: 20px;
    }
    /* Styling for the flexbox container */
.flex-container {
            display: flex;
            justify-content: space-around; /* Distributes space evenly around the items */
        }
        /* Basic card styling */
        .card {
            width: 30%; /* Each card takes up 30% of the flex container width */
            text-align: left; /* Center the text inside the card */
        }
</style>