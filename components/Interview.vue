<template>
    <div
        class="antialiased bg-white dark:bg-black dark:text-white flex flex-col items-center justify-center min-h-screen place-content-center sm:text-base text-black text-sm">
        <div class="flex flex-1 flex-col gap-y-16 py-14">
            <div class="flex flex-col gap-y-4 items-center justify-center">
                <span class="dark:text-white font-semibold sm:text-5xl text-4xl text-black text-center">Software
                    Engineering Résumé Review & Job Search Strategy Consulting</span>
            </div>
            <div class="flex flex-col items-center justify-center">
                <div class="gap-6 grid grid-cols-2 lg:grid-cols-10 max-w-[960px] px-4">
                    <div class="col-span-2 lg:col-span-10 relative items-center ">
                        <div class="absolute inset-y-0 left-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- left area -->
                        </div>
                        <div
                            class="absolute inset-y-0 right-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- right area -->
                        </div>
                        <div class="-top-[58px] absolute flex inset-x-0 justify-center w-full">
                        </div>
                        <h1 class="text-2xl mb-10">Trouble getting calls back after applying to open positions?</h1>
                        <p class="m-6">I help software developers of any experience level industry land interviews fast.
                        </p>
                        <p class="m-6">Software engineer, software developer, programmer, data scientist. 
                            Whatever you call yourself, I can help you market yourself more effectively.</p>
                        <p class="m-6">
                            By having an in-depth conversation about your skills, experience, where you want to go,
                            and where you've been I
                            provide actionable steps to
                            accelerate your résumé and job search strategy.
                        </p>
                        <div>
                            <h1 class="font-bold text-2xl">Why me?</h1>
                            <ul class="list-inside list-disc">
                                <li>I'm a software developer by trade</li>
                                <li>I understand your experience, tools, and tech. Front-end, back-end, full-stack,
                                    devops, data science, database developers,
                                    juniors, seniors, lead devs, etc.</li>
                                <li>I know what recruiters and hiring managers want to see</li>
                                <li>I've done it multiple times before and learned the lessons so you don't have to</li>
                                <li>I ask you questions and listen to what makes you a great candidate</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="gap-6 grid grid-cols-2 lg:grid-cols-10 max-w-[960px] px-4">
                    <div class="col-span-2 lg:col-span-10 relative items-center ">
                        <div class="absolute inset-y-0 left-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- left area -->
                        </div>
                        <div
                            class="absolute inset-y-0 right-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- right area -->
                        </div>
                        <div class="-top-[58px] absolute flex inset-x-0 justify-center w-full">
                        </div>
                        <div class="flex flex-col gap-y-4 items-center pb-6 pt-[58px] px-4 rounded-xl sm:px-28 z-10">
                            <span class="text-md font-semibold">Hear from other people I've
                                helped!</span>
                            <TestimonialCarosel />
                        </div>
                    </div>
                </div>
                <div class="gap-6 grid grid-cols-2 lg:grid-cols-10 max-w-[960px] px-4">
                    <div class="col-span-2 lg:col-span-10 relative items-center ">
                        <div class="absolute inset-y-0 left-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- left area -->
                        </div>
                        <div
                            class="absolute inset-y-0 right-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- right area -->
                        </div>
                        <div class="-top-[58px] absolute flex inset-x-0 justify-center w-full">
                        </div>
                        <div class="flex flex-col gap-y-4 items-center pb-6 pt-[58px] px-4 rounded-xl sm:px-28 z-10">
                        </div>
                        <h1 class="text-lg font-semibold">What you get</h1>
                        <ul class="list-inside list-disc">
                            <li>A 1 hour conversation to understand where you are in your job search journey</li>
                            <li>An understanding of who you are and what skills & experience make you attractive in the
                                job
                                market</li>
                            <li>An in-depth review of your résumé and search strategy</li>
                            <li>Actionable list of steps to jump start your job search after our consultation</li>
                            <li>1 <span class="font-bold">FREE</span> async résumé follow-up review for additional
                                improvements</li>
                        </ul>
                    </div>
                </div>
                <div class="gap-6 grid grid-cols-2 lg:grid-cols-10 max-w-[960px] px-4">
                    <div class="col-span-2 lg:col-span-10 relative items-center ">
                        <div class="absolute inset-y-0 left-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- left area -->
                        </div>
                        <div
                            class="absolute inset-y-0 right-0 rounded-xl to-transparent transition-opacity w-[20%] z-1">
                            <!-- right area -->
                        </div>
                        <div class="-top-[58px] absolute flex inset-x-0 justify-center w-full">
                        </div>
                        <div class="flex flex-col gap-y-4 items-center pb-6 pt-[58px] px-4 rounded-xl sm:px-28 z-10">
                        </div>
                        <h1 class="text-lg font-semibold">
                            <!-- Schedule a call! -->
                            <ULink to="https://calendly.com/d-michaelalthoff/60min"
                                active-class="text-primary"
                                class="text-blue-600 dark:text-blue-500 hover:underline"
                                >
                                <Icon name="logos:google-calendar"/>&nbsp;Click Here to Schedule A Call!
                            </ULink>
                        </h1>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
import TestimonialCarosel from './TestimonialCarosel.vue';
</script>
<style>
</style>