<template>
  <div class="about-card">
    <div class="card-title">
      <img height="200px" src="../assets/jedavatar.png" alt="avatar" class="avatar" />
      <div class="title-text-content">
        <p>About me</p>
        <h2>Jed Delmiguez</h2>
      </div>
    </div>
    <div class="card-content">
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
        Aliquam tenetur itaque ratione dolorum veritatis facere,
        fugiat nobis nihil! Blanditiis tempore harum totam alias
        minus ab quibusdam eum et dolore, unde omnis dicta ullam
        veritatis impedit facere natus explicabo officia fugit dolor
        odit. Reiciendis obcaecati libero itaque enim aperiam ea quasi?
      </p>
      <table width="100%">
        <tr>
          <th>Requirement</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>Photoshop, Figma, Canva, Adobe XD</td>
        </tr>
        <tr>
          <td>Front-end</td>
          <td>React.js, Vue.js, Nuxt.js, HTML, CSS, JavaScript</td>
        </tr>
        <tr>
          <td>Back-end</td>
          <td>Node.js, Express.js, Mongo, GraphQL</td>
        </tr>
        <tr>
          <td>ML</td>
          <td>ML5, TensorFlow, Algorithm Design</td>
        </tr>
        <tr>
          <td>Shop</td>
          <td>Stripe, PayFast, E-commerce, CMS</td>
        </tr>
      </table>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
        Aliquam tenetur itaque ratione dolorum veritatis facere,
        fugiat nobis nihil! Blanditiis tempore harum totam alias
        minus ab quibusdam eum et dolore, unde omnis dicta ullam
        veritatis impedit facere natus explicabo officia fugit dolor
        odit. Reiciendis obcaecati libero itaque enim aperiam ea quasi?
      </p>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit.
        Aliquam tenetur itaque ratione dolorum veritatis facere,
        fugiat nobis nihil! Blanditiis tempore harum totam alias
        minus ab quibusdam eum et dolore, unde omnis dicta ullam
        veritatis impedit facere natus explicabo officia fugit dolor
        odit. Reiciendis obcaecati libero itaque enim aperiam ea quasi?
      </p>
    </div>
  </div>
</template>

<style lang="sass" scoped>
.about-card
  background: #333
  padding: 3em
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content
    p
      margin-bottom: 0
      color: rgb(210, 210, 210)
    h2
      margin-top: 0

.card-content p 
  line-height: 1.5
  margin: 30px auto

table
  border-spacing: 0px
  margin: 50px auto
  tr th, tr td
    border: 1px solid white
    border-top: none
    padding: 10px
    text-align: center
    &:first-of-type
      border-left: none
    &:nth-of-type(2)
      border-right: none
</style>