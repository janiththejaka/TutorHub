<template>
  <q-layout view="lHh Lpr lff">
    <q-header class="text-dark shadow-sm bg-glass" height-hint="98">
      <q-toolbar class="q-py-md container-xl">
        <q-btn flat no-caps no-wrap class="q-ml-xs" to="/">
          <q-icon name="school" color="primary" size="28px" />
          <q-toolbar-title shrink class="text-weight-bold text-h5 q-ml-sm text-primary">
            EduPro<span class="text-secondary">LMS</span>
          </q-toolbar-title>
        </q-btn>

        <q-space />

        <div class="gt-sm row q-gutter-sm items-center">
          <q-btn flat no-caps label="Features" />
          <q-btn flat no-caps label="Courses" />
          <q-btn flat no-caps label="Pricing" />
          <q-btn flat no-caps label="About Us" />
          <q-separator vertical spaced />
          <q-btn outline color="primary" label="Log in" no-caps class="q-px-md" />
          <q-btn unelevated color="primary" label="Sign up" no-caps class="q-px-md shadow-2" />
        </div>

        <div class="lt-md">
          <q-btn flat dense icon="menu" @click="toggleLeftDrawer" />
        </div>
      </q-toolbar>
    </q-header>

    <q-drawer v-model="leftDrawerOpen" side="right" bordered overlay behavior="mobile" class="bg-white text-dark q-pa-md">
      <div class="column q-gutter-md q-pt-xl">
        <q-btn flat no-caps label="Features" align="left" class="text-h6" />
        <q-btn flat no-caps label="Courses" align="left" class="text-h6" />
        <q-btn flat no-caps label="Pricing" align="left" class="text-h6" />
        <q-btn flat no-caps label="About Us" align="left" class="text-h6" />
        <q-separator />
        <q-btn outline color="primary" label="Log in" no-caps class="full-width q-py-sm" />
        <q-btn unelevated color="primary" label="Sign up" no-caps class="full-width q-py-sm shadow-2" />
      </div>
      <q-btn icon="close" flat round dense class="absolute-top-right q-ma-md" @click="toggleLeftDrawer" />
    </q-drawer>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-dark text-white q-py-xl">
      <div class="container-xl q-px-md">
        <div class="row q-col-gutter-xl">
          <div class="col-12 col-md-4">
            <div class="row items-center q-mb-md">
              <q-icon name="school" color="secondary" size="32px" />
              <div class="text-h5 text-weight-bold q-ml-sm">EduProLMS</div>
            </div>
            <p class="text-grey-5">
              Empowering global education through technology. The most trusted platform for online learning management.
            </p>
          </div>
          <div class="col-6 col-md-2">
            <div class="text-subtitle1 text-weight-bold q-mb-md">Platform</div>
            <div class="column q-gutter-sm">
              <a href="#" class="text-grey-5 no-decoration hover-white">Overview</a>
              <a href="#" class="text-grey-5 no-decoration hover-white">Features</a>
              <a href="#" class="text-grey-5 no-decoration hover-white">Pricing</a>
            </div>
          </div>
          <div class="col-6 col-md-2">
            <div class="text-subtitle1 text-weight-bold q-mb-md">Company</div>
            <div class="column q-gutter-sm">
              <a href="#" class="text-grey-5 no-decoration hover-white">About</a>
              <a href="#" class="text-grey-5 no-decoration hover-white">Careers</a>
              <a href="#" class="text-grey-5 no-decoration hover-white">Contact</a>
            </div>
          </div>
          <div class="col-12 col-md-4">
            <div class="text-subtitle1 text-weight-bold q-mb-md">Subscribe</div>
            <p class="text-grey-5">Get the latest updates and offers.</p>
            <q-input dark dense outlined placeholder="Enter your email" class="q-mb-sm">
              <template v-slot:append>
                <q-btn flat label="Go" color="secondary" />
              </template>
            </q-input>
          </div>
        </div>
        <q-separator dark class="q-my-lg" />
        <div class="row justify-between items-center text-grey-6">
          <div>© 2024 EduProLMS. All rights reserved.</div>
          <div class="row q-gutter-sm">
            <q-btn round flat icon="facebook" size="sm" />
            <q-btn round flat icon="add_to_photos" size="sm" /> <!-- Logo for twitter/landing -->
            <q-btn round flat icon="star" size="sm" />
          </div>
        </div>
      </div>
    </q-footer>
  </q-layout>
</template>

<script setup>
import { ref } from 'vue'

const leftDrawerOpen = ref(false)

function toggleLeftDrawer() {
  leftDrawerOpen.value = !leftDrawerOpen.value
}
</script>

