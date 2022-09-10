<template>
  <header class="header">
    <nav>
      <ul class="contain-link favorit">
        <li>
          <a href="https://instagram.com/moreless00" target="blank"
            ><img src="@/assets/instagram.png" alt="instagram"
          /></a>
        </li>
        <li>
          <a
            href="https://www.facebook.com/karen.guimaraes.397501"
            target="blank"
            ><img src="@/assets/facebook.png" alt="facebook"
          /></a>
        </li>
        <li>
          <a href="#"><img src="@/assets/linkedin.png" alt="linkedin" /></a>
        </li>
      </ul>
    </nav>
    <div class="contain-menu">
      <div class="contain-img">
        <img src="@/assets/logo.gif" alt="logo" />
      </div>
      <nav>
        <ul class="contain-link">
          <li><a href="#">Teste</a></li>
          <li><a href="#">Teste</a></li>
          <li><a href="#">Teste</a></li>
          <li><a href="#">Teste</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>
<script>
export default {
  name: "Header",
};
</script>
<style lang="scss">
.header {
  padding: 15px;

  background: hsla(167, 68%, 73%, 1);

  background: linear-gradient(
    90deg,
    hsla(167, 68%, 73%, 1) 22%,
    hsla(178, 59%, 48%, 1) 75%
  );

  background: -moz-linear-gradient(
    90deg,
    hsla(167, 68%, 73%, 1) 22%,
    hsla(178, 59%, 48%, 1) 75%
  );

  background: -webkit-linear-gradient(
    90deg,
    hsla(167, 68%, 73%, 1) 22%,
    hsla(178, 59%, 48%, 1) 75%
  );
}
.contain-menu {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  nav {
    margin:0 auto;
  }
}
.contain-img {
  max-width: 200px;
}
.contain-link {
  display: flex;
}
.favorit {
  justify-content: end;
  li {
    max-width: 40px;
    margin-right: 15px;
    img {
      &:hover {
        padding: 2px;
      }
    }
  }
}
a{
    font:initial 1.6rem bold ;
    padding: 1.5rem;
}
</style>
