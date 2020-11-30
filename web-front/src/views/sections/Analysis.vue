<template>
  <v-container
    id="about"
    class="pa-0"
    fluid
    tag="section"
  >
    <v-row
      class="ma-0"
      no-gutters
    >
      <v-col
        cols="12"
        md="6"
      >
        <v-img
          height="calc(100vh - 96px - 156px)"
          src="/javert3.jpg"
        />
      </v-col>

      <v-col
        class="d-block d-md-flex align-center grey lighten-3 pa-6"
        cols="12"
        md="6"
      >
        <v-responsive
          class="mx-auto px-3 px-md-12"
          max-width="750"
        >
          <h1
            class="mb-6"
            :class="$vuetify.breakpoint.mdAndUp ? 'display-1' : 'display-1'"
          >
            안녕하십니까.<br>
          </h1>

          <p>
           저는 이번 마이다스IT 경영솔루션 운영 직무에 지원한 강동훈입니다.<br>
           사전 과제로 주어졌던 시스템 아키텍쳐 설계 과제를 단순히 아키텍쳐 설계만으로 끝내는게 아니라,<br>
           실제로 구현해보고 제가 새로 도입한 시스템이 기존의 시스템과 어떤 차이점이 있는지<br>
           분석해보는 페이지를 만들어 보았습니다.<br>
          </p>

          <div class="signature">
            jesuisjavert
          </div>
        </v-responsive>
      </v-col>
    </v-row>
     <v-row
      class="ma-0"
      no-gutters
    >
      <v-col
        cols="12"
        md="6"
      >
        <v-img
          height="calc(100vh - 96px - 156px)"
          src="/javert3.jpg"
        />
      </v-col>

      <v-col
        class="d-block d-md-flex align-center grey lighten-3 pa-6"
        cols="12"
        md="6"
      >
        <v-responsive
          class="mx-auto px-3 px-md-12"
          max-width="750"
        >
          <h1
            class="mb-6"
            :class="$vuetify.breakpoint.mdAndUp ? 'display-1' : 'display-1'"
          >
            안녕하십니까.<br>
          </h1>

          <p>
           저는 이번 마이다스IT 경영솔루션 운영 직무에 지원한 강동훈입니다.<br>
           사전 과제로 주어졌던 시스템 아키텍쳐 설계 과제를 단순히 아키텍쳐 설계만으로 끝내는게 아니라,<br>
           실제로 구현해보고 제가 새로 도입한 시스템이 기존의 시스템과 어떤 차이점이 있는지<br>
           분석해보는 페이지를 만들어 보았습니다.<br>
          </p>

          <div class="signature">
            jesuisjavert
          </div>
        </v-responsive>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'Analysis',
  }
</script>

<style lang="sass">
  .signature
    font-family: 'Cedarville Cursive', cursive !important
    font-size: 2rem
    font-style: italic
</style>
