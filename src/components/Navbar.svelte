


<div class="navbar">
    <h1>Logo</h1>
    <div class="btn-wrapper">
        <button class="nav-btn"><div class="btn-text">Home</div></button>
        <button class="nav-btn"><div class="btn-text">About</div></button>
        <button class="nav-btn"><div class="btn-text">More</div></button>
    </div>
</div>


<style>
    .navbar{
        background-color: black;
        width:30.5rem;
        height: 5rem;
        top:0;
        position: sticky;
        display: flex;
        flex-direction: row;
        align-items: center;
        user-select: none;
        transition: 0.6s;
        clip-path: polygon(0% 0%, 75% 0%, 80.5% 50%, 75% 100%, 0% 100%);
    }

    h1{
        color: var(--white-color);
    }

    .btn-wrapper{
        margin-left: 3rem;
    }

    .nav-btn{
        height:4.75rem;
        width:6.5rem;
        margin-left: -1.70rem;
        font-size:.9em;
        clip-path: polygon(75% 0%, 100% 50%, 75% 100%, 0% 100%, 25% 50%, 0% 0%);
        transition: 0.6s;
    }

    .btn-text{
        transform: rotate(-59deg);
        font-weight:550;
        font-size:1rem;
    }

    .btn-wrapper:hover .nav-btn:nth-child(2){
        margin-right: 1rem;
        margin-left: -0.75rem;
    }

    
</style>