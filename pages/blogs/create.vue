<template>
  <div>
    <div class="content">
      <div class="container">
        <div class="row">
          <div class="col-lg-3">
            <app-menu></app-menu>
          </div>
          <div class="col-lg-9">
            <h3 class="mg3">New Blogs</h3>
            <blog-create-edit></blog-create-edit>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AppMenu from '@/components/AppMenu'
import BlogCreateEdit from '@/components/BlogCreateEdit'

export default {
  components: { BlogCreateEdit }
}
</script>