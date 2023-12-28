<template>
    <div class=" text-white lg:px-56 px-8 pt-24 pb-10 h-full flex flex-col items-center">
        <div
            class="bg-[#171717] rounded-3xl pt-10 xl:px-24 lg:px-24 md:px-32 px-8 h-full lg:max-w-5xl md:max-w-2xl sm:max-w-2xl max-w-lg w-full relative items-center">
            <div class="  h-5/6 overflow-auto">
                <!-- This component is the onboarding screen like Mengheang's UI -->
                <!-- <Introduction /> -->

                <ChatPanel />
            </div>

            <PromptInput class=" absolute bottom-10   xl:inset-x-32 lg:inset-x-24 md:inset-x-32 inset-x-10 " />
        </div>
    </div>
</template>

<script>
export default {
    setup() {


        return {}
    }
}
</script>

<style >
.scrollbar-w-2::-webkit-scrollbar {
    width: 0.25rem;
    height: 0.25rem;
}
</style>