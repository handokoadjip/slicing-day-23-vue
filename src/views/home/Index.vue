<template>
  <Content1Component />
  <Content2Component />
  <TestimoniComponent />
</template>

<script>
import Content1Component from "@/components/Content1Component.vue";
import Content2Component from "@/components/Content2Component.vue";
import TestimoniComponent from "@/components/TestimoniComponent.vue";

export default {
  name: "HomePage",
  components: {
    Content1Component,
    Content2Component,
    TestimoniComponent,
  },
  mounted() {
    document.title = "designschool.canva.com | Adam Widmanski"
  }
}
</script>
