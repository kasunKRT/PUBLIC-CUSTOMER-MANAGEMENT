<template>
  <q-layout view="hHh lpR fFf" class="bg-white text-dark">
    <q-header class="bg-white text-primary shadow-2" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-cyan.svg" />
          </q-avatar>
          CustFlow
        </q-toolbar-title>

        <q-tabs align="left">
          <q-route-tab to="/" label="Home" />
          <q-route-tab to="/features" label="Features" />
          <q-route-tab to="/pricing" label="Pricing" />
          <q-route-tab to="/contact" label="Contact" />
        </q-tabs>

        <q-space />

        <div class="q-gutter-sm row items-center no-wrap">
          <q-btn round dense flat color="grey-6" icon="notifications">
            <q-badge color="red" text-color="white" floating> 2 </q-badge>
            <q-tooltip>Notifications</q-tooltip>
          </q-btn>
          <q-btn round flat color="grey-6">
            <q-avatar size="26px">
              <img src="https://cdn.quasar.dev/img/boy-avatar.png" />
            </q-avatar>
            <q-tooltip>Account</q-tooltip>
          </q-btn>
          <q-btn flat label="Log In" color="primary" />
          <q-btn color="primary" label="Get Started" unelevated />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-grey-2 text-grey-8">
      <div class="q-pa-md row justify-between items-center">
        <div>&copy; 2024 CustFlow. All rights reserved.</div>
        <div class="q-gutter-md">
          <q-btn flat round icon="facebook" />
          <q-btn flat round icon="twitter" />
          <q-btn flat round icon="linkedin" />
        </div>
      </div>
    </q-footer>
  </q-layout>
</template>

<script setup>
// No script needed for this layout currently
</script>
