<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import HeaderBlog from '@/components/BlogPost/headerblog.vue'
import BlogContent from '@/components/BlogPost/blogcontent.vue'
import blogpostsection from '@/components/Blog/blogpostsection.vue'
</script>

<template>
  <MainLayout>
    <HeaderBlog>
    </HeaderBlog>
    <BlogContent/>
    <Blogpost>
    </Blogpost>
  </MainLayout>
</template>

<script lang="ts">
import {
  defineComponent
} from 'vue'
import Blogpostsection from '@/components/BlogPost/blogpostsection.vue';

export default defineComponent({
  name: 'BlogLayout'
})

</script>

<style scoped>

</style>