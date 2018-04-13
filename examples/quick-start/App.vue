<template>
  <div>
    <md-toolbar class="md-primary">
        <h1 class="md-title">Vue Material</h1>
    </md-toolbar>
    <md-content>
      let's start.
      <br>
      <md-icon class="md-size-2x">add</md-icon>
      <md-icon class="md-size-3x">thumb_up</md-icon>
      <md-icon>verified_user</md-icon>
      <md-icon class="md-size-5x">home</md-icon>
      <br>
    <md-avatar>
      <img src="http://images2015.cnblogs.com/blog/740839/201607/740839-20160730201459981-792406306.jpg" alt="Avatar">
    </md-avatar>

    <md-avatar class="md-avatar-icon">
      <md-icon>home</md-icon>
    </md-avatar>

    <md-avatar class="md-avatar-icon md-primary">
      <md-icon>folder</md-icon>
    </md-avatar>

    <md-avatar class="md-avatar-icon md-accent">
      <md-icon>favorite</md-icon>
    </md-avatar>
    </md-content>

  </div>    
</template>

<script>
export default {
  name: "App"
};
</script>

<style lang="scss">
.md-content {
  padding: 16px;
}
</style>
