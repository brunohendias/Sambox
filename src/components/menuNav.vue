<template>
	<div>
    <nav class="navbar navbar-expand-lg bg-dark navbar-light fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand text-white" href="#cabeca">Sam Box</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive"
          aria-controls="#navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="navbar-collapse collapse" id="navbarResponsive">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a href="#cabeca" class="nav-link js-scroll-trigger text-white">Sobre nós</a>
            </li>
            <li class="nav-item">
              <a href="#services" class="nav-link js-scroll-trigger text-white">Serviços</a>
            </li>
            <li class="nav-item">
              <a href="#contact" class="nav-link js-scroll-trigger text-white">Contato</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
	</div>
</template>

<script>
export default {
  name: 'menuNav',
}
</script>