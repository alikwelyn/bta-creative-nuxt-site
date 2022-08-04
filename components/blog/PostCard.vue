<template>
  <div
    id="blog-cont"
    class="col-md-4 aos-init aos-animate"
    data-aos="fade-right"
    data-aos-duration="1000"
    data-aos-once="true"
  >
    <article class="post clearfix">
      <div class="entry-header">
        <div class="post-thumb thumb">
          <img
            width="360"
            height="230"
            src="http://localhost/bta/bta-site/wp-content/uploads/2022/04/04-29-blog-dia-maes-v1-360x230.jpg"
            class="img-responsive img-fullwidth wp-post-image"
            alt="Dia das Mães: dicas de marketing digital"
            loading="lazy"
          />
        </div>
      </div>
      <div class="entry-content">
        <div class="entry-meta media">
          <div class="media-body">
            <h2>
              <NuxtLink :to="{ name: 'slug', params: { slug: post.slug } }">{{
                post.title
              }}</NuxtLink>
            </h2>
            <!-- eslint-disable-next-line vue/no-v-html -->
            <p v-html="post.date"></p>
          </div>
        </div>
        <p v-html="post.excerpt"></p>
        <div class="leia-mais">
          <NuxtLink :to="{ name: 'slug', params: { slug: post.slug } }">
            ver matéria completa
          </NuxtLink>
        </div>
        <!-- eslint-disable-next-line vue/no-v-html -->
        <div class="clearfix"></div>
      </div>
    </article>
  </div>
</template>

<script>
export default {
  props: ["post"],
};
</script>

<style>
</style>