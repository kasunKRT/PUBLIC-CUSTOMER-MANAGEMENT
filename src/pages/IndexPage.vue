<template>
  <q-page class="bg-white text-dark">
    <!-- Hero Section -->
    <section
      class="hero-section relative-position flex flex-center text-center q-pa-xl"
      style="min-height: 80vh; overflow: hidden"
    >
      <q-img
        src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80"
        class="absolute-full"
        style="z-index: 0"
        fit="cover"
      />

      <div class="relative-position z-top container" style="z-index: 2; max-width: 800px">
        <h1 class="text-h2 text-weight-bolder text-white q-mb-md">
          Empower Your <span class="text-light-blue-13">Customer Relationships</span>
        </h1>
        <p class="text-h5 text-grey-3 q-mb-xl">
          The ultimate solution for managing customer data, interactions, and insights with a sleek,
          modern interface.
        </p>
        <div class="row justify-center q-gutter-md">
          <q-btn color="primary" size="lg" label="Get Started" unelevated no-caps class="q-px-xl" />
          <q-btn outline color="white" size="lg" label="Learn More" no-caps class="q-px-xl" />
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section class="q-py-xl bg-white">
      <div class="container q-pa-md" style="max-width: 1200px; margin: 0 auto">
        <div class="text-center q-mb-xl">
          <h2 class="text-h3 text-weight-bold text-dark">Why Choose CustFlow?</h2>
          <div class="text-primary text-h6">Powerful Features for Modern Business</div>
        </div>

        <div class="row q-col-gutter-lg">
          <div class="col-12 col-md-4">
            <q-card class="bg-grey-1 q-pa-md hover-scale shadow-2 border-none">
              <q-card-section class="text-center">
                <q-icon name="analytics" color="primary" size="4rem" />
                <div class="text-h5 q-mt-md text-weight-bold text-dark">Real-time Analytics</div>
              </q-card-section>
              <q-card-section class="text-grey-7 text-center">
                Gain deep insights into customer behavior with our advanced real-time dashboard and
                reporting tools.
              </q-card-section>
            </q-card>
          </div>

          <div class="col-12 col-md-4">
            <q-card class="bg-grey-1 q-pa-md hover-scale shadow-2 border-none">
              <q-card-section class="text-center">
                <q-icon name="security" color="primary" size="4rem" />
                <div class="text-h5 q-mt-md text-weight-bold text-dark">Secure Data</div>
              </q-card-section>
              <q-card-section class="text-grey-7 text-center">
                Enterprise-grade security ensures your customer data is protected with end-to-end
                encryption.
              </q-card-section>
            </q-card>
          </div>

          <div class="col-12 col-md-4">
            <q-card class="bg-grey-1 q-pa-md hover-scale shadow-2 border-none">
              <q-card-section class="text-center">
                <q-icon name="sync" color="primary" size="4rem" />
                <div class="text-h5 q-mt-md text-weight-bold text-dark">Automated Workflows</div>
              </q-card-section>
              <q-card-section class="text-grey-7 text-center">
                Streamline your operations by automating repetitive tasks and focusing on what
                matters most.
              </q-card-section>
            </q-card>
          </div>
        </div>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="q-py-xl bg-grey-1 text-dark border-top border-bottom">
      <div class="container q-pa-md" style="max-width: 1200px; margin: 0 auto">
        <div class="row justify-evenly text-center q-gutter-y-lg">
          <div class="col-12 col-md-3">
            <div class="text-h2 text-weight-bolder text-primary">10k+</div>
            <div class="text-h6 text-grey-8">Active Users</div>
          </div>
          <div class="col-12 col-md-3">
            <div class="text-h2 text-weight-bolder text-primary">99.9%</div>
            <div class="text-h6 text-grey-8">Uptime</div>
          </div>
          <div class="col-12 col-md-3">
            <div class="text-h2 text-weight-bolder text-primary">24/7</div>
            <div class="text-h6 text-grey-8">Support</div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="q-py-xl bg-white text-center">
      <div class="container q-pa-md" style="max-width: 800px; margin: 0 auto">
        <h2 class="text-h3 text-dark text-weight-bold q-mb-md">
          Ready to Transform Your Business?
        </h2>
        <p class="text-grey-7 text-h6 q-mb-xl">
          Join thousands of companies using CustFlow to build better customer relationships.
        </p>
        <q-btn
          color="primary"
          size="xl"
          label="Get Started for Free"
          unelevated
          no-caps
          class="q-px-xl"
        />
      </div>
    </section>
  </q-page>
</template>

<script setup>
// Script logic can be added here
</script>

<style scoped>
.bg-gradient {
  background: linear-gradient(135deg, #000000 0%, #3a0000 100%);
}
.hover-scale {
  transition: transform 0.3s ease;
}
.hover-scale:hover {
  transform: translateY(-10px);
}
.border-top {
  border-top: 1px solid #e0e0e0;
}
.border-bottom {
  border-bottom: 1px solid #e0e0e0;
}
</style>
