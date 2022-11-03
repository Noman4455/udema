<template>
  <!-- Nav Bar Section  -->
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
                <a href="#" class="a-link"><q-item-label>Menu</q-item-label></a>
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
                <a href="#" class="a-link"><q-item-label>Blog</q-item-label></a>
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
  <!-- Nav Bar Section  -->

  <!-- Home Section -->
  <div class="bg-img gt-sm">
    <div class="text-center q-pt-xl text-white q-gutter-md">
      <div class="text-h3 q-mt-xl q-pt-xl text-weight-bold">
        WHAT WOULD YOU LEARN?
      </div>
      <div class="text-h5 text-weight-bold">
        Increase your expertise in business, technology and personal development
      </div>
      <div class="flex flex-center row">
        <q-input
          outlined
          dark
          dense
          placeholder="Ex. Medical, Architecture"
          style="width: 600px"
        />
        <q-btn style="background-color: #3b0a5f" label="Search" />
      </div>
    </div>
  </div>
  <div class="bg-img lt-md">
    <div class="text-center q-pt-lg text-white q-gutter-md">
      <div class="text-h4 q-mt-lg q-pt-lg text-weight-bold">
        WHAT WOULD YOU LEARN?
      </div>
      <div class="text-h6 q-mx-lg text-weight-bold">
        Increase your expertise in business, technology and personal development
      </div>
      <div class="flex flex-center row">
        <q-input
          outlined
          dark
          dense
          placeholder="Ex. Medical, Architecture"
          style="width: 250px"
        />
        <q-btn style="background-color: #3b0a5f" label="Search" />
      </div>
    </div>
  </div>

  <div class="flex row q-mx-auto col bg-dark gt-sm">
    <div class="col-3 text-center q-py-md">
      <q-icon name="school" color="white" size="40px" />
      <div class="text-h6 text-yellow">+200 Courses</div>
      <div class="text-sub-title1 text-bold text-white">
        Explore a verity of Fresh Topic
      </div>
    </div>
    <div class="col-3 text-center q-py-md">
      <q-icon name="emoji_events" color="white" size="40px" />
      <div class="text-h6 text-yellow">Expert Teachers</div>
      <div class="text-sub-title1 text-bold text-white">
        Find the right instructor for you
      </div>
    </div>
    <div class="col-3 text-center q-py-md">
      <q-icon name="crisis_alert" color="white" size="40px" />
      <div class="text-h6 text-yellow">Focus on Target</div>
      <div class="text-sub-title1 text-bold text-white">
        Increase your personal expertise
      </div>
    </div>
    <div class="col-3 text-center q-py-md">
      <q-icon name="card_membership" color="white" size="40px" />
      <div class="text-h6 text-yellow">Best Certificate</div>
      <div class="text-sub-title1 text-bold text-white">
        Explore a verity of Fresh Topic
      </div>
    </div>
  </div>
  <div class="flex row q-mx-auto q-py-xl bg-dark lt-md">
    <div class="col-12 text-center q-py-md">
      <q-icon name="school" color="white" size="40px" />
      <div class="text-body1 text-bold text-warning">+200 Courses</div>
      <div class="text-subtitle2 text-bold text-white">
        Explore a verity of Fresh Topic
      </div>
    </div>
    <div class="col-12 text-center q-py-md">
      <q-icon name="emoji_events" color="white" size="40px" />
      <div class="text-body1 text-bold text-warning">Expert Teachers</div>
      <div class="text-subtitle2 text-bold text-white">
        Find the right instructor for you
      </div>
    </div>
    <div class="col-12 text-center q-py-md">
      <q-icon name="crisis_alert" color="white" size="40px" />
      <div class="text-body1 text-bold text-warning">Focus on Target</div>
      <div class="text-subtitle2 text-bold text-white">
        Increase your personal expertise
      </div>
    </div>
  </div>
  <!-- Home Section -->

  <!-- 2nd Page Carousal -->
  <div class="text-purple-2 text-center text-bold">
    <p class="q-pt-xl">
      _______<span style="color: #3b0a5f">_________________</span>_______
    </p>
  </div>
  <div class="q-mb-xl gt-sm">
    <div class="text-h4 text-center q-pt-xl text-bold">News & Events</div>
    <div class="text-h6 text-center">
      Cum doctus civibus efficiantur in imperdiet deterruisset.
    </div>
  </div>
  <div class="q-mb-xl lt-md">
    <div class="text-h5 text-center q-pt-xl text-bold">News & Events</div>
    <div class="text-body1 text-bold text-center">
      Cum doctus civibus efficiantur in imperdiet deterruisset.
    </div>
  </div>
  <Carousel class="gt-sm" :itemsToShow="3" :wrapAround="true" :transition="500">
    <Slide v-for="item in list" :key="item">
      <div class="">
        <q-card class="my-card q-mb-xl q-px-md" style="width: 400px">
          <img :src="item.src" />
          <q-card-section class="text-left">
            <div class="text-subtitle2 text-grey-7">Categories</div>
            <div class="text-h6">Persuis delient has cu</div>
            <div class="text-subtitle2">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis,
              dignissimos.
            </div>
            <div class="q-gutter-y-md column q-my-xs">
              <q-rating
                v-model="ratingModel"
                size="20px"
                color="orange"
                readonly
              />
            </div>
            <hr />
          </q-card-section>
          <div class="text-left">
            <q-card-section>
              <q-icon name="schedule" /> 1h 30min
              <span class="q-ml-sm"
                ><q-icon name="thumb_up_off_alt" size="22px" /> 890</span
              >
              <q-btn
                class="float-right"
                rounded
                label="Enroll Now"
                outline
                color="purple"
                size="10px"
              />
            </q-card-section>
          </div>
        </q-card>
      </div>
    </Slide>
  </Carousel>
  <Carousel class="lt-md" :itemsToShow="1" :wrapAround="true" :transition="500">
    <Slide v-for="item in list" :key="item">
      <div class="">
        <q-card class="my-card q-mb-xl q-px-md" style="width: 300px">
          <img :src="item.src" />
          <q-card-section class="text-left">
            <div class="text-subtitle2 text-grey-7">Categories</div>
            <div class="text-h6">Persuis delient has cu</div>
            <div class="text-subtitle2">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis,
              dignissimos.
            </div>
            <div class="q-gutter-y-md column q-my-xs">
              <q-rating
                v-model="ratingModel"
                size="20px"
                color="orange"
                readonly
              />
            </div>
            <hr />
          </q-card-section>
          <div class="text-left">
            <q-card-section>
              <q-icon name="schedule" /> 1h 30min
              <span class="q-ml-sm"
                ><q-icon name="thumb_up_off_alt" size="22px" /> 890</span
              >
              <q-btn
                class="float-right"
                rounded
                label="Enroll Now"
                outline
                color="purple"
                size="10px"
              />
            </q-card-section>
          </div>
        </q-card>
      </div>
    </Slide>
  </Carousel>

  <!-- 2nd Page Carousal -->

  <!-- 3rd Page Courses -->
  <div class="bg-grey-2">
    <div class="text-purple-2 text-center text-bold q-py-lg">
      <p class="q-pt-xl">
        _______<span style="color: #3b0a5f">_________________</span>_______
      </p>
    </div>
    <div class="gt-sm">
      <div class="text-h4 text-center text-bold">Udema Categories Courses</div>
      <div class="text-h6 text-center">
        Cum doctus civibus efficiantur in imperdiet deterruisset.
      </div>
    </div>
    <div class="lt-md">
      <div class="text-h5 text-center text-bold">Udema Categories Courses</div>
      <div class="text-body1 text-bold text-center">
        Cum doctus civibus efficiantur in imperdiet deterruisset.
      </div>
    </div>

    <div class="row container q-py-xl q-col-gutter-y-lg lt-md">
      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c1.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Arts & Humanities</div>
            </div>
          </q-img>
        </q-card>
      </div>
      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c2.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Engineering</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c3.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Architecture</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c4.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Science & Biology</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c5.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Law & Criminology</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c6.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Medical</div>
            </div>
          </q-img>
        </q-card>
      </div>
    </div>
    <div class="row container q-py-xl q-col-gutter-lg gt-sm">
      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c1.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Arts & Humanities</div>
            </div>
          </q-img>
        </q-card>
      </div>
      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c2.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Engineering</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c3.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Architecture</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c4.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Science & Biology</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c5.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Law & Criminology</div>
            </div>
          </q-img>
        </q-card>
      </div>

      <div class="col-md-4 col-sm-6 col-xs-12">
        <q-card class="my-card">
          <q-img class="course-img" src="~assets/c6.jpg">
            <div class="absolute-bottom">
              <div class="text-body">
                <q-icon
                  size="18px"
                  class="q-mr-sm"
                  name="fa-regular fa-copy"
                />15 Program
              </div>
              <div class="text-body1 text-bold">Medical</div>
            </div>
          </q-img>
        </q-card>
      </div>
    </div>
  </div>

  <!-- 3rd Page Courses -->

  <!-- News Page -->
  <div class="text-purple-2 text-center text-bold q-pb-xl">
    <p class="q-pt-xl">
      _______<span style="color: #3b0a5f">_________________</span>_______
    </p>
  </div>
  <div class="q-mb-xl gt-sm">
    <div class="text-h4 text-center text-bold">News & Events</div>
    <div class="text-h6 text-center">
      Cum doctus civibus efficiantur in imperdiet deterruisset.
    </div>
  </div>
  <div class="q-mb-xl lt-md">
    <div class="text-h5 text-center text-bold">News & Events</div>
    <div class="text-body1 text-bold text-center">
      Cum doctus civibus efficiantur in imperdiet deterruisset.
    </div>
  </div>
  <div class="row container q-col-gutter-lg gt-sm">
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n1.jpg">
            <span
              class="absolute-top-right bg-orange text-black text-bold q-px-sm"
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-h6 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-body text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n2.jpg">
            <span
              class="absolute-top-right text-black bg-orange text-bold q-px-sm"
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-h6 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-body text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n3.jpg">
            <span
              class="absolute-top-right text-black bg-orange text-bold q-px-sm"
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-h6 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-body text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n4.jpg">
            <span
              class="
                absolute-top-right
                text-black text-black
                bg-orange
                text-bold
                q-px-sm
              "
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-h6 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-body text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
  </div>
  <div class="row container q-col-gutter-y-md lt-md">
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n1.jpg">
            <span
              class="absolute-top-right bg-orange text-black text-bold q-px-sm"
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-body1 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n2.jpg">
            <span
              class="absolute-top-right text-black bg-orange text-bold q-px-sm"
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-body1 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n3.jpg">
            <span
              class="absolute-top-right text-black bg-orange text-bold q-px-sm"
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-body1 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
    <div class="col-xs-12 col-md-5">
      <q-card flat class="my-news-card">
        <q-card-section horizontal>
          <q-img class="news-img" width="200px" src="~assets/n4.jpg">
            <span
              class="
                absolute-top-right
                text-black text-black
                bg-orange
                text-bold
                q-px-sm
              "
              >28 <br />
              Oct</span
            ></q-img
          >

          <q-card-section>
            <div class="text-body text-grey">Mark Twain - 28.10.2022</div>
            <div class="text-body1 text-bold">Pri Oportere Scribenture eu</div>
            <div class="text-black">
              Cum doctus civibus efficiantur in imperdiet Cum doctus.
            </div>
          </q-card-section>
        </q-card-section>

        <q-separator />
      </q-card>
    </div>
  </div>
  <q-card flat class="my-card q-mb-xl gt-sm">
    <q-card-actions align="right">
      <q-btn class="q-mr-xl" rounded color="primary" label="View All News" />
    </q-card-actions>
  </q-card>
  <q-card flat class="my-card q-ml-xl q-mt-md q-mb-xl lt-md">
    <q-card-actions align="center">
      <q-btn class="q-mr-xl" rounded color="primary" label="View All News" />
    </q-card-actions>
  </q-card>
  <!-- News Page -->

  <!-- Paralex image Section -->
  <div>
    <q-card class="">
      <q-parallax src="~assets/bg-slider.jpg" :height="600">
        <q-card style="width: 400px" class="bg-dark text-white q-pa-lg gt-sm">
          <q-card-section>
            <div class="text-h5">Enjoy a great students community</div>
            <div class="text-body">
              Ius cu tamquam persequeris, eu veniam apeirian platonem qui, id
              aliquip voluptatibus pri. Ei mea primis ornatus disputationi.
              Menandri erroribus cu per, duo solet congue ut.
            </div>
          </q-card-section>
          <q-card-actions
            ><q-btn rounded color="primary" label="Read More" />
          </q-card-actions>
        </q-card>
        <q-card style="width: 350px" class="bg-dark text-white q-pa-lg lt-md">
          <q-card-section>
            <div class="text-h5">Enjoy a great students community</div>
            <div class="text-body">
              Ius cu tamquam persequeris, eu veniam apeirian platonem qui, id
              aliquip voluptatibus pri. Ei mea primis ornatus disputationi.
              Menandri erroribus cu per, duo solet congue ut.
            </div>
          </q-card-section>
          <q-card-actions
            ><q-btn rounded color="primary" label="Read More" />
          </q-card-actions>
        </q-card>
      </q-parallax>
    </q-card>
  </div>
  <!-- Paralex image Section -->

  <!-- Footer section -->
  <footer class="gt-sm">
    <div style="background-color: #0f1921" class="row q-pa-xl">
      <div class="col-xs-12 col-md-6 col-lg-5">
        <q-img src="~assets/logo.png" class="q-mt-xl q-ml-xl" width="160px" />
        <p class="q-mx-xl q-my-lg text-grey-5">
          Mea nibh meis philosophia eu. Duis legimus efficiantur ea sea. Id
          placerat tacimates definitionem sea, prima quidam vim no. Duo nobis
          persecuti cu. Nihil facilisi indoctum an vix, ut delectus expetendis
          vis.
        </p>
      </div>
      <div class="col-xs-8 col-md-4 col-lg-1 q-ma-xl">
        <div class="text-h6 q-mt-xl text-white">Usefull Links</div>
        <ul class="text-grey-5">
          <li class="f-list">Admission</li>
          <li class="f-list">Aboud</li>
          <li class="f-list">Login</li>
          <li class="f-list">Register</li>
          <li class="f-list">News</li>
          <li class="f-list">Events</li>
          <li class="f-list">Contacts</li>
        </ul>
      </div>
      <div class="col-xs-10 col-md-7 col-lg-3 q-ma-xl">
        <div class="text-h6 q-mt-xl text-white">Contact Details</div>
        <div class="f-info text-grey-5">
          <q-icon name="smartphone" /> 0344-5587326
        </div>
        <div class="f-info text-grey-5">
          <q-icon name="mail_outline" /> mughalnoman445@gmail.com
        </div>
        <div class="text-h6 text-white q-pt-xl">
          News Letter
          <div class="flex flex-center row">
            <q-input
              outlined
              dark
              dense
              placeholder="Your Email"
              style="width: 260px"
            />
            <q-btn style="background-color: #3b0a5f" label="Submit" />
          </div>
        </div>
      </div>
      <div class="row text-body q-ml-xl text-white">
        FOLLOW US:
        <div class="q-pl-lg q-gutter-lg">
          <q-icon class="icon" size="20px" name="fa-brands fa-facebook-f" />
          <q-icon class="icon" size="20px" name="fa-brands fa-twitter" />
          <q-icon class="icon" size="20px" name="fa-brands fa-google-plus-g" />
          <q-icon class="icon" size="20px" name="fa-brands fa-pinterest" />
          <q-icon class="icon" size="20px" name="fa-brands fa-instagram" />
        </div>
      </div>
    </div>
  </footer>
  <footer class="lt-md">
    <div style="background-color: #0f1921" class="row">
      <div class="col-xs-12 col-md-6 col-lg-5">
        <q-img src="~assets/logo.png" class="q-mt-xl q-ml-lg" width="160px" />
        <p class="q-mx-lg q-mt-lg text-grey-5">
          Mea nibh meis philosophia eu. Duis legimus efficiantur ea sea. Id
          placerat tacimates definitionem sea, prima quidam vim no. Duo nobis
          persecuti cu. Nihil facilisi indoctum an vix, ut delectus expetendis
          vis.
        </p>
      </div>
      <div class="col-xs-10 col-md-7 col-lg-3 q-mt-lg q-ml-lg">
        <div class="text-h6 text-white">Contact Details</div>
        <div class="f-info text-grey-5">
          <q-icon name="smartphone" /> 0344-5587326
        </div>
        <div class="f-info text-grey-5">
          <q-icon name="mail_outline" /> mughalnoman445@gmail.com
        </div>
        <div class="text-h6 text-white q-my-lg">
          News Letter
          <div class="flex flex-center row">
            <q-input
              outlined
              dark
              dense
              placeholder="Your Email"
              style="width: 200px"
            />
            <q-btn style="background-color: #3b0a5f" label="Submit" />
          </div>
        </div>
      </div>
      <div class="row text-body q-ml-lg q-mb-lg text-white">
        FOLLOW US:
        <div class="q-pl-lg q-gutter-lg">
          <q-icon class="icon" size="20px" name="fa-brands fa-facebook-f" />
          <q-icon class="icon" size="20px" name="fa-brands fa-twitter" />
          <q-icon class="icon" size="20px" name="fa-brands fa-google-plus-g" />
          <q-icon class="icon" size="20px" name="fa-brands fa-pinterest" />
          <q-icon class="icon" size="20px" name="fa-brands fa-instagram" />
        </div>
      </div>
    </div>
  </footer>
  <!-- Footer section -->

  <!-- drawer -->
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
  <!-- Drawer -->
