<template>
  <div class="car">
    <div class="container">
      <div class="title">
        <div class="date">2014 - Currently</div>
        <h1>F56</h1>
        <div class="models">
          <p>Cooper Hatchback</p>
          <p>Cooper S Hatchback</p>
        </div>
      </div>

      <div class="slider">
        <Slider></Slider>
      </div>

      <div class="menu-car">
        <ul>
          <li>
            <a class="active" href="#">Historical</a>
          </li>
          <li>
            <a href="#">Specifications</a>
          </li>
          <li>
            <a href="#">More About</a>
          </li>
        </ul>
      </div>

      <section id="historical">
        <h2>Historical</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum, quod. Odit molestias perspiciatis magni vel amet qui esse voluptas? Saepe modi a voluptate? Natus numquam qui molestiae exercitationem ullam! Soluta!</p>
      </section>

    </div>
  </div>
</template>

<script>
import Slider from './components/Slider'

export default {
  name: "Car",
  components: { Slider }
};
</script>

<style lang="scss" scoped>
.car {
  .container {
    padding: 0;
  }

  /* Title Car Model */
  .title {
    display: flex;
    justify-content: center;
    align-items: center;
    position: sticky;
    top: 0;
    height: 104px;
    color: #707070;
    background: #FFF;
    h1 {
      font-size: 5em;
      font-weight: 900;
    }
    .date {
      margin-right: 20px;
      padding: 0;
      font-size: 1em;
    }
    .models {
      margin-left: 20px;
      p {
        padding: 0;
        font-size: 1em;
      }
    }
  }

  /* Slider */
  .slider {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 451px;
    h2 {
      font-size: 2em;
      color: #e6e6e6;
    }
  }

  /* Menu Car Model */
  .menu-car {
    padding: 0 40px;
    margin-bottom: 50px;
    ul {
      display: flex;
      justify-content: space-between;
      li {
        list-style-type: none;
        padding: 6px 15px;
        a {
          text-decoration: none;
          color: #707070;
          font-size: 1.3em;
          text-transform: uppercase;
          &.active {
            font-weight: 700;
          }
        }
      }
    }
  }

  /* Section */
  section {
    padding: 0 20px;
  }

}
</style>

