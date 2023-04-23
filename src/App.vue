<template>
    <HeaderFl/>
    <PreviewFl/>
    <FeaturesFl/>
    <ContentsFl/>
    <GalleryFl/>
    <PartnersFl/>
    <TestimonialsFl/>
    <OpentypeFl/>
    <FooterFl/>
</template>
<script>
import HeaderFl from '@/components/HeaderFl.vue';
import PreviewFl from '@/components/PreviewFl.vue';
import FeaturesFl from '@/components/FeaturesFl.vue';
import ContentsFl from '@/components/ContentsFl.vue';
import GalleryFl from '@/components/GalleryFl.vue';
import PartnersFl from '@/components/PartnersFl.vue';
import TestimonialsFl from '@/components/TestimonialsFl.vue';
import OpentypeFl from '@/components/OpentypeFl.vue';
import FooterFl from '@/components/FooterFl.vue'

export default{
    components : {
        HeaderFl,
        PreviewFl,
        FeaturesFl,
        ContentsFl,
        GalleryFl,
        PartnersFl,
        TestimonialsFl,
        OpentypeFl,
        FooterFl,
    }
}
</script>
<style>

*
{
    transition: all .5s;
    background-color: transparent;
    margin: 0;
    padding: 0;
    text-decoration: none;
    outline: none;
    list-style-type: none;
    font-family: 'Inter', sans-serif;
    color: #fff;
}
body
{
    margin: 0;
    background-color: #181818;
}
.container
{
    max-width: 1045px;
    margin: 0 auto;
    padding: 0px 30px;
}

a,button,input
{ 
    padding: 0;
    margin: 0;
    cursor: pointer;
    border: 0;
    background: none;
}
@media (max-width: 850px){
    #footer__wrap,#footer__items-left,#opent__wrap,.gallery__items-line1,
    #contents__items,#features__items
    {
        display: flex;
        flex-direction: column;
    }
    #footer__wrap
    { gap: 100px;}
    #opent__wrap
    { background-color: transparent; box-shadow: none; }
    #testm__items-wrap
    { grid-template-columns: none; }
    #partners__items
    { 
        display: grid;
        grid-template-rows: 1fr ;
        grid-template-columns: 1fr 1fr 1fr ;
        gap: 40px; 
    }
    .gallery__items-line2,#header__links
    { display: none; }
    #contents__items
    { max-width: fit-content;}
    .features__img-2{ left: 21%; margin-top: -300px; }
    #features__textzone
    { margin: 0 auto; }
    #header__login
    { margin-left: 37%; }
}

</style>
