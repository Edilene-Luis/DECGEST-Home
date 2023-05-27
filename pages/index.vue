<template>
  <div class="main">
    <banner />
    <div class="container my-2">
      <div class="row">
        <div v-for="(item, i) in contents" :key="i" class="col-12">
          <HomeContent v-bind="item" :idx="i + 1" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      contents: [
        {
          img: '/images/img1.png',
          title: 'Missão',
          text: 'Lorem ipsum dolor sit amet consectetur. Vitae at sed purus diam in ullamcorper bibendum risus enim. Vestibulum porttitor vitae dui quam molestie nec convallis eget orci. Adipiscing volutpat commodo nunc libero in consectetur vitae non sed. Scelerisque proin mattis in sapien turpis nunc purus aliquet quis. Dictum pellentesque arcu aliquam rutrum. Sem diam iaculis varius fringilla lobortis purus et ut porta. Nibh penatibus velit sem penatibus tincidunt tristique ridiculus facilisis. Ullamcorper sagittis tempus dui aliquam commodo tincidunt. Dui gravida quis mattis diam aliquam gravida. Praesent nibh mattis scelerisque placerat. Fringilla lacus purus velit turpis facilisi neque quis vulputate commodo.',
        },
        {
          img: '/images/img2.png',
          title: 'Visão',
          text: 'Lorem ipsum dolor sit amet consectetur. Vitae at sed purus diam in ullamcorper bibendum risus enim. Vestibulum porttitor vitae dui quam molestie nec convallis eget orci. Adipiscing volutpat commodo nunc libero in consectetur vitae non sed. Scelerisque proin mattis in sapien turpis nunc purus aliquet quis. Dictum pellentesque arcu aliquam rutrum. Sem diam iaculis varius fringilla lobortis purus et ut porta. Nibh penatibus velit sem penatibus tincidunt tristique ridiculus facilisis. Ullamcorper sagittis tempus dui aliquam commodo tincidunt. Dui gravida quis mattis diam aliquam gravida. Praesent nibh mattis scelerisque placerat. Fringilla lacus purus velit turpis facilisi neque quis vulputate commodo.',
        },
        {
          img: '/images/img3.png',
          title: 'Valores',
          text: 'Lorem ipsum dolor sit amet consectetur. Vitae at sed purus diam in ullamcorper bibendum risus enim. Vestibulum porttitor vitae dui quam molestie nec convallis eget orci. Adipiscing volutpat commodo nunc libero in consectetur vitae non sed. Scelerisque proin mattis in sapien turpis nunc purus aliquet quis. Dictum pellentesque arcu aliquam rutrum. Sem diam iaculis varius fringilla lobortis purus et ut porta. Nibh penatibus velit sem penatibus tincidunt tristique ridiculus facilisis. Ullamcorper sagittis tempus dui aliquam commodo tincidunt. Dui gravida quis mattis diam aliquam gravida. Praesent nibh mattis scelerisque placerat. Fringilla lacus purus velit turpis facilisi neque quis vulputate commodo.',
        },
      ],
    }
  },
}
</script>

<style scoped>
.main {
  overflow-x: hidden;
}
</style>
