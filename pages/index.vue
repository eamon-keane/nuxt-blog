<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news</h1>
    </section>
    <section class="featured-posts">
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
  </div>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview';
export default {
  components: {
    PostPreview
  }
};
</script>

<style scoped>
.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-position: center;
  background-size: cover;
}

.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}

.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>
