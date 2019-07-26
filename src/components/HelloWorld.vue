<template>
  <div>
    <main id="main">

    </main>

    <nav id="nav-wrap">

      <div class="logo">
        <a href="#" id="nav-logo">
          <img src="../assets/logo.png" alt="MINI Timeline">
        </a>
      </div>

      <div class="nav-content g1">
        <ul>
          <li>
            <a href="#">R50</a>
          </li>
          <li>
            <a href="#">R52</a>
          </li>
          <li>
            <a href="#">R53</a>
          </li>
        </ul>
      </div>

      <div class="nav-content g2">
        <ul>
          <li>
            <a href="#">R55</a>
          </li>
          <li>
            <a href="#">R56</a>
          </li>
          <li>
            <a href="#">R57</a>
          </li>
          <li>
            <a href="#">R58</a>
          </li>
          <li>
            <a href="#">R59</a>
          </li>
          <li>
            <a href="#">R60</a>
          </li>
          <li>
            <a href="#">R61</a>
          </li>
        </ul>
      </div>

      <div class="nav-content g3">
        <ul>
          <li>
            <a href="#">F56</a>
          </li>
        </ul>
      </div>

      <div class="nav-content hp">
        <ul>
          <li>
            <a href="#">JCW</a>
          </li>
        </ul>
      </div>

    </nav>
  </div>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
#nav-wrap {
  width: 20vw;
  height: 100vh;
  position: fixed;
  background: #e6e6e6;

  .logo {
    background: rgb(255,255,255);
    background: linear-gradient(180deg, rgba(255,255,255,1) 40%, rgba(230,230,230,1) 90%);
    padding: 20px 0;
    display: flex;
    justify-content: center;
  }

  .g1 {
  display: flex;

  ul {
    list-style: none;
    width: 100%;

    li {
      background: #3995d5;
      text-align: center;
      padding: 5px;
      cursor: pointer;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
      }
      &:hover {
        background: darken(#3995d5, 10);
      }
    }
  }
}

.g2 {
  display: flex;

  ul {
    list-style: none;
    width: 100%;

    li {
      background: #105fa2;
      text-align: center;
      padding: 5px;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
      }
      &:hover {
        background: darken(#105fa2, 10);
      }
    }
  }
}

.g3 {
  display: flex;

  ul {
    list-style: none;
    width: 100%;

    li {
      background: #3C5264;
      text-align: center;
      padding: 5px;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
      }
      &:hover {
        background: darken(#3C5264, 10);
      }
    }
  }
}

.hp {
  display: flex;

  ul {
    list-style: none;
    width: 100%;

    li {
      background: #C24044;
      text-align: center;
      padding: 5px;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
      }
      &:hover {
        background: darken(#C24044, 10);
      }
    }
  }
}
}

</style>
