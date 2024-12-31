<template>

  <nav class="navbar">
    <ul>
      <li class="nav-item">
          <nuxt-link to="/" class="nav-link active" aria-current="page">Beranda</nuxt-link>
      </li>
      <li class="nav-item dropdown">
        <a href="#" class="nav-link dropdown-toggle">Profil</a>
        <ul class="dropdown-menu">
          <li><nuxt-link to="/profil/identitasSekolah">Identitas Sekolah</nuxt-link></li>
          <li><nuxt-link to="/profil/sejarah">Sejarah</nuxt-link></li>
          <li><nuxt-link to="/profil/visiMisi">Visi & Misi</nuxt-link></li>
          
          <li><a href="#"></a></li>
        </ul>
      </li>
      <li class="nav-item">
        <nuxt-link to="/ekskul/ekstrakulikuler" class="nav-link active" aria-current="page">Ekstrakulikuler</nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link to="/gelery/" class="nav-link active" aria-current="page">Galery</nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link to="/kontak/index" class="nav-link active" aria-current="page">Kontak Kami</nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inria+Serif:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');

/* .navbar {
  background-color: #D9D9D9;
} */

.navbar {
font-family: "Inria Serif", serif;
font-weight: 500;
font-style: normal;
margin: 0px;
background-color:#D9D9D9;
color: #000000;
padding: 1em;
justify-content: center ;
font-size: 20px;
/* text-align: center; */

}

.nav-item {
display: inline-block;
margin-right: 20px;
position: relative;
}

.dropdown-toggle {
cursor: pointer;
}

.dropdown-menu {
background-color: #D9D9D9;
border: none;
display: none;
padding: 10px;
position: absolute;
top: 100%;
left: 0;
z-index: 1;
}

.dropdown-menu li {
display: block;
margin-bottom: 10px;
}

.dropdown-menu a {
color: black;
text-decoration: none;
}

.dropdown-menu a:hover {
color: #ccc;
}

.nav-item:hover .dropdown-menu {
display: block;
}
</style>

