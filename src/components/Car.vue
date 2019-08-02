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
        <p>The third generation Mini was unveiled by BMW in November 2013, with sales starting in the first half of 2014. The new car is 98 mm longer, 44 mm wider, and 7 mm taller than the outgoing model, with a 28 mm longer wheelbase and an increase in track width (+42 mm front and +34 mm rear). The increase in size results in a larger interior and a boot volume increase to 211 litres.</p>
        <p>Six all-new engines are offered for this Mini, 4 petrol, and 2 diesels: two models of a 1.2 litre three-cylinder petrol with either 75 bhp or 102 bhp, a 1.5 litre 3-cylinder petrol with 136 bhp, (BMW B38 engine), a 2.0 litre 4-cylinder petrol (BMW B48 engine) that produces 192 bhp for the Cooper S, and a 1.5 litre 3-cylinder diesel (BMW B37 engine) in 2 levels of power output: 95 bhp and 116 bhp (Cooper D), and a 2.0 litre turbo-diesel inline-4 engine that produces 168 bhp (Cooper SD). These engines are mated with a choice of either a 6-speed manual, a 6-speed automatic, or a 6-speed sports automatic gearbox.</p>
        <p>MINI has also released an all-new model called the MINI 5-door (AKA 4-door in US, F55). It is marketed as a 5-door version of the new 3rd generation Hatch. The base MINI 5-door is 190 lbs heavier and 6 inches longer than the 3-door MINI Hatch models with similar performance characteristics and more cargo space.</p>
        <p>The 3-door Mini with an automatic transmission will reach 0–97 km/h (0–60 mph) in 7.3 seconds for the 1.5L 3-cylinder petrol model and in 6.4 seconds with the 2.0L 4-cylinder petrol engine.</p>
        <p>The Cooper S soon got out-powered by the higher performing John Cooper Works model in 2015.</p>
        <p>In 2018, the LCI brought twin turbos to the 3-cylinder diesel engines, albeit with no changes in output. The 6-speed Steptronic torque-converter was also replaced by a 7-speed dual-clutch transmission in all models but the Cooper SD and JCW, with the latter now fitted with a 8-speed Steptronic auto. These changes allow for improved efficiency and better emissions test results in the WLTP cycle, as well as marginally improved performance.</p>
      </section>

    </div>
  </div>
</template>

<script>
import Slider from '../components/Slider'

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

    /* Styled */
    box-shadow: 0 1px 4px 0 rgba(192, 208, 230, 0.8);
    border-bottom: 10px solid rgba(230, 236, 245, 0.3);

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
    height: 450px;
  }

  /* Menu Car Model */
  .menu-car {
    padding: 0 40px;
    margin-bottom: 50px;
    border-bottom: 2px solid rgba(230, 236, 245, 0.3);

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
            border-bottom: 8px solid rgba(230, 236, 245, 0.9);
          }
        }
      }
    }
  }

  /* Section */
  section {
    margin-bottom: 50px;
    padding: 0 20px;

    p {
      margin: 10px 0;
      font-size: .9em;
    }

  }

}
</style>

