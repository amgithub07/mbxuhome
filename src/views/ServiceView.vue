<style>
@import url('https://fonts.googleapis.com/css2?family=Tourney:ital,wght@0,100..900;1,100..900&display=swap');

.font-tourney {
    font-family: "Tourney", sans-serif;
}

.bg-service {
    /* 「服務流程」區塊背景的黑灰對角設計，可嘗試改用 linear-gradient 線性漸層方式來處理，因使用圖片無法達到設計稿完全對角的效果 */
    background: linear-gradient(318deg, #1E1E1E 0%, #1E1E1E 49.97%, #000000 50%);
    /* background: linear-gradient(315deg, #1E1E1E 0%, #1E1E1E 49.97%, #000000 50%); */
    /* background-image: url("../../src/assets/images/process-bg.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center; */
}

.bg-service-item {
    background: linear-gradient(330deg, #1E1E1E 0%, #1E1E1E 49.97%, #000000 50%);
    /* background-image: url("../../src/assets/images/service-item-bg.png"); */
    /* background-repeat: no-repeat;
    background-size: cover;
    background-position: center; */
}
</style>

<script setup>
import ServiceItem from '@/components/Service/items.vue';
import ServiceCase from '@/components/Service/cases.vue';
</script>
<template>
    <div class="service">

        <section class="my-80 my-sm-120">
            <h2 class="fs-2 fw-semibold mb-7 text-center text-primary-700 title-deco mb-80">服務項目</h2>
            <ServiceItem />
        </section>
        <section class="bg-service py-80 py-sm-120">
            <div class="text-primary-50">
                <h2 class="fs-2 fw-semibold text-center title-deco text-white mb-7 mb-lg-80">服務流程</h2>
                <div class="container">
                    <div class="d-flex justify-content-center row">
                        <ol class="col-12 col-lg-6">
                            <li
                                class="align-items-center bg-primary-600 border border-1 border-primary-500 d-flex flex-column flex-sm-row px-6 py-4 rounded-1">
                                <div class="display-2 font-tourney me-sm-2 text-primary-500">1</div>
                                <div class="ms-0 ms-md-6">
                                    <h3 class="text-center text-md-start text-primary-50 text-sm-start">初步接洽</h3>
                                    <p class="mb-0 fs-5 text-primary-300">透過表單或其他社群軟體與我聯絡</p>
                                    <p class="mb-4 mb-md-0 fs-5 text-primary-300">根據難易度與複雜度，後續可能需要電話/線上討論</p>
                                </div>
                            </li>
                            <!--  -->
                            <span
                                class="d-block fs-2 material-symbols-outlined my-4 text-center text-primary-600">arrow_downward</span>
                            <li
                                class="align-items-center bg-primary-600 border border-1 border-primary-500 d-flex flex-column flex-sm-row px-6 py-4 rounded-1">
                                <div class="display-2 font-tourney me-sm-2 text-primary-500">2</div>
                                <div class="ms-0 ms-md-6">
                                    <h3 class="text-center text-md-start text-primary-50 text-sm-start">需求釐清</h3>
                                    <p class="mb-0 fs-5 text-primary-300">透過訪談與問卷，解析客戶需求，並針對痛點給予實際建議</p>
                                </div>
                            </li>
                            <!--  -->
                            <span
                                class="d-block fs-2 material-symbols-outlined my-4 text-center text-primary-600">arrow_downward</span>
                            <li
                                class="align-items-center bg-primary-600 border border-1 border-primary-500 d-flex flex-column flex-sm-row px-6 py-4 rounded-1">
                                <div class="display-2 font-tourney me-sm-2 text-primary-500">3</div>
                                <div class="ms-0 ms-md-6">
                                    <h3 class="text-center text-md-start text-primary-50 text-sm-start">委託簽約</h3>
                                    <p class="mb-0 fs-5 text-primary-300">透過表單或其他社群軟體與我聯絡</p>
                                    <p class="mb-4 mb-md-0 fs-5 text-primary-300">根據難易度與複雜度，後續可能需要電話/線上討論</p>
                                </div>
                            </li>
                            <!--  -->
                            <span
                                class="d-block fs-2 material-symbols-outlined my-4 text-center text-primary-600">arrow_downward</span>
                            <li
                                class="align-items-center bg-primary-600 border border-1 border-primary-500 d-flex flex-column flex-sm-row px-6 py-4 rounded-1">
                                <div class="display-2 font-tourney me-sm-2 text-primary-500">4</div>
                                <div class="ms-0 ms-md-6">
                                    <h3 class="text-center text-md-start text-primary-50 text-sm-start">版本呈現</h3>
                                    <p class="mb-0 fs-5 text-primary-300">根據合約內容進行設計或開發</p>
                                </div>
                            </li>
                            <!--  -->
                            <span
                                class="d-block fs-2 material-symbols-outlined my-4 text-center text-primary-600">arrow_downward</span>
                            <li
                                class="align-items-center bg-primary-600 border border-1 border-primary-500 d-flex flex-column flex-sm-row px-6 py-4 rounded-1">
                                <div class="display-2 font-tourney me-sm-2 text-primary-500">5</div>
                                <div class="ms-0 ms-md-6">
                                    <h3 class="text-center text-md-start text-primary-50 text-sm-start">來回修正</h3>
                                    <p class="mb-0 fs-5 text-primary-300">依據合約規定之修正次數進行，次數計算以 mail 為準</p>
                                </div>
                            </li>
                            <!--  -->
                            <span
                                class="d-block fs-2 material-symbols-outlined my-4 text-center text-primary-600">arrow_downward</span>
                            <li
                                class="align-items-center bg-primary-600 border border-1 border-primary-500 d-flex flex-column flex-sm-row px-6 py-4 rounded-1">
                                <div class="display-2 font-tourney me-sm-2 text-primary-500">6</div>
                                <div class="ms-0 ms-md-6">
                                    <h3 class="text-center text-md-start text-primary-50 text-sm-start">終版確認</h3>
                                    <p class="mb-0 fs-5 text-primary-300">雙方同意後即為最終版</p>
                                </div>
                            </li>
                            <!--  -->
                            <span
                                class="d-block fs-2 material-symbols-outlined my-4 text-center text-primary-600">arrow_downward</span>
                            <li
                                class="align-items-center bg-primary-600 border border-1 border-primary-500 d-flex flex-column flex-sm-row px-6 py-4 rounded-1">
                                <div class="display-2 font-tourney me-sm-2 text-primary-500">7</div>
                                <div class="ms-0 ms-md-6">
                                    <h3 class="text-center text-md-start text-primary-50 text-sm-start">結案</h3>
                                    <p class="mb-0 fs-5 text-primary-300">客戶簽署驗收單，並於約定日期支付尾款</p>
                                </div>
                            </li>
                        </ol>
                    </div>
                </div>
            </div>
        </section>
        <section class="my-80 my-sm-120">
            <h2 class="fs-2 fw-semibold text-center text-primary-700 title-deco mb-7 mb-lg-80">價格表</h2>
            <div class="container">
                <div class="row row-gap-4">
                    <div class="col-12 col-lg-4">
                        <div class="bg-primary-100 border-0 rounded-3 shadow">
                            <div class="align-items-center d-flex flex-wrap p-5">
                                <svg width="42" height="42" viewBox="0 0 80 80" fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path
                                        d="M54.1333 38.3666L59.3667 33.1333L46.8667 20.6333L41.6333 25.8666L27.8333 12.1C25.2333 9.49997 21 9.49997 18.4 12.1L12.0667 18.4333C9.46667 21.0333 9.46667 25.2666 12.0667 27.8666L25.8333 41.6333L10.5 57C10.1667 57.3333 10 57.7333 10 58.2V68.3333C10 69.2666 10.7333 70 11.6667 70H21.8C22.2333 70 22.6667 69.8333 22.9667 69.5L38.3667 54.1L52.1333 67.8666C56.5333 72.2666 61.3333 68.1 61.5667 67.8666L67.9 61.5333C70.5 58.9333 70.5 54.7 67.9 52.1L54.1333 38.3666ZM30.6 36.9L16.8 23.1333L23.1 16.8L27.3333 21.0333L25.7667 22.6666C25.1434 23.2899 24.7933 24.1352 24.7933 25.0166C24.7933 25.8981 25.1434 26.7434 25.7667 27.3666C26.3899 27.9899 27.2352 28.34 28.1167 28.34C28.9981 28.34 29.8434 27.9899 30.4667 27.3666L32.0667 25.7666L36.9 30.6L30.6 36.9ZM56.8667 63.2L43.1 49.4333L49.4333 43.1L54.2667 47.9333L52.6667 49.5333C52.3581 49.8419 52.1133 50.2083 51.9462 50.6115C51.7792 51.0147 51.6933 51.4469 51.6933 51.8833C51.6933 52.3197 51.7792 52.7519 51.9462 53.1551C52.1133 53.5583 52.3581 53.9247 52.6667 54.2333C52.9753 54.5419 53.3416 54.7867 53.7449 54.9537C54.1481 55.1207 54.5802 55.2067 55.0167 55.2067C55.4531 55.2067 55.8853 55.1207 56.2885 54.9537C56.6917 54.7867 57.0581 54.5419 57.3667 54.2333L58.9667 52.6333L63.2 56.8666L56.8667 63.2ZM69.0333 23.4666C69.3423 23.1583 69.5875 22.792 69.7548 22.3887C69.922 21.9855 70.0081 21.5532 70.0081 21.1166C70.0081 20.6801 69.922 20.2478 69.7548 19.8446C69.5875 19.4413 69.3423 19.075 69.0333 18.7666L61.2333 10.9666C59.6667 9.39997 57.5 9.99997 56.5333 10.9666L50.4333 17.0666L62.9333 29.5666L69.0333 23.4666Z"
                                        fill="#C1C1C1" />
                                </svg>
                                <span class="fs-3 fw-semibold ms-2 text-primary-600">平面設計</span>
                                <hr class="flex-grow-1 mx-3 border-primary-400 opacity-100">
                                <div class="fs-2 fw-bold text-primary-800 me-2">6,000
                                    <span class="text-primary-600 fs-6 fw-normal">起</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-4">
                        <div class="bg-primary-100 border-0 rounded-3 shadow">
                            <div class="align-items-center d-flex flex-wrap p-5">
                                <svg width="42" height="42" viewBox="0 0 80 80" fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" clip-rule="evenodd"
                                        d="M42.2185 23.3013L56.4435 37.5296L50.2739 56.0415L17.3716 65.8237L33.9674 49.228C34.9437 48.2516 34.9437 46.6687 33.9674 45.6924C32.9911 44.7161 31.4081 44.7161 30.4318 45.6924L14.3491 61.7751L24.7826 30.4803L42.2185 23.3013ZM24.855 30.2629C24.8549 30.2634 24.8548 30.2638 24.8546 30.2642L24.855 30.2629ZM7.47136 66.5959L20.1108 28.6841C20.111 28.6837 20.1111 28.6833 20.1113 28.6828C20.3151 28.0708 20.6482 27.5098 21.0879 27.0378C21.5279 26.5655 22.0643 26.1933 22.6608 25.9466L40.6186 18.5528C40.6183 18.5529 40.6189 18.5527 40.6186 18.5528C41.4398 18.2139 42.3437 18.1252 43.215 18.2987C44.0866 18.4722 44.8873 18.8999 45.5161 19.5278L60.1972 34.2123C60.1971 34.2121 60.1973 34.2124 60.1972 34.2123C60.788 34.8031 61.203 35.5471 61.3951 36.3603C61.5872 37.1736 61.5489 38.0244 61.2847 38.8173L54.9347 57.8706L54.9342 57.8722C54.7051 58.5579 54.3143 59.1783 53.7947 59.6809C53.2751 60.1835 52.6421 60.5536 51.9492 60.7597L13.0221 72.3332C12.233 72.5675 11.3941 72.5812 10.5979 72.3722C9.8017 72.1633 9.07809 71.7399 8.50581 71.1483C7.93352 70.5567 7.53446 69.8194 7.35206 69.0167C7.16969 68.2142 7.21101 67.3767 7.47136 66.5959ZM56.6616 37.7478C56.6614 37.7475 56.6611 37.7472 56.6608 37.7469L56.6616 37.7478Z"
                                        fill="#C1C1C1" />
                                    <path
                                        d="M61.3421 10.6068L69.2221 18.4868C69.8143 19.0533 70.2873 19.7324 70.6134 20.4843C70.9395 21.2361 71.1122 22.0455 71.1213 22.865C71.1303 23.6844 70.9756 24.4975 70.6662 25.2563C70.3567 26.0152 69.8989 26.7046 69.3194 27.2841C68.7399 27.8635 68.0505 28.3214 67.2916 28.6309C66.5328 28.9403 65.7197 29.095 64.9003 29.086C64.0808 29.0769 63.2714 28.9042 62.5196 28.5781C61.7677 28.252 61.0886 27.7789 60.5221 27.1868L52.6388 19.3068C51.5269 18.1446 50.9142 16.5933 50.932 14.985C50.9498 13.3767 51.5966 11.8392 52.7339 10.7019C53.8712 9.56462 55.4086 8.91782 57.0169 8.90003C58.6252 8.88225 60.1799 9.4949 61.3421 10.6068Z"
                                        fill="#C1C1C1" stroke="white" stroke-width="1.5" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                    <path fill-rule="evenodd" clip-rule="evenodd"
                                        d="M34.6892 35.7149C35.5495 35.3629 36.4712 35.1858 37.4007 35.1939C38.3301 35.2019 39.2487 35.3951 40.1027 35.7619C40.9567 36.1288 41.7291 36.6621 42.3749 37.3306C43.65 38.6508 44.3555 40.4191 44.3396 42.2544C44.3236 44.0898 43.5874 45.8455 42.2896 47.1434C40.9917 48.4412 39.236 49.1774 37.4007 49.1933C35.5653 49.2093 33.7971 48.5037 32.4769 47.2286C31.8083 46.5829 31.275 45.8105 30.9082 44.9565C30.5413 44.1024 30.3482 43.1839 30.3401 42.2544C30.332 41.325 30.5091 40.4032 30.8611 39.5429C31.2131 38.6827 31.7328 37.9011 32.3901 37.2439C33.0473 36.5866 33.8289 36.0668 34.6892 35.7149ZM37.3659 39.1937C36.9676 39.1903 36.5725 39.2662 36.2038 39.417C35.8352 39.5678 35.5002 39.7906 35.2185 40.0723C34.9368 40.354 34.7141 40.6889 34.5632 41.0576C34.4124 41.4263 34.3365 41.8213 34.34 42.2197C34.3434 42.618 34.4262 43.0117 34.5834 43.3777C34.7406 43.7437 34.9692 44.0747 35.2557 44.3515C35.8215 44.8979 36.5793 45.2003 37.3659 45.1935C38.1525 45.1867 38.9049 44.8712 39.4612 44.3149C40.0174 43.7587 40.3329 43.0063 40.3397 42.2197C40.3466 41.4331 40.0442 40.6753 39.4977 40.1095C39.221 39.8229 38.8899 39.5944 38.5239 39.4372C38.1579 39.2799 37.7642 39.1972 37.3659 39.1937Z"
                                        fill="#C1C1C1" />
                                </svg>

                                <span class="fs-3 fw-semibold ms-2 text-primary-600">UI設計</span>
                                <hr class="flex-grow-1 mx-3 border-primary-400 opacity-100">
                                <div class="fs-2 fw-bold text-primary-800 me-2">15,000
                                    <span class="text-primary-600 fs-6 fw-normal">起</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-4">
                        <div class="bg-primary-100 border-0 rounded-3 shadow">
                            <div class="align-items-center d-flex flex-wrap p-5">
                                <svg width="42" height="42" viewBox="0 0 80 80" fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path
                                        d="M25.6178 32.3054L16.1841 40.0003L25.6178 47.6952C25.9306 47.9462 26.1897 48.2554 26.3799 48.6048C26.5701 48.9543 26.6877 49.3372 26.7261 49.7314C26.7644 50.1256 26.7226 50.5233 26.6031 50.9016C26.4836 51.2799 26.2889 51.6313 26.03 51.9356C25.7711 52.2398 25.4532 52.4909 25.0947 52.6743C24.7362 52.8577 24.3442 52.9698 23.9412 53.0042C23.5382 53.0385 23.1323 52.9945 22.7468 52.8745C22.3613 52.7545 22.0039 52.561 21.6952 52.3052L9.43706 42.3053C9.09182 42.0238 8.81405 41.6713 8.62342 41.273C8.4328 40.8747 8.33398 40.4402 8.33398 40.0003C8.33398 39.5604 8.4328 39.126 8.62342 38.7276C8.81405 38.3293 9.09182 37.9769 9.43706 37.6954L21.6952 27.6955C22.3205 27.1938 23.1231 26.9544 23.928 27.0293C24.7328 27.1043 25.4748 27.4876 25.9923 28.0958C26.5098 28.7039 26.7608 29.4876 26.6906 30.2761C26.6205 31.0646 26.2349 31.794 25.6178 32.3054ZM70.5642 37.6954L58.3061 27.6955C57.9974 27.4396 57.64 27.2461 57.2545 27.1262C56.869 27.0062 56.4631 26.9621 56.0601 26.9965C55.6571 27.0308 55.2651 27.1429 54.9066 27.3263C54.5481 27.5097 54.2302 27.7608 53.9713 28.0651C53.7124 28.3693 53.5177 28.7207 53.3982 29.0991C53.2787 29.4774 53.2369 29.8751 53.2752 30.2693C53.3136 30.6635 53.4312 31.0464 53.6214 31.3958C53.8116 31.7453 54.0707 32.0544 54.3835 32.3054L63.8172 40.0003L54.3835 47.6952C54.0707 47.9462 53.8116 48.2554 53.6214 48.6048C53.4312 48.9543 53.3136 49.3372 53.2752 49.7314C53.2369 50.1256 53.2787 50.5233 53.3982 50.9016C53.5177 51.2799 53.7124 51.6313 53.9713 51.9356C54.2302 52.2398 54.5481 52.4909 54.9066 52.6743C55.2651 52.8577 55.6571 52.9698 56.0601 53.0042C56.4631 53.0385 56.869 52.9945 57.2545 52.8745C57.64 52.7545 57.9974 52.561 58.3061 52.3052L70.5642 42.3053C70.9095 42.0238 71.1873 41.6713 71.3779 41.273C71.5685 40.8747 71.6673 40.4402 71.6673 40.0003C71.6673 39.5604 71.5685 39.126 71.3779 38.7276C71.1873 38.3293 70.9095 37.9769 70.5642 37.6954ZM49.2198 15.1806C48.8415 15.046 48.4398 14.9856 48.0377 15.0029C47.6355 15.0202 47.2408 15.1149 46.8761 15.2816C46.5113 15.4483 46.1837 15.6837 45.9119 15.9744C45.6401 16.265 45.4295 16.6053 45.2921 16.9756L28.9479 60.975C28.6709 61.7226 28.7084 62.5473 29.0522 63.2678C29.396 63.9883 30.018 64.5457 30.7815 64.8175C31.1167 64.9387 31.4713 65.0005 31.8286 65C32.4578 65.0001 33.0717 64.8106 33.5871 64.4573C34.1025 64.104 34.4943 63.6039 34.7092 63.025L51.0534 19.0256C51.191 18.6553 51.2527 18.2621 51.235 17.8684C51.2173 17.4747 51.1205 17.0883 50.9502 16.7313C50.78 16.3742 50.5395 16.0535 50.2426 15.7874C49.9457 15.5214 49.5981 15.3152 49.2198 15.1806Z"
                                        fill="#C1C1C1" />
                                </svg>
                                <span class="fs-3 fw-semibold ms-2 text-primary-600">前端開發</span>
                                <hr class="flex-grow-1 mx-3 border-primary-400 opacity-100">
                                <div class="fs-2 fw-bold text-primary-800 me-2">22,000
                                    <span class="text-primary-600 fs-6 fw-normal">起</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section style="background-color: #FAFAFA;" class="py-80 py-sm-120">
            <h2 class="fs-2 fw-semibold text-center text-primary-700 title-deco mb-7 mb-lg-80">客戶案例</h2>
            <ServiceCase />
        </section>
        <section class="my-80 my-sm-120">
            <h2 class=" fs-2 fw-semibold text-center text-primary-700 title-deco mb-7 mb-lg-80">常見問題</h2>
            <div class="container">
                <ul class="row row-gap-3 justify-content-center">
                    <li class="col-12 col-lg-5">
                        <div class="border p-4 rounded-3 h-100">
                            <p class="text-primary-700 fs-4 fw-bold mb-3">時程很趕的話可以加快作業嗎？</p>
                            <p class="text-primary-600 fs-5 lh-base">每提早一天，只要支付總報價的 5%，我們即會視為急件為您趕工！</p>
                        </div>
                    </li>
                    <li class="col-12 col-lg-5">
                        <div class="border p-4 rounded-3 h-100">
                            <p class="text-primary-700 fs-4 fw-bold mb-3">白天可以開會討論嗎？</p>
                            <p class="text-primary-600 fs-5 lh-base">每週一三五的白天，可以約定開會時間！</p>
                        </div>
                    </li>
                    <li class="col-12 col-lg-5">
                        <div class="border p-4 rounded-3 h-100">
                            <p class="text-primary-700 fs-4 fw-bold mb-3">有實際開發的網站可以參考嗎？</p>
                            <p class="text-primary-600 fs-5 lh-base">請填寫表單或來信索取，部分合作有簽保密協定，無法於網路上公開喔。</p>
                        </div>
                    </li>
                    <li class="col-12 col-lg-5">
                        <div class="border p-4 rounded-3 h-100">
                            <p class="text-primary-700 fs-4 fw-bold mb-3">提供比稿服務嗎？</p>
                            <p class="text-primary-600 fs-5 lh-base">只要支付費用，設計提供比稿服務，但切版與前端開發恕不提供該服務內容。</p>
                        </div>
                    </li>
                </ul>
            </div>
        </section>
    </div>
</template>