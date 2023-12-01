<script setup>
    import Header from './components/Header.vue'
    import ButtonPink from './components/ButtonPink.vue'
    import DevicesImg from '/images/illustration-mockups.svg'
    import CardMain from './components/CardMain.vue'
    import Footer from './components/Footer.vue'
    import FlowingImg from '/images/illustration-flowing-conversation.svg'
</script>

<template>

    <div class="bg-[#ebfbff] pb-8 bg-[url('./images/bg-hero-mobile.svg')] lg:bg-[url('./images/bg-hero-desktop.svg')]">
        <Header />
    <main >
        <section class="text-center mx-7 pt-16 lg:pt-10 text-[#00252e] lg:grid lg:grid-cols-2 lg:items-center lg:gap-x-8">
            <div class="lg:text-left lg:ml-12">
                <h1 class="font-semibold text-3xl lg:text-5xl mb-6 lg:mr-8">Build The Community Your Fans Will Love</h1>
                <p class="lg:text-lg lg:mr-12">Huddle re-imagines the way we build communities. You have a voice, but so does your audience. 
                    Create connections with your users as you engage in genuine discussion. 
                </p>
                <ButtonPink text="Get Started For Free" class="my-10"/>
            </div>
            <img class="mx-auto" :src="DevicesImg" alt="" />
        </section>
    </div>

    
        <div class="relative bg-white min-h-min pt-10 pb-32 lg:pb-40"> 
        <CardMain
            img="./images/illustration-grow-together.svg"
            title="Grow Together"
            description="Generate meaningful discussions with your audience and build a strong, loyal community. 
                        Think of the insightful conversations you miss out on with a feedback form."
        />

        <div class="p-4 shadow rounded-md mx-4 lg:mx-20 my-10 lg:grid lg:grid-cols-2 lg:items-center">
            <img :src=FlowingImg class="lg:max-w-[25rem] lg:m-auto" alt="" />
            <div class="text-center lg:text-left py-4 lg:px-10">
                <h2 class="my-3 text-2xl font-bold text-[#00252e]">Flowing Conversations</h2>
                <p class="text-[#808d99]">You wouldn't paginate a conversation in real life, so why do it online? Our threads 
                        have just-in-time loading for a more natural flow.</p>
            </div>
        </div>

        <CardMain
            img="./images/illustration-your-users.svg"
            title="Your Users"
            description="It takes no time at all to integrate Huddle with your app's authentication solution. 
                        This means, once signed in to your app, your users can start chatting immediately."
        />

        <section class="absolute bg-white py-8 px-6  max-w-[21rem] lg:max-w-[50rem] bottom-[-3%] lg:bottom-[-6%] rounded-lg text-center mx-auto inset-x-0 shadow-lg">
            <h3 class="mb-6 font-bold text-lg lg:text-2xl text-[#00252e]">Ready To Build Your Community?</h3>
            <ButtonPink text="Get Started For Free" />
        </section>
        </div>
    </main>
    
    <Footer/>
    
</template>


