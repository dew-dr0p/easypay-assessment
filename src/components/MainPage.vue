<script setup lang="ts">
import MainButton from './MainButton.vue';
</script>

<template>
    <div class="absolute top-0 left-0 w-screen overflow-hidden -z-[1]">
        <img src="../assets/Images/gradients.png" alt="">
    </div>
    <section class="py-20 px-48 relative">
        <div class="grid">
            <div class="max-w-[552px] py-10">
                <h3 class=" font-[MADEMellowPERSONALUSE] text-[64px] leading-[72px] text-[#292A29]">Run your <span class="text-[#11453B]">payroll</span> <span class="text-[#B4A572]">easily</span> in <span class="text-[#EA4E4B]">seconds</span></h3>
                <p class="mt-6 text-xl font-normal tracking-[0.2px]">We’ve built an all-inclusive simple solution for individual and businesses to manage staff, pay salaries, bills, and relevant taxes all at once.</p>
                <MainButton text="Start using Free, Forever" class="mt-6 p-4 px-9 rounded-[32px]" />
                <div class="w-fit mt-[4.5rem]">
                    <p class="text-lg text-black leading-6">Download the Eazipay App</p>
                    <div class="inline-flex gap-4 mt-4">
                        <div class="grid p-3 grid-flow-col-dense bg-white rounded-lg items-center shadow-[0px_20px_48px_0px_rgba(170,_170,_170,_0.29)]">
                            <div class="bg-[#F2F1F1] p-3 rounded-full mr-3">
                                <img src="../assets/Images/ic_baseline-apple.png" alt="">
                            </div>
                            <div>
                                <p class="text-xs">Download on the</p>
                                <p class="text-lg font-bold leading-6">Appstore</p>
                            </div>
                        </div>
                        <div class="grid p-3 grid-flow-col-dense bg-white rounded-lg items-center shadow-[0px_20px_48px_0px_rgba(170,_170,_170,_0.29)]">
                            <div class="bg-[#F2F1F1] p-3 rounded-full mr-3">
                                <img src="../assets/Images/logos_google-play-icon.svg" alt="" >
                            </div>
                            <div>
                                <p class="text-xs">Get on</p>
                                <p class="text-lg font-bold leading-6">Google Play</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="absolute w-[52rem] right-0">
                <img src="../assets/Images/MainHero.png" alt="" class="w-[52rem]">
            </div>
        </div>
    </section>
    <section class="">
        <div class="relative -z-[1]">
            <div class="absolute left-0 top-0">
                <img src="../assets/Images/EaziWave.png" alt="">
            </div>
            <div class="absolute left-0 top-0">
                <img src="../assets/Images/MaskGroup.png" alt="">
            </div>
        </div>
        <div class="text-center py-32 px-48">
            <h3 class="font-[MADEMellowPERSONALUSE] text-[64px] leading-[64px] text-[#11453B]">For Individuals and Businesses</h3>
            <p class="text-xl leading-6 tracking-[0.2px] font-normal mt-4">Join 200+ businesses using Eazipay's easy solution.</p>
            <div class="grid grid-flow-col w-fit m-auto my-16">
                <div class="p-16 rounded-2xl text-white text-left max-w-[552px] shadow-[-11px_0px_19px_0px_rgba(23,_23,_23,_0.30),_0px_13px_20px_0px_rgba(23,_23,_23,_0.20)]" style="background: radial-gradient(50% 50.00% at 50% 50.00%, rgba(217, 235, 205, 0.14) 0%, rgba(217, 235, 205, 0.03) 100%), #11453B;">
                    <p class="font-bold text-3xl text-[28px]">Tamper-proof Payroll for LIfe</p>
                    <div class="gap-4 text-lg leading-6 flex flex-col mt-6">
                        <p>Your staff payroll history is kept in one place forever.</p>
                        <p>No more excel sheet or manual records.</p>
                        <p>Download your payroll history anytime you need it.</p>
                    </div>
                </div>
                <div class="p-16 rounded-2xl text-white text-left max-w-[552px] -ml-[264px] shadow-[-11px_0px_19px_0px_rgba(23,_23,_23,_0.30),_0px_13px_20px_0px_rgba(23,_23,_23,_0.20)]" style="background: radial-gradient(50% 50.00% at 50% 50.00%, rgba(217, 235, 205, 0.14) 0%, rgba(217, 235, 205, 0.03) 100%), #11453B;">
                    <p class="font-bold text-3xl text-[28px]">All Payroll, Anytime Anywhere</p>
                    <div class="gap-4 text-lg leading-6 flex flex-col mt-6">
                        <p>Wherever you are Eazipay has got you covered on ALL your Payroll tasks.</p>
                        <p>Whether it is Taxes, Pension insurances HMOs, trustfunds, Eazipay handle all your compliamces in one place and easily, in seconds!</p>
                    </div>
                </div>
                <div class="p-16 rounded-2xl text-white text-left max-w-[552px] -ml-[264px] shadow-[-11px_0px_19px_0px_rgba(23,_23,_23,_0.30),_0px_13px_20px_0px_rgba(23,_23,_23,_0.20)]" style="background: radial-gradient(50% 50.00% at 50% 50.00%, rgba(217, 235, 205, 0.14) 0%, rgba(217, 235, 205, 0.03) 100%), #11453B;">
                    <p class="font-bold text-3xl text-[28px]">Payroll in Seconds</p>
                    <div class="gap-4 text-lg leading-6 flex flex-col mt-6">
                        <p>Never again wil you spend more than 2 minutes on payroll.</p>
                        <p>Just click on your staff annd bulk-pay them at once.</p>
                        <p>Payment is done permanently.</p>
                    </div>
                </div>
            </div>
            <p class="text-xl leading-6 tracking-[0.2px] font-normal max-w-xl m-auto">We are happy to answer your queries. Please, reach us at <span class="text-[#EA4E4B]">hello@myeazipay.com</span> and expect our response shortly after.</p>
        </div>
    </section>
    <section class="text-center mt-24 px-36">
        <h5 class="font-[MADEMellowPERSONALUSE] text-[3.5rem] leading-[4rem] text-[#11453B] mb-4">How Eazipay Works</h5>
        <p class="font-normal text-[1.75rem] text-3xl mb-24">Get started in 3 simple steps.</p>
        <div class="grid grid-flow-col">
            <div class="relative grid place-items-center w-fit">
                <div class="grid place-items-center w-[36rem] h-[36rem] bg-[#F0F7EB] rounded-[50%] border-[0.187px] border-[11453B]">
                    <div class="grid place-items-center w-[32.5rem] h-[32.5rem] bg-[#D9EBCD] rounded-[50%]">
                        <div class="grid place-items-center w-[28rem] h-[28rem] bg-[#11453B] rounded-[50%]"></div>
                    </div>
                </div>
                <img src="../assets/Images/onboarding2.gif" alt="" class="rounded-[64px] absolute w-[21.75rem]">
            </div>
            <div class="relative">
                <img src="../assets/Images/steps1.svg" alt="" class="absolute top-8 -left-14">
                <div class="grid gap-16 max-w-[22.5rem]">
                    <div class="grid gap-4">
                        <button class="text-white text-4xl leading-[48px] font-bold w-16 h-16 bg-[#11453B] rounded-2xl shadow-[0px_20px_48px_0px_rgba(170,_170,_170,_0.29)]">1</button>
                        <h6 class="font-bold text-xl leading-6 tracking-[0.2px]">Create your free account</h6>
                        <p class="leading-6 font-normal">Click here to set up your Eazipay account.</p>
                    </div>
                    <div class="grid gap-4">
                        <button class="text-[#11453B] text-4xl leading-[48px] font-bold w-16 h-16 bg-[#F2F1F1] rounded-2xl">2</button>
                        <h6 class="font-bold text-xl leading-6 tracking-[0.2px]">Add Employee Data</h6>
                        <p class="leading-6 font-normal">Your employee information is 100% safe and secure.</p>
                    </div>
                    <div class="grid gap-4">
                        <button class="text-[#11453B] text-4xl leading-[48px] font-bold w-16 h-16 bg-[#F2F1F1] rounded-2xl">3</button>
                        <h6 class="font-bold text-xl leading-6 tracking-[0.2px]">Prepare your Transaction</h6>
                        <p class="leading-6 font-normal">Run payroll: Bulk Salaries and Compliance are done at once!</p>
                    </div>
                </div>
                <img src="../assets/Images/steps23.svg" alt="" class="absolute top-60 left-20">
            </div>
        </div>
    </section>
    <section class="bg-[#FFE9E7] bg-[url(../assets/Images/Patterns.png)] mt-36 px-48">
        <img src="../assets/Images/Frame25.png" alt="" class="relative -left-10">
        <div class="grid grid-flow-col mt-8 mx-auto w-fit gap-20 pb-36">
            <div class="grid gap-[2.625rem] w-fit">
                <h5 class="font-[MADEMellowPERSONALUSE] text-[3.5rem] leading-[4rem] font-medium text-[#292A29]">Free forever <br>for your <span class="text-[#EA4E4B]">salary <br>payment</span></h5>
                    <div class="w-fit">
                    <p class="text-lg text-black leading-6">Subscribe to the Eazilife today</p>
                    <div class="inline-flex gap-4 mt-4">
                        <div class="grid p-3 grid-flow-col-dense bg-white rounded-lg items-center shadow-[0px_20px_48px_0px_rgba(170,_170,_170,_0.29)]">
                            <div class="bg-[#F2F1F1] p-3 rounded-full mr-3">
                                <img src="../assets/Images/ic_baseline-apple.png" alt="">
                            </div>
                            <div>
                                <p class="text-xs">Download on the</p>
                                <p class="text-lg font-bold leading-6">Appstore</p>
                            </div>
                        </div>
                        <div class="grid p-3 grid-flow-col-dense bg-white rounded-lg items-center shadow-[0px_20px_48px_0px_rgba(170,_170,_170,_0.29)]">
                            <div class="bg-[#F2F1F1] p-3 rounded-full mr-3">
                                <img src="../assets/Images/logos_google-play-icon.svg" alt="" >
                            </div>
                            <div>
                                <p class="text-xs">Get on</p>
                                <p class="text-lg font-bold leading-6">Google Play</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/Images/Frame.png" alt="">
            </div>
        </div>
    </section>
    <section class="relative px-48 mt-0">
        <img src="../assets/Images/Frame3.png" alt="" class="absolute right-0 w-fit -z-[1]">
        <img src="../assets/Images/Frame251.png" alt="" class="absolute left-0 top-20">
        <div class="grid grid-flow-col gap-36 place-items-center mt-[8.25rem] mb-28">
            <div class="grid gap-6 mt-24 w-fit h-fit max-w-md">
                <h5 class="font-[MADEMellowPERSONALUSE] text-[4rem] leading-[4.5rem] text-[#11453B]">Get an Exclusive Demo of Eazipay</h5>
                <p class="text-2xl font-normal">Our greatest priority is to put you and your business first. Let’s show you how we can help.</p>
            </div>
            <div class="p-8 text-center gap-[0.75rem] max-w-[552px] rounded-[2rem] border border-[#E7E8E7] bg-white shadow-[0px_20px_48px_0px_rgba(170,_170,_170,_0.29)]">
                <h6 class="text-[#292A29] font-bold text-[1.75rem] leading-[3rem]">First things first</h6>
                <p class="text-lg leading-6 font-normal text-[#444]">We want to serve you better. Tell us a bit about yourself or company</p>
                <div class="flex p-2 rounded-2xl gap-3 border-[1.15px] border-[#E7E8E7]">
                    <button class="text-white tracking-[0.1px] py-2 w-full bg-[#11453B] rounded-2xl shadow-[0px_20px_48px_0px_rgba(170,_170,_170,_0.29)]">Individual</button>
                    <button class="text-[#11453B] tracking-[0.1px] py-2 w-full bg-[#F2F1F1] rounded-2xl">Company</button>
                </div>
                <form action="#" class="grid gap-3">
                    <input type="text" placeholder="First Name" class="mt-3 p-4 border w-full rounded-2xl border-[#B5B6B5]">
                    <input type="text" placeholder="Last Name" class="mt-3 p-4 border w-full rounded-2xl border-[#B5B6B5]">
                    <input type="email" placeholder="Email" class="mt-3 p-4 border w-full rounded-2xl border-[#B5B6B5]">
                    <input type="text" placeholder="Job Title" class="mt-3 p-4 border w-full rounded-2xl border-[#B5B6B5]">
                    <input type="text" placeholder="Company Size" class="mt-3 p-4 border w-full rounded-2xl border-[#B5B6B5]">
                    <MainButton text="Request Demo" class="w-full mt-5" />
                </form>
            </div>
        </div>
    </section>
    <footer class="py-16 grid grid-flow-col gap-32 px-48 border-t border-[#EAEAEA]">
        <div class="gap-10 grid">
            <img src="../assets/Images/Logo.svg" alt="">
            <div class="gap-2 text-sm font-normal tracking-[0.25px]">
                <p>Copyright © 2023 Eazipay.</p>
                <p>All rights reserved</p>
            </div>
            <div class="flex gap-4">
                <img src="../assets/Images/Instagram.svg" alt="">
                <img src="../assets/Images/Twitter.svg" alt="">
                <img src="../assets/Images/Linkedin.svg" alt="">
                <img src="../assets/Images/Facebook.svg" alt="">
            </div>
        </div>
        <div class="grid grid-flow-col gap-8">
            <div class="grid">
                <h6 class="text-xl leading-6 font-medium tracking-[0.2px] text-[#292A29]">Product</h6>
                <div class="grid gap-3 text-base font-normal text-[#7C7C7C]">
                    <p>Indidual</p>
                    <p>Businesses</p>
                    <p>Request Demo</p>
                    <p>Pricing</p>
                </div>
            </div>
            <div class="grid">
                <h6 class="text-xl leading-6 font-medium tracking-[0.2px] text-[#292A29]">Legal</h6>
                <div class="grid gap-3 text-base font-normal text-[#7C7C7C]">
                    <p>Privacy Policy</p>
                    <p>Terms of Service</p>
                </div>
            </div>
            <div class="grid">
                <h6 class="text-xl leading-6 font-medium tracking-[0.2px] text-[#292A29]">Resources</h6>
                <div class="grid gap-3 text-base font-normal text-[#7C7C7C]">
                    <p>FAQs</p>
                    <p>Blog</p>
                    <p>Career</p>
                    <p>Customer Stories</p>
                </div>
            </div>
            <div class="grid">
                <h6 class="text-xl leading-6 font-medium tracking-[0.2px] text-[#292A29]">Contact us</h6>
                <div class="grid gap-3 text-base font-normal text-[#7C7C7C]">
                    <p>eazipay@gmail.com</p>
                    <p>+234 816 878 9518</p>
                    <input type="text" placeholder="Your email address" class="rounded-2xl pl-4 pt-2 pb-3 bg-[#F2F1F1]">
                    <!-- <label for="input"><img src="../assets/Images/send.svg" alt=""></label> -->
                </div>
            </div>
        </div>
    </footer>
</template>