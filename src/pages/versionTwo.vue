<template>
  <q-page class="bg-clr">
    <!-- nav bar -->
    <div class="gt-sm">
      <q-toolbar flat class="text-white bg-nav q-pa-sm q-py-md">
        <a href="#">
          <q-img width="130px" class="q-ml-md" src="~assets/logo.png"
        /></a>
        <q-space />
        <q-tabs shrink>
          <q-btn-dropdown flat label="Home">
            <q-list>
              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Home Default</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Home Video Bg</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Home Flex Slider</q-item-label></a
                  >
                </q-item-section>
              </q-item>
            </q-list>
          </q-btn-dropdown>
          <q-btn-dropdown flat label="Courses">
            <q-list>
              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Courses Grid</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Courses Layout</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Courses Details</q-item-label></a
                  >
                </q-item-section>
              </q-item>
            </q-list> </q-btn-dropdown
          ><q-btn-dropdown flat label="Pages">
            <q-list>
              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Menu</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>About</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Blog</q-item-label></a
                  >
                </q-item-section>
              </q-item>
            </q-list> </q-btn-dropdown
          ><q-btn-dropdown flat label="Extra">
            <q-list>
              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Cart Page</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Media Gallery</q-item-label></a
                  >
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section>
                  <a href="#" class="a-link"
                    ><q-item-label>Coming</q-item-label></a
                  >
                </q-item-section>
              </q-item>
            </q-list>
          </q-btn-dropdown>
          <a href="#" class="a-link text-white q-mr-md"
            ><q-icon size="25px" name="lock"
          /></a>
          <a href="#" class="a-link text-white"
            ><q-icon size="25px" name="search"
          /></a>
          <q-btn
            rounded
            color="warning"
            class="text-black q-px-lg q-mx-lg"
            label="Admission"
          />
        </q-tabs>
      </q-toolbar>
    </div>

    <div class="lt-md">
      <q-toolbar flat class="text-white bg-nav q-pa-sm q-py-md">
        <q-btn flat @click="drawer = !drawer" round dense icon="menu" />
        <a href="#">
          <q-img width="130px" class="q-ml-md" src="~assets/logo.png"
        /></a>
        <q-space />
        <q-tabs shrink>
          <q-btn
            rounded
            color="warning"
            class="text-black q-px-lg q-mx-lg"
            label="Admission"
          />
        </q-tabs>
      </q-toolbar>
    </div>
    <!-- nav bar -->

    <!-- Home Section -->
    <hr class="no-margin no-padding" />
    <div class="row container">
      <div class="col-md-3 col-sm-6 col-xs-6 q-gutter-sm text-grey-5 q-mt-lg">
        <div class="text-h6 text-weight-bold text-white">Home</div>
        <div class="text-body links">Home Default</div>
        <div class="text-body links">Home Video Bg</div>
        <div class="text-body links">Home Flexslider</div>
        <div class="text-body links">Home Layer Slider</div>
        <div class="text-body links">Home Full Screen</div>
        <div class="text-body links">Home Parallex Video</div>
        <div class="text-body links">With Cookie Bar</div>
      </div>

      <div class="col-md-3 col-sm-6 col-xs-6 q-gutter-sm text-grey-5 q-mt-lg">
        <div class="text-h6 text-weight-bold text-white">Courses</div>
        <div class="text-body links">Courses Grid</div>
        <div class="text-body links">Courses Grid Slider</div>
        <div class="text-body links">Courses List</div>
        <div class="text-body links">Courses List Side Bar</div>
        <div class="text-body links">Courses Details</div>
        <div class="text-body links">Courses Detail (Working)</div>
        <div class="text-body links">Admission Wizard</div>
      </div>

      <div class="col-md-3 col-sm-6 col-xs-6 q-gutter-sm text-grey-5 q-mt-lg">
        <div class="text-h6 text-weight-bold text-white">Pages</div>
        <div class="text-body links">About</div>
        <div class="text-body links">Menu 1</div>
        <div class="text-body links">Login</div>
        <div class="text-body links">Blog</div>
        <div class="text-body links">Register</div>
        <div class="text-body links">Contact</div>
        <div class="text-body links">404 Page</div>
        <div class="text-body links">Agenda Calender</div>
        <div class="text-body links">FAQ</div>
        <div class="text-body links">Help</div>
      </div>
      <div class="col-md-3 col-sm-6 col-xs-6 q-gutter-sm text-grey-5 q-mt-lg">
        <div class="text-h6 text-weight-bold text-white">Extra Pages</div>
        <div class="text-body links">Admin Dashboard</div>
        <div class="text-body links">Media Gallery</div>
        <div class="text-body links">Cart Page 1</div>
        <div class="text-body links">Cart Page 2</div>
        <div class="text-body links">Cart Page 3</div>
        <div class="text-body links">Responsive Pricing table</div>
        <div class="text-body links">Coming Soon</div>
        <div class="text-body links">Icon Pack 1</div>
        <div class="text-body links">Icon pack 2</div>
        <div class="text-body links">Icon pack 3</div>
        <div class="text-body links">Icon pack 4</div>
      </div>
      <q-footer class="bg-clr q-pb-md">
        <div class="text-center">
          <div class="text-h6 text-white text-weight-bold">Follow us</div>
          <div class="q-gutter-md">
            <q-icon
              class="links"
              color="grey-5"
              size="20px"
              name="fa-brands fa-facebook-f"
            />

            <q-icon
              class="links"
              color="grey-5"
              size="20px"
              name="fa-brands fa-twitter"
            />

            <q-icon
              class="links"
              color="grey-5"
              size="20px"
              name="fa-brands fa-google-plus-g"
            />

            <q-icon
              class="links"
              color="grey-5"
              size="20px"
              name="fa-brands fa-pinterest"
            />

            <q-icon
              class="links"
              color="grey-5"
              size="20px"
              name="fa-brands fa-instagram"
            />
          </div>
        </div>
      </q-footer>
    </div>

    <q-drawer
      style="background-image: linear-gradient(#3b0a5f, #c31432)"
      v-model="drawer"
      show-if-above
      :width="200"
      :breakpoint="500"
      behavior="mobile"
      bordered
    >
      <q-scroll-area class="fit">
        <q-list padding class="menu-list">
          <q-expansion-item
            expand-separator
            icon="home"
            label="Home"
            header-class="text-white"
          >
            <q-card style="background-image: linear-gradient(#3b0a5f, #c31432)">
              <q-list>
                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Home Default</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Home Video Bg</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Home Flex Slider</q-item-label></a
                    >
                  </q-item-section>
                </q-item>
              </q-list>
            </q-card>
          </q-expansion-item>
          <q-expansion-item
            expand-separator
            icon="school"
            label="Courses"
            header-class="text-white"
          >
            <q-card style="background-image: linear-gradient(#3b0a5f, #c31432)">
              <q-list>
                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Courses Grid</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Courses Layout</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Courses Details</q-item-label></a
                    >
                  </q-item-section>
                </q-item>
              </q-list>
            </q-card> </q-expansion-item
          ><q-expansion-item
            expand-separator
            icon="layers"
            label="Pages"
            header-class="text-white"
          >
            <q-card style="background-image: linear-gradient(#3b0a5f, #c31432)">
              <q-list>
                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Menu</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>About</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Blog</q-item-label></a
                    >
                  </q-item-section>
                </q-item>
              </q-list>
            </q-card> </q-expansion-item
          ><q-expansion-item
            expand-separator
            icon="expand_circle_down"
            label="Extra"
            header-class="text-white"
          >
            <q-card style="background-image: linear-gradient(#3b0a5f, #c31432)">
              <q-list>
                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Cart Page</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Media Gallery</q-item-label></a
                    >
                  </q-item-section>
                </q-item>

                <q-item>
                  <q-item-section>
                    <a href="#" class="a-link text-white"
                      ><q-item-label>Coming</q-item-label></a
                    >
                  </q-item-section>
                </q-item>
              </q-list>
            </q-card>
          </q-expansion-item>
        </q-list>
      </q-scroll-area>
    </q-drawer>
  </q-page>
</template>



<script>
import { ref } from "vue";

export default {
  setup() {
    return {
      drawer: ref(false),
    };
  },
};
</script>



<style lang="scss">
.bg-nav {
  background-image: linear-gradient(90deg, #3b0a5f, #c31432);
}
.a-link {
  text-decoration: none;
  color: black;
}
.bg-clr {
  background-image: linear-gradient(90deg, #3b0a5f, #c31432);
}
.links {
  cursor: pointer;
}
.links:hover {
  text-decoration: underline;
  color: white;
}

.container {
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}
@media (min-width: 768px) {
  .container {
    width: 750px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 970px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1170px;
  }
}
</style>
