<script setup lang="ts"></script>

<template>
  <v-row>
    <v-col cols="12" sm="12" lg="8"> <DashboardSalesOverview /></v-col>
    <v-col cols="12" sm="12" lg="4"><DashboardBlog /></v-col>
    <v-col cols="12" sm="12" lg="4">
      <DashboardProfileCard />
      <div class="mb-7"></div>
      <DashboardContactsMyContacts />
    </v-col>
    <v-col cols="12" sm="12" lg="8">
      <DashboardTimeline />
    </v-col>
  </v-row>
</template>
