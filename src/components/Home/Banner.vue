<style scoped>
/* banner 不需設定 1920px 寬度 */
/* .banner {
max-width: 1920px;
}*/

.banner img.pc {
    object-fit: cover;
    max-width: 1154px;
    width: 100%;
    height: 792px;
}

.banner img.mobile {
    object-fit: cover;
    max-width: 375px;
    width: 100%;
    height: 285px;
}

@keyframes pulse {
    0% {
        box-shadow: 0 0 0 0 rgba(33, 37, 41, 1);
    }

    70% {
        box-shadow: 0 0 0 10px rgba(33, 37, 41, 0);
    }

    100% {
        box-shadow: 0 0 0 50px rgba(33, 37, 41, 0);
    }
}

.btn-pluse {
    animation: pulse 2s infinite;
    box-shadow: 0 0 0 0 rgba(33, 37, 41, 0.4);
}
</style>
<script setup>
import SocialIcon from '@/components/Common/socialIcon.vue';
</script>

<template>
    <section class="banner position-relative">
        <div class="container-fluid mx-auto">
            <div class="d-flex flex-lg-row-reverse row">
                <div class="col-12 col-lg-8">
                    <div class="d-flex justify-content-center justify-content-lg-end">
                        <img src="@/assets/images/Home/hero-lg.png" class="d-none d-lg-block pc" />
                        <img src="@/assets/images/Home/hero-sm.png" class="d-lg-none banner mobile" />
                    </div>
                </div>
                <!-- mobile start-->
                <div class="col d-lg-none">
                    <div class="d-flex justify-content-center my-7">
                        <div class="benner-text-mobile text-center">
                            <h1 class="fw-semibold text-primary-700 mb-4">Hi！我是 Amber</h1>
                            <div class="fs-5 mb-5 text-primary-600">
                                <p class="mb-2">具有 10 年經驗的資深軟體工程師</p>
                                <p>擅長將企業業務邏輯和客製化需求轉化為系統架構</p>
                            </div>
                            <!-- <SocialIcon class="mt-4 mt-lg-9" /> -->
                            <a class="btn btn-dark btn-pluse" href="https://www.cake.me/me/xu3woli"
                                target="_blank">關於我</a>
                        </div>
                    </div>
                </div>
                <!-- mobile end-->
            </div>
        </div>
        <!-- pc start-->
        <div class="container d-lg-block d-none">
            <div class="align-items-center d-flex h-100 position-absolute top-0">
                <div class="benner-text-pc text-start">
                    <h1 class="fw-semibold text-primary-700 mb-4">Hi！我是 Amber</h1>
                    <div class="fs-5 mb-5 text-primary-600">
                        <!--  -->
                        <p class="mb-2">具有 10 年經驗的軟體工程師</p>
                        <p>擅長將企業業務邏輯和客製化需求轉化為系統架構</p>
                        <!--  -->
                    </div>
                    <!-- <SocialIcon class="mt-9 mt-lg-9" /> -->
                    <a class="btn btn-dark btn-pluse" href="https://www.cake.me/me/xu3woli" target="_blank">關於我</a>
                </div>
            </div>
        </div>
        <!-- pc end -->
    </section>
</template>