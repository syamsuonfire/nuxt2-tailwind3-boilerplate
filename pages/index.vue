<template>
  <Tutorial />
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      currentTab: "active",
      result: [],
    };
  },
  mounted() {
    console.log("Check Debugger"); // I'm text inside the component.
  },
};
</script>
