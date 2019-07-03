<template>
  <div>
    <main id="main"></main>

    <nav id="nav-wrap">
      <a href="#" id="nav-logo">
        MINI
        <br />TIMELINE
      </a>

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
  float: left;
  width: 20vw;
  height: 100vh;
  position: fixed;
}

.g1 {
  display: flex;

  ul {
    list-style: none;
    width: 100%;

    li {
      background: #3995d5;
      text-align: center;
      padding: 15px;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
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
      padding: 15px;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
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
      padding: 15px;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
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
      padding: 15px;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: bold;
      }
    }
  }
}
</style>
