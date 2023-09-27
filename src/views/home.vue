<template>
  <div>
    <main-info></main-info>
    <calendar></calendar>
    <wedding-details></wedding-details>
    <gifts></gifts>
    <wedding-assistance-confirm></wedding-assistance-confirm>
    <wedding-gallery></wedding-gallery>
    <!--    <corona-message></corona-message>-->
    <account-info></account-info>
    <contact-info></contact-info>
    <the-footer></the-footer>
  </div>
</template>

<script>
import MainInfo from "@/components/main_info.vue";
// import CoronaMessage from "@/components/coronaMessage.vue";
import WeddingGallery from "@/components/wedding_gallery.vue";
import AccountInfo from "@/components/account_info.vue";
import ContactInfo from "@/components/contact_info.vue";
import TheFooter from '@/components/TheFooter.vue';
import Calendar from '@/components/calendar.vue';
import WeddingDetails from "@/components/wedding-details.vue";
import Gifts from "@/components/gifts.vue";
import weddingAssistanceConfirm from "@/components/wedding-assistance-confirm.vue";

export default {
  components: {
    MainInfo,
    AccountInfo,
    Calendar,
    WeddingDetails,
    weddingAssistanceConfirm,
    Gifts,
    ContactInfo,
    WeddingGallery,
    TheFooter
  },
};
</script>

<style scoped>
</style>
