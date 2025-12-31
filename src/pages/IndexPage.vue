<template>
  <q-page>
    <!-- Hero Section -->
    <section class="min-h-screen-nav flex flex-center relative-position overflow-hidden bg-gradient-hero q-pb-xl">
      <div class="container-xl row items-center q-col-gutter-xl q-pt-xl">
        <div class="col-12 col-md-6 z-10 animate-fade-up">
          <q-badge color="orange-1" text-color="orange-9" label="🚀 #1 Online Learning Platform" class="q-py-xs q-px-sm text-subtitle2 q-mb-md" />
          <h1 class="text-h2 text-weight-bolder text-dark q-mt-none q-mb-md lh-tight">
            Unlock Your Potential with <span class="text-primary">EduPro</span>
          </h1>
          <p class="text-h6 text-grey-7 q-mb-lg lh-base" style="max-width: 500px">
            Master new skills with our expertly curated courses. Join a global community of learners and achieve your goals today.
          </p>
          <div class="row q-gutter-md">
            <q-btn unelevated color="primary" size="lg" label="Get Started Free" no-caps class="q-px-xl text-weight-bold shadow-lg" icon-right="arrow_forward" />
            <q-btn outline color="primary" size="lg" label="Explore Courses" no-caps class="q-px-xl text-weight-bold bg-white" />
          </div>
          <div class="row q-mt-lg q-gutter-sm items-center text-grey-6">
            <div class="row -space-x-4">
               <q-avatar size="32px" class="shadow-1"><img src="https://cdn.quasar.dev/img/avatar1.jpg"></q-avatar>
               <q-avatar size="32px" class="shadow-1" style="margin-left: -10px"><img src="https://cdn.quasar.dev/img/avatar2.jpg"></q-avatar>
               <q-avatar size="32px" class="shadow-1" style="margin-left: -10px"><img src="https://cdn.quasar.dev/img/avatar3.jpg"></q-avatar>
               <q-avatar size="32px" class="shadow-1 bg-grey-3 text-caption" style="margin-left: -10px">+2k</q-avatar>
            </div>
            <div class="text-caption q-ml-sm">Trusted by 2,000+ students</div>
          </div>
        </div>
        <div class="col-12 col-md-6 relative-position">
           <img src="~assets/hero-illustration.png" alt="LMS Illustration" class="full-width float-animation" />
           <!-- Decorative elements -->
           <div class="absolute-top-right bg-secondary text-white q-pa-md rounded-borders shadow-lg float-card" style="top: 10%; right: -20px;">
              <div class="text-weight-bold text-subtitle1">300+</div>
              <div class="text-caption">Active Courses</div>
           </div>
        </div>
      </div>
      <!-- Background blobs -->
      <div class="absolute-top-right bg-blue-1 circle-blob" style="top: -100px; right: -100px; width: 500px; height: 500px;"></div>
      <div class="absolute-bottom-left bg-teal-1 circle-blob" style="bottom: -50px; left: -100px; width: 300px; height: 300px;"></div>
    </section>

    <!-- Stats Section -->
    <section class="bg-primary text-white q-py-xl">
      <div class="container-xl">
        <div class="row q-col-gutter-lg text-center">
          <div class="col-6 col-md-3">
            <div class="text-h3 text-weight-bold">15k+</div>
            <div class="text-subtitle1 text-blue-2">Active Students</div>
          </div>
          <div class="col-6 col-md-3">
            <div class="text-h3 text-weight-bold">500+</div>
            <div class="text-subtitle1 text-blue-2">Expert Instructors</div>
          </div>
          <div class="col-6 col-md-3">
            <div class="text-h3 text-weight-bold">1.2k</div>
            <div class="text-subtitle1 text-blue-2">Quality Courses</div>
          </div>
          <div class="col-6 col-md-3">
            <div class="text-h3 text-weight-bold">4.9</div>
            <div class="text-subtitle1 text-blue-2">Average Rating</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section class="q-py-xl bg-grey-1">
      <div class="container-xl q-mb-xl text-center">
        <div class="text-secondary text-weight-bold text-subtitle2 uppercase tracking-wide">Why Choose Us</div>
        <h2 class="text-h3 text-weight-bold text-dark q-mt-sm">Transform Your Learning Experience</h2>
      </div>
      
      <div class="container-xl">
        <div class="row q-col-gutter-lg">
          <div class="col-12 col-md-4">
             <q-card flat class="q-pa-lg bg-white rounded-lg hover-scale item-center text-center h-full">
                <div class="q-mb-md inline-block q-pa-md bg-blue-1 rounded-circle text-primary">
                   <q-icon name="laptop_mac" size="32px" />
                </div>
                <div class="text-h6 text-weight-bold q-mb-sm">Learn Anywhere</div>
                <p class="text-grey-7">Access your courses from any device, anytime. Switch seamlessly between laptop, tablet, and mobile.</p>
             </q-card>
          </div>
          <div class="col-12 col-md-4">
             <q-card flat class="q-pa-lg bg-white rounded-lg hover-scale text-center h-full">
                <div class="q-mb-md inline-block q-pa-md bg-teal-1 rounded-circle text-secondary">
                   <q-icon name="workspace_premium" size="32px" />
                </div>
                <div class="text-h6 text-weight-bold q-mb-sm">Expert Instructors</div>
                <p class="text-grey-7">Learn from industry experts who are passionate about teaching and helping you succeed.</p>
             </q-card>
          </div>
          <div class="col-12 col-md-4">
             <q-card flat class="q-pa-lg bg-white rounded-lg hover-scale text-center h-full">
                <div class="q-mb-md inline-block q-pa-md bg-orange-1 rounded-circle text-accent">
                   <q-icon name="groups" size="32px" />
                </div>
                <div class="text-h6 text-weight-bold q-mb-sm">Community</div>
                <p class="text-grey-7">Join a supportive community of learners. Share knowledge, ask questions, and grow together.</p>
             </q-card>
          </div>
        </div>
      </div>
    </section>

    <!-- Popular Courses -->
    <section class="q-py-xl">
      <div class="container-xl row justify-between items-end q-mb-xl">
         <div>
            <div class="text-secondary text-weight-bold text-subtitle2 uppercase tracking-wide">Explore</div>
            <h2 class="text-h3 text-weight-bold text-dark q-mt-sm q-mb-none">Popular Courses</h2>
         </div>
         <q-btn flat color="primary" label="View All Courses" icon-right="arrow_forward" no-caps />
      </div>

      <div class="container-xl">
         <div class="row q-col-gutter-lg">
            <!-- Course Card 1 -->
            <div class="col-12 col-md-4" v-for="i in 3" :key="i">
               <q-card class="rounded-lg shadow-1 overflow-hidden hover-shadow transition-all cursor-pointer column h-full">
                  <q-img :src="`https://cdn.quasar.dev/img/parallax${i}.jpg`" :ratio="16/9">
                     <div class="absolute-top-left bg-transparent q-pa-sm">
                        <q-badge color="white" text-color="dark" label="Design" />
                     </div>
                  </q-img>
                  <q-card-section class="q-pb-xs">
                     <div class="row items-center justify-between no-wrap">
                        <div class="row items-center text-caption text-grey-7">
                           <q-icon name="schedule" size="14px" class="q-mr-xs" /> 6 weeks
                        </div>
                        <div class="row items-center text-caption text-orange">
                           <q-icon name="star" size="14px" /> 4.8 (1.2k)
                        </div>
                     </div>
                     <div class="text-h6 q-mt-sm text-weight-bold doc-title q-my-xs">UI/UX Design Masterclass</div>
                     <p class="text-grey-7 text-caption ellipsis-2-lines">Learn to create beautiful user interfaces and intuitive user experiences from scratch.</p>
                  </q-card-section>
                  <q-separator inset />
                  <q-card-section class="q-pt-sm row justify-between items-center bg-grey-1">
                     <div class="row items-center">
                        <q-avatar size="24px" class="q-mr-sm"><img src="https://cdn.quasar.dev/img/avatar.png"></q-avatar>
                        <span class="text-caption text-weight-medium">John Doe</span>
                     </div>
                     <div class="text-h6 text-primary text-weight-bold">$49</div>
                  </q-card-section>
               </q-card>
            </div>
         </div>
      </div>
    </section>

    <!-- Call to Action -->
    <section class="q-py-xl bg-dark text-white text-center relative-position overflow-hidden">
       <div class="container-xl relative-position z-10">
          <h2 class="text-h3 text-weight-bold q-mb-md">Ready to Start Learning?</h2>
          <p class="text-h6 text-grey-4 q-mb-xl" style="max-width: 600px; margin-left: auto; margin-right: auto;">
             Join thousands of students and start transforming your career today.
          </p>
          <q-btn unelevated color="secondary" size="lg" label="Join for Free" class="q-px-xl text-weight-bold" />
       </div>
       <div class="absolute-full opacity-10 bg-gradient-overlay"></div>
    </section>
  </q-page>
</template>

<script setup>
//
</script>

<style lang="scss" scoped>
.lh-tight {
  line-height: 1.1;
}
.lh-base {
  line-height: 1.6;
}
.min-h-screen-nav {
  min-height: calc(100vh - 80px); /* Adjust based on navbar height */
}
.circle-blob {
  border-radius: 50%;
  filter: blur(80px);
  opacity: 0.6;
  z-index: 0;
}
.z-10 {
  z-index: 10;
}
.float-animation {
  animation: float 6s ease-in-out infinite;
}
@keyframes float {
  0% { transform: translateY(0px); }
  50% { transform: translateY(-20px); }
  100% { transform: translateY(0px); }
}
.float-card {
  animation: float-delayed 5s ease-in-out infinite;
}
@keyframes float-delayed {
  0% { transform: translateY(0px); }
  50% { transform: translateY(-15px); }
  100% { transform: translateY(0px); }
}
.hover-scale {
  transition: transform 0.3s ease;
  &:hover {
    transform: translateY(-5px);
  }
}
.hover-shadow:hover {
  box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
}
.rounded-lg {
  border-radius: 12px;
}
.rounded-circle {
  border-radius: 50%;
}
.h-full {
  height: 100%;
}
</style>
