<!-- src/components/Navbar.svelte -->
<script>
    // You can define component-specific logic here
</script>

<nav class="navbar">
    <span>
        <img src="favicon.png" alt="logo" width="50px">
    </span>
    <div>
        <a href="/about">About</a>
        <a href="/syllabus">Research</a>
        <a href="/newsletter">Newsletter</a>
        <a href="/contact">Contact</a>
    </div>
</nav>

<style>
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 50px;
        background-color: #009CFF;
        font-size: 20px;

    }
    .navbar a {
        color: white;
        text-decoration: none;
        margin: 0 10px;
        font-weight: 600;
    }
    
</style>
