<template>
  <div id="app">
    <!--  banner   -->
    <div
      id="displayBanner"
      class="header-banner"
      style="background-color: black"
    >
      <div
        id="easycontent_container_88"
        class="easycontent_container full_container block"
      >
        <div class="container">
          <div class="row">
            <div class="col-12">
              <aside id="easycontent_88" class="easycontent_88 easycontent">
                <div class="style_content block_content">
                  <div
                    class="easy_brother_block text-2 text-md-0"
                    style="color: white"
                  >
                    <p>
                      Comprando acumulas puntos que puedes redimir en tus juegos
                      favoritos
                    </p>
                  </div>
                </div>
              </aside>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--  nav primmary with logo   -->
    <div>
      <nav class="navbar navbar-light bg-light">
        <div class="container-fluid">
          <a class="navbar-brand"></a>
          <form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
              autocomplete="on"
            />
            <button class="btn btn-outline-success" type="submit">
              Search
            </button>
          </form>
        </div>
      </nav>
      <a href="http://localhost:8080/?#/">
        <img src="@/assets/logo.png" alt="logo" />
      </a>
    </div>
    <!--  nav sub functional  -->
    <div id="nav" class="color: White" style="background-color: black">
      | <router-link to="/">| Principal </router-link>
      <router-link to="/Carrito">| Carrito de Compras </router-link>
      <router-link to="/Usuario">| Usuario </router-link>
      <router-link to="/Pago">| Pago </router-link>
      <router-link to="/About">| Contactanos |</router-link>
    </div>
    <!--  Views components   -->
    <router-view />
    <!--  footer principal   -->
    <footer>
      <section id="footer-primary">
        <div class="wide_container">
          <div class="container">
            <div class="row footer_first_level_row">
              <div id="stacked_footer_column_2" class="col-lg-4">
                <section
                  id="easycontent_82"
                  class="easycontent footer_block block"
                >
                  <div class="title_block">
                    <div class="title_block_inner">Contáctanos</div>
                    <div class="opener">
                      <i class="fto-plus-2 plus_sign"></i
                      ><i class="fto-minus minus_sign"></i>
                    </div>
                  </div>
                  <div class="style_content footer_block_content">
                    <!-- first module info -->
                    <div id="steasy_column_469" class="row">
                      <div
                        id="steasy_column_470"
                        class="col-lg-12 col-sm-12 col-12 steasy_column"
                      >
                        <div class="steasy_element_block">
                          <div class="row">
                            <div
                              id="steasy_element_646"
                              class="col-lg-12 steasy_element_1"
                            >
                              <div class="steasy_element_item text-0">
                                <div
                                  class="
                                    easy_icon_with_text_4_1
                                    flex_container flex_start
                                  "
                                >
                                  <div class="flex_child">
                                    <div>#unplugandplaymedellin</div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </section>
              </div>
              <!-- second module info -->
              <div id="stacked_footer_column_3" class="col-lg-2">
                <section
                  class="stlinkgroups_links_footer footer_block block"
                >
                  <div class="title_block">
                    <div class="title_block_inner">Mi Cuenta</div>
                  </div>
                  <ul class="footer_block_content bullet custom_links_list">
                    <li>
                      Dashboard
                    </li>
                    <li>
                      Mis Ordenes
                    </li>
                    <li>
                      Mis Direcciones
                    </li>
                  </ul>
                </section>
              </div>
              <!-- third module info -->
              <div id="stacked_footer_column_4" class="col-lg-2">
                <section
                  id="multilink_13"
                  class="stlinkgroups_links_footer footer_block block"
                >
                  <div class="title_block">
                    <div class="title_block_inner">Soporte</div>
                  </div>
                  <ul class="footer_block_content bullet custom_links_list">
                    <li>
                      Nuestras Tiendas
                    </li>
                    <li>
                      Contáctanos
                    </li>
                    <li>
                      Mapa del Sitio
                    </li>
                  </ul>
                </section>
              </div>
              <!-- fourth module info -->
              <div id="stacked_footer_column_5" class="col-lg-4">
                <section
                  id="st_news_letter_5"
                  class="st_news_letter_5 footer_block block"
                >
                  <div class="title_block flex_container title_align_0">
                    <div class="flex_child title_flex_left"></div>
                    <div class="title_block_inner">Boletín de Noticias.</div>
                    <div class="flex_child title_flex_right"></div>
                  </div>
                  <div class="footer_block_content text-1 text-md-2">
                    <div class="st_news_letter_box">
                      <div class="news_letter_0">
                        <div
                          class="
                            st_news_letter_content
                            style_content
                            flex_child_md
                          "
                        >
                          <p class="m-b-1">
                            Suscríbete gratis hoy y se el primero en enterarte
                            de nuevas actualizaciones, descuentos y promociones.
                          </p>
                        </div>
                        <form action="" class="st_news_letter_form flex_child">
                          <div class="st_news_letter_form_inner">
                            <div
                              class="
                                input-group
                                round_item
                                js-parent-focus
                                input-group-with-border
                              "
                            >
                              <input
                                class="
                                  form-control
                                  st_news_letter_input
                                  js-child-focus
                                "
                                type="text"
                                name="email"
                                value=""
                                placeholder="Correo Electronico IUSH"
                              />
                              <span class="input-group-btn">
                                <button
                                  type="submit"
                                  name="submitStNewsletter"
                                  class="
                                    btn btn-less-padding
                                    st_news_letter_submit
                                    link_color
                                  "
                                >
                                </button>
                              </span>
                            </div>
                          </div>
                          <input type="hidden" name="action" value="0" />
                          <input
                            type="hidden"
                            name="submitNewsletter"
                            value="1"
                          />
                        </form>
                      </div>
                    </div>
                  </div>
                </section>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- banner footer end -->
      <div
        id="footer-bottom"
        class="footer_bottom_center"
        style="background-color: black"
      >
        <div class="wide_container">
          <div class="container">
            <div class="row">
              <div class="col-12 col-sm-12 clearfix">
                <aside id="footer_bottom_left text-center">
                  <img
                    class="img-fluid"
                    src="https://www.unplugandplay.co/upload/stthemeeditor/4ce12708311ffc30cff049e94db6cd12.png"
                    alt="Formas de Pago"
                  />
                </aside>
                <aside id="footer_bottom_center" style="color: white">
                  © 2021 Vue Project. All right Reserved IUSH
                </aside>
              </div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: white;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

#footer-primary {
  background-color: #bab9b8;
}
</style>

