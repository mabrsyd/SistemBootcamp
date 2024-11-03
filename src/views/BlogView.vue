<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import FeaturedPost from '@/components/Blog/feature.vue'
import AllPost from '@/components/Blog/blogpost.vue'
import CategorySection from '@/components/Blog/categorysection.vue'
import JoinOurTeam from '@/components/Home/JoinOutTeam.vue'

</script>

<template>
  <MainLayout>
    <FeaturedPost>
    </FeaturedPost>
    <AllPost category="News" title="Some title" description="Some description" />
    <CategorySection>
    </CategorySection>
    <JoinOutTeam>
    </JoinOutTeam>
  </MainLayout>
</template>

<script lang="ts">
import {
  defineComponent
} from 'vue'
import JoinOutTeam from '@/components/Home/JoinOutTeam.vue'

export default defineComponent({
  name: 'BlogLayout'
})

</script>

<style scoped>

</style>