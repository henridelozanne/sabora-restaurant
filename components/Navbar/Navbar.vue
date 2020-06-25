<template>
  <div class="navbar">
    <nuxt-link to="/" class="website-title">SABORA</nuxt-link>
    <div class="links-and-reservation">
      <nav>
        <ul class="nav-list">
          <li>
            <nuxt-link to="/" style="color: #C19D60">HOME</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/menu">MENU</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/about">ABOUT</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contact">CONTACT</nuxt-link>
          </li>
        </ul>
      </nav>
      <div class="menu-logo-ctn">
        <MenuLogo />
      </div>
      <div class="reservation">RESERVATION</div>
    </div>
  </div>
</template>

<script>
import MenuLogo from '../SVGs/MenuLogo'

export default {
  name: 'Navbar',
  components: {
    MenuLogo
  }
}
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #fff;
  height: 70px;
  border-top: none;
  padding-left: 20px;

  .website-title {
    font-weight: 800;
    text-decoration: none;
    color: black;
  }

  .links-and-reservation {
    display: flex;
    align-items: center;
    height: 100%;

    .menu-logo-ctn {
      padding: 0 20px;
      height: 100%;
      border-left: 1px solid rgb(230, 230, 230);
      display: flex;
      align-items: center;
      display: none;
      cursor: pointer;
    }

    @media screen and (max-width: 1400px) {
      nav {
        display: none;
      }

      .menu-logo-ctn {
        display: flex;
      }
    }
    
    .nav-list {
      display: flex;
      list-style-type: none;
      font-weight: 700;
      font-size: 13px;
      margin-right: 20px;

      li {
        cursor: pointer;

        &:hover {
          a {
            color: #C19D60;
          }
        }

        a {
          text-decoration: none;
          color: rgb(60, 60, 60);
        }
      }

      li:not(:last-of-type) {
        margin-right: 20px;
      }
    }

    .reservation {
      padding: 0 20px;
      border-left: 1px solid rgb(230, 230, 230);
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 11px;
      font-weight: 700;
      color: rgb(164, 164, 164);
      letter-spacing: 2px;
      cursor: pointer;

      &:hover {
        background: #C19D60;
        color: white;
      }
    }
  }
}
</style>
