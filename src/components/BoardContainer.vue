<template>
  <div class="board-container">
    <div class="board-wrapper board-list">
      <div class="list-content">
        <div class="list-header"></div>
        <div class="list-cards"></div>
        <div class="list-button"></div>
      </div>
    </div>
    <div class="board-wrapper">
      <a href="" @click.prevent="" class="board-generate">
        <v-icon small color="#fff">mdi-plus</v-icon>
        Add new card
      </a>
    </div>  
  </div>
</template>

<script>
export default {
  name: "BoardContainer"
}
</script>

<style lang="scss" scoped>
.board-generate {
  display: flex;
  align-items: center;
  width: 272px;
  height: 40px;
  margin: 4px;
  padding: 0 15px;
  font-size: 0.9rem;
  color: white;
  text-decoration: none;
  background-color: rgba(255,255,255,0.1);
  border-radius: 0.2rem;
  &:hover {
    background-color: rgba(255,255,255,0.2);
  }
  .v-icon {
    margin-right: 4px;
  }
}
.board-wrapper {
  position: relative;
  width: 272px;
  height: 100%;
  margin: 0 4px;
  box-sizing: border-box;
  display: inline-block;
  vertical-align: top;
  white-space: nowrap;
}
.list-content {
  background-color: #ebecf0;
  border-radius: 3px;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  max-height: 100%;
  position: relative;
  white-space: normal;
}
</style>