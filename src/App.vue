<template>
  <div id="app">
    <CalendarWeek />
    <CalendarEntry />
    <strong>Welcome, this is Weekly Todo App!</strong>
    <p>It is a simple application, because most human forget alot in general, and the common todo apps are basiclly deppend on monthly prespective. So I assumed the shorter list will be the better for achieving most of theme.</p>
  </div>
</template>

<script>
import CalendarWeek from "@/components/CalendarWeek";
import CalendarEntry from "@/components/CalendarEntry";

export default {
  name: "app",
  components: {
    CalendarWeek,
    CalendarEntry
  }
};
</script>

<style lang="scss">
html,
body {
  height: 100%;
}
</style>

<style lang="scss" scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background-color: #6e6e6e;
  height: inherit;

  strong,
  p {
    margin: 0 auto;
    padding: 10px;
    color: #cccccc;
  }
  strong {
    margin-top: 10px;
    display: block;
  }
}
</style>
