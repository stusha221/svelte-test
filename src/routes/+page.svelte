<nav>
    <div class="nav-container">
    <a href="/" class="nav-logo" title="Back to Homepage">Имя Фамилия </a>
     <div class="nav-links">
    <a href="/about" class="link">Обо мне</a>
    <a href="/blog" class="link" >Блог</a>
    <a href="/projects" class="link">Портфолио </a>
    <a href="/contact" class="link">Контакты</a>
    </div>
    </div>
    </nav>
    <div class="container">
    <!-- Pages will be injected below -->
     <slot></slot>
    </div>
    <style>
    .container {
    max-width: 1400px; 
    margin: 50px auto;
    }
    </style>

<svelte:head>
<title>Анастасия Ваулина </title>
</svelte:head>
<div class='container'>
<div class='info'>
<div class='animate-background'>
<div class='container info-container'>
<div class='info-text'>
<h1>
<p class='animate-text-1'>Lorem ipsum dolor sit,</p> <p class='text-2'>Lorem ipsum dolor sit amet.</p>
</h1>
</div>
<h2 class='subtitle'>
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium architecto au
cupiditate dolores
ducimus expedita labore nemo odio quibusdam quidem sapiente soluta. </h2>
<div style='color:black' class='scroll-button animate-scroll' tabindex='0'>
<a href='/about'>Click Here</a> <div class='arrow'>→</div>
</div>
</div>
</div>
</div>
</div>
<div class='background-div'></div>

