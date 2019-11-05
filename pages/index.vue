<template>
  <div>
    <!-- Navigation -->
    <navigation></navigation>

    <!-- Masthead -->
    <masthead></masthead>

    <!-- Icons Grid -->
    <icons-grid></icons-grid>

    <!-- Image Showcases -->
    <image-showcase></image-showcase>

    <!-- Testimonials -->
    <testimonials></testimonials>

    <!-- Call to Action -->
    <call-to-action></call-to-action>

    <!-- Footer -->
    <footer-component></footer-component>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Navigation from '~/components/Navigation'
import CallToAction from '~/components/CallToAction'
import FooterComponent from '~/components/FooterComponent'
import IconsGrid from '~/components/IconsGrid'
import Masthead from '~/components/Masthead'
import ImageShowcase from '~/components/ImageShowcase'
import Testimonials from '~/components/Testimonials'

export default {
  components: {
    Logo,
    Navigation,
    CallToAction,
    FooterComponent,
    IconsGrid,
    Masthead,
    ImageShowcase,
    Testimonials
  }
}
</script>
