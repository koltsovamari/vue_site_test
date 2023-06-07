<template>
  <menu class="menu">
    <div class="container">
      <div class="div menu_icon">

        <svg viewBox="0 0 500 500" version="1.1" xmlns="http://www.w3.org/2000/svg"
             xmlns:xlink="http://www.w3.org/1999/xlink">
          <title>vue-logo</title>
          <g id="vue-js" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
            <path
                d="M306.580124,38 L250,136 L193.419876,38 L5,38 L250,462.357172 L495,38 L306.580124,38 Z M250.00052,424.916676 L37.4228873,56.7204672 L113.80758,56.7204672 L250,292.609311 L386.189695,56.7204672 L462.57628,56.7204672 L250.00052,424.916676 Z"
                id="Shape" fill="#000000" fill-rule="nonzero"></path>
          </g>
        </svg>
      </div>
      <div class="menu_content">
        <ul class="menu_list list">
          <a href="#/" class="list_link"><li class="list_item">Home</li></a>
          <a href="#/" class="list_link"><li class="list_item">Blog</li></a>
          <a href="#/" class="list_link"><li class="list_item">About us</li></a>
        </ul>
      </div>
    </div>
  </menu>
</template>

<script>
export default {}
</script>

<style scoped lang="scss">
.menu {
  display: flex;
  // .menu_icon
  &_icon svg{
    width: 50px;
    height: 50px;
  }

  // .menu_content
  &_content {
  }

  // .menu_list
  &_list {
  }
}

.div {
}

.list {
  // .list_link
  &_link {
  }

  // .list_item
  &_item {
  }
}
</style>