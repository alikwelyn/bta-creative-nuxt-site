<template>
    <div>
        <nav class="navbar navbar-expand-lg">
            <div class="container">
                <NuxtLink 
                    to="/"
                    class="navbar-brand"
                >
                    <img src="~/assets/logo-bta.svg" width="100" />
                </NuxtLink>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item">
                            <a 
                                href="#trabalhos"
                                class="nav-link active"
                            >
                            trabalhos
                            </a>
                        </li>
                        <li class="nav-item">
                            <a 
                                href="#como-fazemos"
                                class="nav-link active"
                            >
                            como fazemos
                            </a>
                        </li>
                        <li class="nav-item">
                            <a 
                                href="#parceiros"
                                class="nav-link active"
                            >
                            parceiros
                            </a>
                        </li>
                        <li class="nav-item">
                            <NuxtLink 
                                to="/blog"
                                class="nav-link active"
                            >
                            Blog
                            </NuxtLink>
                        </li>
                        <li class="nav-item">
                            <a 
                                href="#contato"
                                class="nav-link active"
                            >
                            contato
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style>
.navbar {
    background-color: transparent;
}
.navbar-nav > li.nav-item {
    padding-right: 10px;
}
.navbar-nav > li.nav-item > .nav-link {
    color: #6d6e71;
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 16px;
    text-transform: lowercase;
}
.navbar-nav > li.nav-item > .nav-link:hover {
  color: #fb1787;
}
</style>