<template>
  <div>
    <nav id="nav-wrap">
      <div class="logo">
        <a href="#" id="nav-logo">
          <img src="../assets/logo.png" alt="MINI Timeline" />
        </a>
      </div>
      <div class="nav-content">
        <ul>
          <li class="g1">
            <a href="#">R50</a>
          </li>
          <li class="g1">
            <a href="#">R52</a>
          </li>
          <li class="g1">
            <a href="#">R53</a>
          </li>
          <li class="g2">
            <a href="#">R55</a>
          </li>
          <li class="g2">
            <a href="#">R56</a>
          </li>
          <li class="g2">
            <a href="#">R57</a>
          </li>
          <li class="g2">
            <a href="#">R58</a>
          </li>
          <li class="g2">
            <a href="#">R59</a>
          </li>
          <li class="g2">
            <a href="#">R60</a>
          </li>
          <li class="g2">
            <a href="#">R61</a>
          </li>
          <li class="g3">
            <a href="#">F56</a>
          </li>
          <li class="jcw">
            <a href="#">JCW</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
#nav-wrap {
  width: 18vw;
  height: 100vh;
  position: fixed;
  background: #e6e6e6;

  .logo {
    background: rgb(255, 255, 255);
    background: linear-gradient(
      180deg,
      rgba(255, 255, 255, 1) 40%,
      rgba(230, 230, 230, 1) 90%
    );
    padding: 20px 0;
    display: flex;
    justify-content: center;
  }

  .nav-content {
    display: flex;

    ul {
      list-style: none;
      width: 100%;
    }

    li {
      text-align: center;
      cursor: pointer;
      a {
        text-decoration: none;
        font-size: 1.3em;
        color: #fff;
        font-weight: 500;
        padding: 5px 0;
        display: inline-block;
        width: 100%;
      }
    }

    .g1 {
      background: #3995d5;
      &:hover {
        background: darken(#3995d5, 10);
      }
    }

    .g2 {
      background: #105fa2;
      &:hover {
        background: darken(#105fa2, 10);
      }
    }

    .g3 {
      background: #3c5264;
      &:hover {
        background: darken(#3c5264, 10);
      }
    }

    .jcw {
      background: #c24044;
      &:hover {
        background: darken(#c24044, 10);
      }
    }
  }
}
</style>
