<template>
  <div class="flex flex-row mb-6">
    <AdminHeader />
    <AdminFooter />
  </div>
    <AdminWebsite />
  </template>
  
  <style scoped>
  /* Additional styles can go here */
  </style>
  
  <script setup>
  definePageMeta({
    layout: 'dashboard',
    middleware: "auth",
  })
  </script>
  
  
  
  