<template>
    <div class=" flex items-center space-x-3">
        <svg class=" shrink-0 h-4" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.49998 6.43942V12.5447" stroke="white" stroke-width="1.5" stroke-linecap="round"
                stroke-linejoin="round" />
            <path d="M12.5556 9.49206H6.44446" stroke="white" stroke-width="1.5" stroke-linecap="round"
                stroke-linejoin="round" />
            <path fill-rule="evenodd" clip-rule="evenodd"
                d="M13.4047 1.16666H5.5952C2.87298 1.16666 1.16663 3.09339 1.16663 5.82095V13.179C1.16663 15.9066 2.86504 17.8333 5.5952 17.8333H13.4047C16.1349 17.8333 17.8333 15.9066 17.8333 13.179V5.82095C17.8333 3.09339 16.1349 1.16666 13.4047 1.16666Z"
                stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
        </svg>

        <input v-model="inputText" @keyup.enter="submitInput"
            class=" border border-white border-opacity-20 rounded-full w-full bg-white bg-opacity-10 focus:ring-0 outline-none px-5 py-3 text-sm font-normal"
            placeholder="Enter your prompt" />

        <button type="submit" @click="submitInput"
            class=" rounded-full p-4 bg-[#005E9B] hover:bg-opacity-70 hover:ease-in-out hover:duration-500">
            <svg class=" shrink-0 h-4" viewBox="0 0 17 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M16.3563 0.648572C15.9396 0.222739 15.323 0.0652386 14.748 0.231905L1.33963 4.10607C0.732962 4.27441 0.302962 4.75524 0.187129 5.36524C0.0687953 5.98691 0.482129 6.77691 1.02213 7.10691L5.21463 9.66691C5.64463 9.93024 6.19963 9.86441 6.55546 9.50774L11.3563 4.70691C11.598 4.45607 11.998 4.45607 12.2396 4.70691C12.4813 4.94774 12.4813 5.34024 12.2396 5.59024L7.43046 10.3911C7.0738 10.7477 7.00713 11.3011 7.26963 11.7319L9.8313 15.9402C10.1313 16.4394 10.648 16.7236 11.2146 16.7236C11.2813 16.7236 11.3563 16.7236 11.423 16.7144C12.073 16.6319 12.5896 16.1894 12.7813 15.5644L16.7563 2.25691C16.9313 1.69024 16.773 1.07357 16.3563 0.648572Z"
                    fill="white" />
                <path opacity="0.4" fill-rule="evenodd" clip-rule="evenodd"
                    d="M1.00889 12.5065C0.848886 12.5065 0.688886 12.4457 0.567219 12.3232C0.323053 12.079 0.323053 11.684 0.567219 11.4398L1.70472 10.3015C1.94889 10.0582 2.34472 10.0582 2.58889 10.3015C2.83222 10.5457 2.83222 10.9415 2.58889 11.1857L1.45055 12.3232C1.32889 12.4457 1.16889 12.5065 1.00889 12.5065ZM4.14322 13.5002C3.98322 13.5002 3.82322 13.4393 3.70155 13.3168C3.45739 13.0727 3.45739 12.6777 3.70155 12.4335L4.83905 11.2952C5.08322 11.0518 5.47905 11.0518 5.72322 11.2952C5.96655 11.5393 5.96655 11.9352 5.72322 12.1793L4.58489 13.3168C4.46322 13.4393 4.30322 13.5002 4.14322 13.5002ZM4.35464 16.4735C4.4763 16.596 4.6363 16.6568 4.7963 16.6568C4.9563 16.6568 5.1163 16.596 5.23797 16.4735L6.3763 15.336C6.61964 15.0918 6.61964 14.696 6.3763 14.4518C6.13214 14.2085 5.7363 14.2085 5.49214 14.4518L4.35464 15.5902C4.11047 15.8343 4.11047 16.2293 4.35464 16.4735Z"
                    fill="white" />
            </svg>

        </button>
    </div>
</template>

<script>
export default {
    setup() {
        const inputText = ref('')
        return { inputText }
    },
    methods: {
        submitInput() {
            console.log("Print this input text:", this.inputText)
        }
    },
}
</script>

<style lang="scss" scoped></style>