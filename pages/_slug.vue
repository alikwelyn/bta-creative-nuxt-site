<template>
  <div>
    <section id="blog-single" class="divider">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-6">
            <div class="blog-single">
              <div class="thumb">
                <div class="blog-category category-absolute">
                  <div class="category">
                    <div class="btn btn-category" alt="Adwords">Adwords</div>
                  </div>
                </div>
              </div>
              <div class="blog-details clearfix">
                <div>
                  <h3>
                    {{ post.title }}
                    <!-- eslint-disable-next-line vue/no-v-html -->
                  </h3>
                  <p>29 de abril de 2022</p>
                </div>
                <div>
                  <ul class="styled-icons">
                    <li>
                      <a
                        href="https://www.facebook.com/sharer/sharer.php?u=http://localhost/bta/bta-site/dia-das-maes-dicas-de-marketing-digital/"
                        target="_new"
                        alt="Compartilhar no Facebook"
                        ><i class="fa fa-facebook"></i
                      ></a>
                    </li>
                    <li>
                      <a
                        href="https://www.linkedin.com/shareArticle?mini=true&amp;url=http://localhost/bta/bta-site/dia-das-maes-dicas-de-marketing-digital/"
                        target="_new"
                        alt="Compartilhar no Linkedin"
                        ><i class="fa fa-linkedin" target="_new"></i
                      ></a>
                    </li>
                    <li>
                      <a
                        href="https://api.whatsapp.com/send?text=Dia das Mães: dicas de marketing digital para a sua empresa - http://localhost/bta/bta-site/dia-das-maes-dicas-de-marketing-digital/"
                        target="_new"
                        alt="Compartilhar no Whatsapp"
                        ><i class="fa fa-whatsapp" target="_new"></i
                      ></a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <div id="post-thumb" class="col-md-6">
            <div>
              <img
                width="730"
                height="400"
                src="http://localhost/bta/bta-site/wp-content/uploads/2022/04/04-29-blog-dia-maes-v1-730x400.jpg"
                class="img-responsive img-fullwidth wp-post-image"
                alt="Dia das Mães: dicas de marketing digital"
              />
            </div>
          </div>
        </div>
      </div>
      <div id="blog-more" class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="blog-post">
              <p v-html="post.content"></p>
              <div class="like-content">
                <div class="row">
                  <div class="col-md-12">
                    <h1>
                      Curtiu o nosso conteúdo?<br />Então compartilha praquela
                      pessoa que também pode gostar.
                    </h1>
                  </div>
                  <div class="col-md-12">
                    <div>
                      <ul class="styled-icons">
                        <li>
                          <a
                            href="https://www.facebook.com/sharer/sharer.php?u=http%3A%2F%2Flocalhost%2Fbta%2Fbta-site%2Fdia-das-maes-dicas-de-marketing-digital%2F"
                            target="_blank"
                            alt="Compartilhar no Facebook"
                            ><i class="fa fa-facebook"></i
                          ></a>
                        </li>
                        <li>
                          <a
                            href="https://www.linkedin.com/shareArticle?mini=true&amp;url=http%3A%2F%2Flocalhost%2Fbta%2Fbta-site%2Fdia-das-maes-dicas-de-marketing-digital%2F&amp;title=Dia%20das%20Mães:%20dicas%20de%20marketing%20digital%20para%20a%20sua%20empresa"
                            target="_blank"
                            alt="Compartilhar no Facebook"
                            ><i class="fa fa-linkedin"></i
                          ></a>
                        </li>
                        <li>
                          <a
                            href="https://api.whatsapp.com/send?text=Dia%20das%20Mães:%20dicas%20de%20marketing%20digital%20para%20a%20sua%20empresa - http%3A%2F%2Flocalhost%2Fbta%2Fbta-site%2Fdia-das-maes-dicas-de-marketing-digital%2F"
                            target="_blank"
                            alt="Compartilhar no Facebook"
                            ><i class="fa fa-whatsapp"></i
                          ></a>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>
              <hr />
            </div>
          </div>
        </div>
        <div class="related-title">
          <div class="row">
            <div class="col-md-12">
              <h1>separamos algumas matérias<br />que podem te interessar:</h1>
            </div>
          </div>
        </div>
        <div class="row">
          <div
            class="col-md-4 aos-init"
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
                    src="http://localhost/bta/bta-site/wp-content/uploads/2022/04/04-05-blog-7-erros-seo-v1-360x230.jpg"
                    class="img-responsive img-fullwidth wp-post-image"
                    alt="busca-do-google-no-computador"
                    loading="lazy"
                  />
                </div>
              </div>
              <div class="entry-content">
                <div class="entry-meta media">
                  <div class="media-body">
                    <h2>
                      <a
                        href="http://localhost/bta/bta-site/maiores-erros-de-seo/"
                        >Meu blog não aparece no Googl…</a
                      >
                    </h2>
                    <p>5 de abril de 2022</p>
                  </div>
                </div>
                <p></p>
                <p>
                  Se a sua empresa tem um blog, você já deve ter se perguntado:
                  por que ele não aparece no Google? Essa é uma dúvida bem
                  comum, afinal, aparecer…
                </p>
                <p></p>
                <div class="leia-mais">
                  <a href="http://localhost/bta/bta-site/maiores-erros-de-seo/"
                    >ver matéria completa</a
                  >
                </div>
                <div class="clearfix"></div>
              </div>
            </article>
          </div>

          <div
            class="col-md-4 aos-init"
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
                    src="http://localhost/bta/bta-site/wp-content/uploads/2022/03/03-09-blog-nano-v1-360x230.jpg"
                    class="img-responsive img-fullwidth wp-post-image"
                    alt="Mulher com celular na mão em foto do Instagram"
                    loading="lazy"
                  />
                </div>
              </div>
              <div class="entry-content">
                <div class="entry-meta media">
                  <div class="media-body">
                    <h2>
                      <a
                        href="http://localhost/bta/bta-site/o-que-sao-nanoinfluenciadores/"
                        >Nanoinfluenciadores: os novos …</a
                      >
                    </h2>
                    <p>9 de março de 2022</p>
                  </div>
                </div>
                <p></p>
                <p>
                  Recentemente, a gente mostrou no nosso Instagram quanto custa
                  fazer um único post nos maiores perfis do Insta, como o do
                  Neymar, da cantora Ariana Grande ou do…
                </p>
                <p></p>
                <div class="leia-mais">
                  <a
                    href="http://localhost/bta/bta-site/o-que-sao-nanoinfluenciadores/"
                    >ver matéria completa</a
                  >
                </div>
                <div class="clearfix"></div>
              </div>
            </article>
          </div>

          <div
            class="col-md-4 aos-init"
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
                    src="http://localhost/bta/bta-site/wp-content/uploads/2022/01/01-27-blog-metaverso-v2-360x230.jpg"
                    class="img-responsive img-fullwidth wp-post-image"
                    alt="óculos de realidade virtual escrito metaverso nele"
                    loading="lazy"
                  />
                </div>
              </div>
              <div class="entry-content">
                <div class="entry-meta media">
                  <div class="media-body">
                    <h2>
                      <a
                        href="http://localhost/bta/bta-site/metaverso-o-futuro-do-ecommerce/"
                        >Metaverso: o futuro da experi�…</a
                      >
                    </h2>
                    <p>7 de fevereiro de 2022</p>
                  </div>
                </div>
                <p></p>
                <p>
                  Enquanto algumas empresas deram seus primeiros passos no
                  e-commerce durante a pandemia, já temos empresas se
                  aventurando no utópico metaverso, tido como o futuro das
                  relações humanas e…
                </p>
                <p></p>
                <div class="leia-mais">
                  <a
                    href="http://localhost/bta/bta-site/metaverso-o-futuro-do-ecommerce/"
                    >ver matéria completa</a
                  >
                </div>
                <div class="clearfix"></div>
              </div>
            </article>
          </div>
        </div>
      </div>
    </section>
    <Contact />
  </div>
</template>

<script>
import Contact from "~/components/home/Contact.vue";

export default {
  components: {
    Contact,
  },
  computed: {
    post() {
      return {
        title: "Test Post",
        slug: "test-post",
        content: "<p>This is a test post</p>",
        excerpt: "<p>This is a test post</p>",
      };
    },
  },
};
</script>

<style>
</style>