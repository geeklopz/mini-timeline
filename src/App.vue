<template>
  <Wrapper>
    <NavBar></NavBar>
    <Main>
      <Car></Car>
    </Main>
  </Wrapper>
</template>

<script>
import Wrapper from './components/Wrapper'
import NavBar from './components/NavBar'
import Main from './components/Main'
import Car from './components/Car'

export default {
  name: 'MiniTimeline',
  components: { Wrapper, NavBar, Main, Car },
  data: () => ({

  }),
  methods: {

  }
}
</script>

<style lang="scss">
* { margin: 0; padding: 0; box-sizing: border-box; }
html, body {
  width: 100%;
  height: 100%;
  font-family: 'Poppins', sans-serif;
}
</style>
