<template>

<section class="row bg-about">
    <div class="col-12 col-md-6 d-flex flex-column justify-content-center text-center">
        <p id="name-title">AUSTIN PERRY</p>
    </div>
    <div class="col-12 col-md-6 d-flex flex-column justify-content-center">
        <p class="text-bg">
            Welcome to my website! I'm Austin, a passionate full-stack software developer.
            <br><br>
            I have an Associates of Science (AS) in S.T.E.M. from the College of Western Idaho, where I completed multiple computer science courses. I further honed my skills by successfully completing the Immersive Full Stack Web Development Course at Boise Codeworks.
            <br><br>
            I enjoy diving into projects and acquiring new skills. Beyond software development, you'll find me immersed in video games, movies, playing ping pong, or enjoying the company of my cat. 
            <br><br>
            I'm excited to work with a team, eager to learn, and looking forward to growing as a software developer and as a person. If you'd like to connect or to collaborate please feel free to reach out to me on <a target="blank" href="https://www.linkedin.com/in/austin-perry22/">Linkedin</a> or by using the contact form provided below.
        </p>
        
    </div>
</section>
</template>


<script>
</script>


<style lang="scss" scoped>

#name-title{
    font-size: 56px;
}

.text-bg{
    background-color: rgba(0, 0, 0, 0.5);
    border-radius: 2rem;
    padding: 1rem;
}
.bg-about{
    background-image: url(https://images.unsplash.com/photo-1668681919287-7367677cdc4c?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
    background-size: cover;
    animation: bg-anim 65s;
    animation-fill-mode: forwards;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
    animation-direction: alternate;
}

.row{
  height: 85vh;
}

@keyframes bg-anim {
    from{
        background-position: top left;background-size: 3000px;
    }
    25%{
        background-position: 25% 10%;
    }
    50%{
        background-position: 50% 25%;
    }
    75%{
        background-position: 75% 75%;
    }
    to{
        background-position: 85% right; background-size: 3000px;
    }
}

@media screen and (max-width: 768px){
    #name-title{
        font-size: 46px;
    }
    .row{
        height: 125vh;
    }
}
</style>