</template>



<script>
import { defineComponent } from "vue";
import { ref } from "vue";
import { Carousel, Pagination, Slide } from "vue3-carousel";
import "vue3-carousel/dist/carousel.css";
const list = [
  {
    src: require("assets/course__list_1.jpg"),
  },
  {
    src: require("assets/course__list_2.jpg"),
  },
  {
    src: require("assets/course__list_3.jpg"),
  },
  {
    src: require("assets/course__list_4.jpg"),
  },
  {
    src: require("assets/course__list_5.jpg"),
  },
  {
    src: require("assets/course__list_6.jpg"),
  },
];
export default defineComponent({
  name: "AutoPlay",
  components: {
    Carousel,
    Slide,
  },
  setup() {
    return {
      list,
      ratingModel: ref(3),
      drawerLeft: ref(false),
      drawerRight: ref(false),
      drawer: ref(false),
    };
  },
});
</script>


<style lang="scss">
.bg-nav {
  background-image: linear-gradient(90deg, #3b0a5f, #c31432);
}
.a-link {
  text-decoration: none;
  color: black;
}
.bg-img {
  background-image: url(assets/classroom.jpg);
  height: 76.3vh;
}
@media screen and (max-width: 1023px) {
  .bg-img {
    background-image: url(assets/classroom.jpg);
    height: 50vh;
  }
}

// Carousal Section
.carousel__slide {
  padding: 5px;
}

.carousel__viewport {
  perspective: 2000px;
}

.carousel__track {
  transform-style: preserve-3d;
}

.carousel__slide--sliding {
  transition: 0.5s;
}

.carousel__slide {
  opacity: 0.9;
  transform: rotateY(-20deg) scale(0.9);
}

.carousel__slide--active ~ .carousel__slide {
  transform: rotateY(20deg) scale(0.9);
}

.carousel__slide--prev {
  opacity: 1;
  transform: rotateY(-10deg) scale(0.95);
}

.carousel__slide--next {
  opacity: 1;
  transform: rotateY(10deg) scale(0.95);
}

.carousel__slide--active {
  opacity: 1;
  transform: rotateY(0) scale(1.1);
}
// Carousal Section

.course-img {
  border-radius: none;
  cursor: pointer;
  transition: 0.2s all ease-in-out;
}
.course-img:hover {
  transform: scale(1.05);
}
.my-news-card {
  cursor: pointer;
  cursor: pointer;
  transition: 0.2s all ease-in-out;
}
.my-news-card:hover {
  color: rgb(126, 126, 212);
  transform: scale(1.05);
}
.icon {
  cursor: pointer;
}
.icon:hover {
  color: rgb(66, 64, 64);
}
.f-list {
  cursor: pointer;
}
.f-list:hover {
  color: rgb(66, 64, 64);
  text-decoration: underline;
}
.f-info {
  cursor: pointer;
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





