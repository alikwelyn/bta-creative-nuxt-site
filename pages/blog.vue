<template>
  <div>
    <section id="blog2" class="divider">
      <div class="container">
        <div class="row">
          <div class="col-md-12 aos-init aos-animate">
            <h1
              data-aos="fade-up"
              data-aos-duration="500"
              data-aos-once="true"
              class="aos-init aos-animate"
            >
              we have content
            </h1>
          </div>
        </div>
        <div class="section-content blog">
          <div class="row">
            <PostCard v-for="post in posts" :key="post.slug" :post="post" />
          </div>
          <div class="row">
            <div class="col d-flex justify-content-center">
              <div v-if="pageInfo.hasNextPage">
                <NuxtLink :to="{ query: { after: pageInfo.endCursor } }"
                  ><span>Next Page</span></NuxtLink
                >
              </div>
              <ul class="page-numbers">
                <li>
                  <span aria-current="page" class="page-numbers current"
                    >1</span
                  >
                </li>
                <li>
                  <a
                    class="page-numbers"
                    href="http://localhost/bta/bta-site/blog/page/2/"
                    >2</a
                  >
                </li>
                <li>
                  <a
                    class="page-numbers"
                    href="http://localhost/bta/bta-site/blog/page/3/"
                    >3</a
                  >
                </li>
                <li><span class="page-numbers dots">…</span></li>
                <li>
                  <a
                    class="page-numbers"
                    href="http://localhost/bta/bta-site/blog/page/14/"
                    >14</a
                  >
                </li>
                <li>
                  <a
                    class="next page-numbers"
                    href="http://localhost/bta/bta-site/blog/page/2/"
                    >→</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <Contact key=""/>
  </div>
</template>

<script>
import PostCard from "~/components/blog/PostCard.vue";
import Contact from "~/components/home/Contact.vue";

export default {
  name: "blog",
  components: {
    PostCard,
    Contact,
  },
  computed: {
    posts() {
      return [
        {
          title: "Test Post",
          slug: "test-post",
          date: "29 de abril de 2022",
          content: "<p>This is a test post</p>",
          excerpt: "<p>This is a test post</p>",
        },
      ];
    },
    pageInfo() {
      return {
        endCursor: "",
        hasNextPage: false,
        hasPreviousPage: false,
        startCursor: "",
      };
    },
  },
};
</script>

<style>
ul.page-numbers {
    list-style: none;
    margin: 0;
    padding-top: 5em;
}

.page-numbers:after {
    content: ".";
    display: block;
    clear: both;
    visibility: hidden;
    line-height: 0;
    height: 0;
}

ul.page-numbers li {
    display: block;
    float: left;
    margin: 0 4px 4px 0;
    text-align: center;
}

.page-numbers a,
.page-numbers span {
    line-height: 1.6em;
    display: block;
    padding: 0 15px;
    height: 25px;
    line-height: 25px;
    font-size: 16px;
    text-decoration: none;
    font-weight: 400;
    cursor: pointer;
    border: 1px solid #202c49;
    color: #202c49;
}

.page-numbers a span { padding: 0 }

.page-numbers a:hover,
.page-numbers.current,
.page-numbers.current:hover {
    color: #fb1787;
    background: #f7f7f7;
    text-decoration: none;
    border: 1px solid #fb1787;
}

.page-numbers:hover { text-decoration: none }

</style>