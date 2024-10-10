<script setup>

const router = useRouter()
const donate = () => {
    router.push({ path: '/donate' })
}

</script>
<template>
    <div class="py-2 h-25 fixed bottom-0 left-0 right-0 bg-white/70  backdrop-blur dark:bg-slate-800 space-y-1">
        <div class="flex flex-row items-center justify-center  gap-3">
            <a class="" href="https://github.com/unilei/aipan-netdisk-search">
                <img class="w-5 h-5" src="@/assets/skill-icons--github-dark.svg" alt="github">
            </a>
            <el-button link color="#ffffff" @click="donate()">
                <img class="w-5 h-5" src="@/assets/donation/dashang.svg" alt="打赏">
            </el-button>
        </div>
    </div>
</template>
<style scoped></style>