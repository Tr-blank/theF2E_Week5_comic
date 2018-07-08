<template>
  <div id="app">
    <header>Comicomic</header>
    <main>
      <div class="page">
        <h1>My Hexschool</h1>
        <select name="" id=""><option value="">Chapter 1</option></select>
        <select name="" id=""><option value="">Page 09</option></select>
      </div>
      <picture>
        <img src="img/storyboard-1.png" alt="">
      </picture>
      <section>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        <div>
          <img src="img/storyboard-1.png" alt="">
        </div>
        
      </section>
    </main>
  </div>
</template>

<style lang="stylus">
@import 'stylus/normalize'
@import '../stylus/basic'
body
  background-color #f2f2f2
header 
  background-color #000
  font-size 36px
  color #50FF44
  line-height 74px
  text-align  center
main
  max-width 620px
  margin  0 auto
.page
  display flex
  padding 20px 0
h1
  font-size 20px
  font-weight: bold;
  padding-right: 10px;
select
  border: 2px solid #000;
  padding: 4px;
  &:nth-child(2)
    border-right 0

section
  display table
  overflow auto
  div
    display table-cell
    width 20%
    background-color #000000
    img
      opacity .9
</style>
