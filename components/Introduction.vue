<template>
    <div class=" flex flex-col items-center space-y-4 ">
        <svg width="33" height="32" viewBox="0 0 33 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_1_119)">
                <path
                    d="M13.7913 24.485C13.7023 24.337 13.5766 24.2146 13.4264 24.1296C13.2761 24.0446 13.1064 23.9999 12.9338 24H5.5C5.23478 24 4.98043 23.8946 4.79289 23.7071C4.60536 23.5196 4.5 23.2652 4.5 23V7C4.5 6.73478 4.60536 6.48043 4.79289 6.29289C4.98043 6.10536 5.23478 6 5.5 6H27.5C27.7652 6 28.0196 6.10536 28.2071 6.29289C28.3946 6.48043 28.5 6.73478 28.5 7V23C28.5 23.2652 28.3946 23.5196 28.2071 23.7071C28.0196 23.8946 27.7652 24 27.5 24H20.0662C19.8936 23.9999 19.7239 24.0446 19.5736 24.1296C19.4234 24.2146 19.2977 24.337 19.2087 24.485L17.3575 27.515C17.2687 27.6631 17.143 27.7856 16.9927 27.8707C16.8424 27.9558 16.6727 28.0005 16.5 28.0005C16.3273 28.0005 16.1576 27.9558 16.0073 27.8707C15.857 27.7856 15.7313 27.6631 15.6425 27.515L13.7913 24.485Z"
                    stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                <path
                    d="M16.5 16.5C17.3284 16.5 18 15.8284 18 15C18 14.1716 17.3284 13.5 16.5 13.5C15.6716 13.5 15 14.1716 15 15C15 15.8284 15.6716 16.5 16.5 16.5Z"
                    fill="white" />
                <path
                    d="M11 16.5C11.8284 16.5 12.5 15.8284 12.5 15C12.5 14.1716 11.8284 13.5 11 13.5C10.1716 13.5 9.5 14.1716 9.5 15C9.5 15.8284 10.1716 16.5 11 16.5Z"
                    fill="white" />
                <path
                    d="M22 16.5C22.8284 16.5 23.5 15.8284 23.5 15C23.5 14.1716 22.8284 13.5 22 13.5C21.1716 13.5 20.5 14.1716 20.5 15C20.5 15.8284 21.1716 16.5 22 16.5Z"
                    fill="white" />
            </g>
            <defs>
                <clipPath id="clip0_1_119">
                    <rect width="32" height="32" fill="white" transform="translate(0.5)" />
                </clipPath>
            </defs>
        </svg>
        <div class=" text-lg"> AI Chatbot</div>

        <div class=" bg-white bg-opacity-10 flex items-center space-x-10 font-light py-4 px-5 rounded-2xl" v-for="item in 3"
            :key="item">
            <div class=" text-sm"> Lorem ipsum, dolor sit amet <br> consectetur </div>
            <svg class=" h-3" viewBox="0 0 8 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M0.888062 1.52467L7.13805 7.77466L0.888062 14.0246" stroke="white" stroke-width="1.25"
                    stroke-linecap="round" stroke-linejoin="round" />
            </svg>

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

<style lang="scss" scoped></style>