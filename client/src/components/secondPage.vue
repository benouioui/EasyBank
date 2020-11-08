<template>
    <div class="px-40 py-20">
        <div>
            <h2 class="text-4xl mb-6 blue">Why choose Easybank ?</h2>
            <p class="text-lg gray">We leverage Open Banking to turn your account into your financial hub. <br/> Control your finances like never before. </p>
        </div>
        <div class="flex justify-between mt-16">
            <div>
                <img src="..\assets\images\icon-online.svg" alt="">
                <h3 class="blue mt-10 text-xl">
                    Online Banking
                </h3>
                <p class="mt-6 w-3/4 grey">
                    Our online web and mobile applications allow you to keep track of your finances wherever you are in the world
                </p>                
            </div>
            <div>
                <img src="..\assets\images\icon-budgeting.svg" alt="">
                <h3 class="blue mt-10 text-xl">
                    Simple Budgeting
                </h3>
                <p class="mt-6 w-3/4 grey">
                    See exactly where your money goes each month. Receive notifications when you're close to hitting your limits.
                </p>                
            </div>
            <div>
                <img src="..\assets\images\icon-onboarding.svg" alt="">
                <h3 class="blue mt-10 text-xl">
                    Fast on Onboarding
                </h3>
                <p class="mt-6 w-3/4 grey">
                    We don't do branches.  Open your account in minutes online and start taking control of your finances right away.
                </p>
            </div>
            <div>
                <img src="..\assets\images\icon-api.svg" alt="">
                <h3 class="blue mt-10 text-xl">
                    Open API
                </h3>
                <p class="mt-6 w-3/4 grey">
                    Manage your savings, investments, pension, and much more from one account. Tracking your money has never been easier.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

.gray {
    color: hsl(233, 8%, 62%);
}

.blue {
    color: hsl(233, 26%, 24%)
}

</style>