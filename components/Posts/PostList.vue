<template>
  <section class="post-list">
    <PostPreview
      id="1"
      thumbnail="https://res-3.cloudinary.com/fieldfisher/image/upload/c_lfill,g_auto/f_auto,q_auto/v1/sectors/technology/tech_neoncircuitboard_857021704_medium_lc5h05"
      title="test"
      previewText="Hi there ...."
    />
    <PostPreview
      id="2"
      thumbnail="https://res-3.cloudinary.com/fieldfisher/image/upload/c_lfill,g_auto/f_auto,q_auto/v1/sectors/technology/tech_neoncircuitboard_857021704_medium_lc5h05"
      title="test 2"
      previewText="Hi there 2...."
    />
    <PostPreview
      id="3"
      thumbnail="https://res-3.cloudinary.com/fieldfisher/image/upload/c_lfill,g_auto/f_auto,q_auto/v1/sectors/technology/tech_neoncircuitboard_857021704_medium_lc5h05"
      title="test 3"
      previewText="Hi there 3...."
    />
  </section>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview';
export default {
  components: {
    PostPreview
  }
};
</script>

<style scope>
.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
