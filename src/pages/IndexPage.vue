<template>
  <q-page>
    <div class="gt-xs">
      <div class="bg-clr">
        <div class="q-pa-md text-center">
          <q-card flat class="my-card bg-transparent flex-center q-pt-xl">
            <q-img width="170px" src="~assets/logo.png" />
            <q-card-section>
              <div class="text-h3 text-weight-bold q-my-md text-white">
                Modern Educational Site Template
              </div>
              <div class="text-h5 text-grey-4">
                Choose one of the demo available below.
              </div>
            </q-card-section>
          </q-card>
        </div>
      </div>
      <div
        class="
          flex-center
          text-center
          q-mt-xl q-pt-xl
          row
          items-start
          q-gutter-md
        "
      >
        <div class="card1">
          <a style="text-decoration: none">
            <q-card flat>
              <q-img width="620px" src="~assets/PC1.jpg" />
              <q-card-section class="text-grey-7">
                <div class="text-subtitle1">Menu Version 1</div>
                <div class="text-subtitle1">
                  Standard Menu with Responsive App Style
                </div>
                <q-btn
                  class="q-mt-md"
                  icon="logout"
                  label="Go To"
                  style="
                    background-image: linear-gradient(90deg, #3b0a5f, #c31432);
                    color: white;
                  "
                  to="/versionOne"
                />
              </q-card-section>
            </q-card>
          </a>
        </div>
        <div class="card2">
          <a style="text-decoration: none">
            <q-card flat>
              <q-img width="620px" src="~assets/PC2.jpg" />
              <q-card-section class="text-grey-7">
                <div class="text-subtitle1">Menu Version 2</div>
                <div class="text-subtitle1">
                  Extended Menu With Smooth Transition
                </div>
                <q-btn
                  class="q-mt-md"
                  icon="logout"
                  style="
                    background-image: linear-gradient(90deg, #3b0a5f, #c31432);
                    color: white;
                  "
                  label="Go To"
                  to="/versionTwo"
                />
              </q-card-section>
            </q-card>
          </a>
        </div>
      </div>
      <div class="text-center">
        <q-btn
          size="18px"
          class="q-py-xs q-ma-xl btn text-white text-weight-bold"
          label="Purchase"
        />
      </div>
    </div>

    <!-- for Small Screen -->
    <div class="lt-sm">
      <div class="bg-clr">
        <div class="q-pa-md text-center">
          <q-card flat class="my-card bg-transparent flex-center q-pt-xl">
            <q-img width="170px" src="~assets/logo.png" />
            <q-card-section>
              <div class="text-h4 text-weight-bold q-my-md text-white">
                Modern Educational Site Template
              </div>
              <div class="text-h6 text-grey-5">
                Choose one of the demo available below.
              </div>
            </q-card-section>
          </q-card>
        </div>
      </div>
      <div class="text-center q-mt-xl q-pt-xl row">
        <div class="card1 col-md-6 col-sm-6 col-xs-12">
          <a style="text-decoration: none">
            <q-card flat>
              <q-img src="~assets/PC1.png" />
              <q-card-section class="text-grey-7">
                <div class="text-subtitle1">Menu Version 1</div>
                <div class="text-subtitle1">
                  Standard Menu with Responsive App Style
                </div>
                <q-btn
                  class="q-mt-md"
                  icon="logout"
                  label="Go To"
                  style="
                    background-image: linear-gradient(90deg, #3b0a5f, #c31432);
                    color: white;
                  "
                  to="/versionOne"
                />
              </q-card-section>
            </q-card>
          </a>
        </div>
        <div class="card2 col-md-6 col-sm-6 col-xs-12">
          <a style="text-decoration: none">
            <q-card flat>
              <q-img src="~assets/PC2.png" />
              <q-card-section class="text-grey-7">
                <div class="text-subtitle1">Menu Version 2</div>
                <div class="text-subtitle1">
                  Extended Menu With Smooth Transition
                </div>
                <q-btn
                  class="q-mt-md"
                  icon="logout"
                  style="
                    background-image: linear-gradient(90deg, #3b0a5f, #c31432);
                    color: white;
                  "
                  label="Go To"
                  to="/versionTwo"
                />
              </q-card-section>
            </q-card>
          </a>
        </div>
      </div>
      <div class="text-center">
        <q-btn
          size="18px"
          class="q-py-xs q-ma-xl btn text-white text-weight-bold"
          label="Purchase"
        />
      </div>
    </div>
    <!-- for small screen -->
  </q-page>
</template>


<style lang="scss">
.bg-clr {
  height: 350px;
  width: 100%;
  background-image: linear-gradient(90deg, #3b0a5f, #c31432);
}
.card1:hover {
  -webkit-animation: mover 0s infinite alternate;
  animation: mover 1s infinite alternate;
}
@-webkit-keyframes mover {
  0% {
    transform: translateY(-20px);
  }
  100% {
    transform: translateY(-20px);
  }
}
@keyframes mover {
  0% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(-20px);
  }
}
.card2:hover {
  -webkit-animation: mover 0s infinite alternate;
  animation: mover 1s infinite alternate;
}
@-webkit-keyframes mover {
  0% {
    transform: translateY(-20px);
  }
  100% {
    transform: translateY(-20px);
  }
}
@keyframes mover {
  0% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(-20px);
  }
}
.btn {
  background-image: linear-gradient(90deg, #3b0a5f, #c31432);
}
</style>
