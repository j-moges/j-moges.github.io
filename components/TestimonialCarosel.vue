<script setup lang="ts">
const items = [
    {
        testimonial: `It was quiet and then out of nowhere I got like 4-5 interviews. 
     Software engineer position, full stack web dev position, admin assistant (IT), IT government and another I believe it was web development.
     Got the final interivew for the web developer position, 
     I'm not sure what happened that week but that's when I submitted most of these applications.
     I've stuck with the resume you've helped me build and it's the one that works.`,
        author: 'Kamren S.'
    },
    {
        testimonial: `I have had multiple interviews since I updated my resume. 
  As a matter of fact I am getting ready to do a third interview on Tuesday with a huge restaurant group for a full time IT position.
  I definitely think that the changes we made to my resume opened the door for my initial interview. 
  As a matter of fact I have had almost triple the amount of recruiters asking me if I could interview for a 
  position that I applied for.  The most valuable part of our interaction 
  was the knowledge about the Technology industry and what to stay away from.
  
  I can attest that he was a difference maker in my job search. 
  I had so many versions of my resume with different formats it was quite ridiculous. 
  After working with him it only took a couple of weeks 
  before I started to get noticed more than I had over the past 2 years.`,
        author: 'Michael P.'
    },
    // {
    //     testimonial: 'test testimonial 3',
    //     author: 'TestAuthor 3'
    // }
    // ,
    // {
    //     testimonial: 'test testimonial 4',
    //     author: 'TestAuthor 4'
    // },
    // {
    //     testimonial: 'test testimonial 5',
    //     author: 'TestAuthor 5'
    // },
    // {
    //     testimonial: 'test testimonial 6',
    //     author: 'TestAuthor 6'
    // }
]

const carouselRef = ref()

onMounted(() => {
    setInterval(() => {
        if (!carouselRef.value) return

        if (carouselRef.value.page === carouselRef.value.pages) {
            return carouselRef.value.select(0)
        }

        carouselRef.value.next()
    }, 15000)
})
</script>

<template>
    <UCarousel ref="carouselRef" v-slot="{ item }" :items="items" :ui="{ item: 'basis-full' }"
        class="rounded-lg overflow-hidden" indicators>
        <TestimonialCard :testimonial="item.testimonial" :author="item.author"></TestimonialCard>
        <!-- <img :src="item.pic" class="w-full" draggable="false"> -->
    </UCarousel>
</template>
