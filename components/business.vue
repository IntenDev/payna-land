<template>
  <div>
    <div class="work">
      <span>WORK BETTER</span>
    </div>

    <div class="mb20-block">
      <h2>For Your Business</h2>
    </div>

    <div class="mb50-block">
      <p>We did research what your company needs and here we are providing all of them just for you</p>
    </div>

    <div class="container">
      <div v-for="busblock in busblocks" :key="busblock.id" class="business-block">
        <div class="image">
          <img :src="busblock.image" alt="icon">
        </div>
        <div class="block-title">
          <h3>{{ busblock.title }}</h3>
        </div>
        <div class="block-description">
          <p>{{ busblock.description }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Business',
  data () {
    return {
      busblocks: [
        {
          id: 1,
          image: '/img/Group21.png',
          title: 'Share Insights',
          description: 'Working together with your'
        },
        {
          id: 2,
          image: '/img/Group22.png',
          title: 'Kanban Mode',
          description: 'Organize the report that easy to be understand'
        },
        {
          id: 3,
          image: '/img/Group17.png',
          title: 'Track Leads',
          description: 'See where your money goes and comes in business'
        },
        {
          id: 4,
          image: '/img/Group18.png',
          title: 'Reward System',
          description: 'Motivate your team working harder and receive a gift'
        },
        {
          id: 5,
          image: '/img/Group19.png',
          title: 'Offline Mode',
          description: 'Use the feature while off from internet? sure can'
        },
        {
          id: 6,
          image: '/img/Group20.png',
          title: '189 Country',
          description: 'Working together worldwide people from anywhere'
        }
      ]
    }
  }
}
</script>

<style scoped>
.work {
  font-family: PoppinsB;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 24px;
  /* identical to box height */
  text-align: center;
  color: #F75C4E;
}
h2 {
  font-family: PoppinsB;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 54px;
  /* identical to box height */
  text-align: center;
  color: #000000;
}
h3 {
  font-family: Poppins;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 42px;
}
p {
  font-family: Poppins;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 32px;
  /* or 200% */
  text-align: center;
  color: #575455;
}
.business-block {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  width: 320px;
  padding-right: 93px;
}
.container {
  margin-left: 200px;
}
.image {
  width: 60px;
}
.block-title {
}

</style>
