


<div class="header">
    <div class="title-wrap">
        <div class="title">Title</div>
    </div>
    <div class="author">
        <div class="name">Author</div>
    </div>
</div>


<style>

    .header{
        display: flex;
        justify-content: space-between;
        align-items:flex-start;
    }
    .title-wrap{
        background-color: black;
        clip-path: polygon(50% 0%, 100% 0, 93% 22%, 0 22%, 0 0);
        width: 800px;
        padding-left: 3rem;
        padding-right: 3rem;
        height: 150px;
    }

    .author{
        background-color: black;
        clip-path: polygon(10.4% 0, 75% 0%, 100% 0, 100% 16%, 0 16%);
        text-align: end;
        width: 525px;
        padding-left: 3rem;
        padding-right: 3rem;
        height: 220px;
    }

    .title,
    .name{
        color: var(--white-color);
    }

    @media(max-width:700px){
        
    }
</style>