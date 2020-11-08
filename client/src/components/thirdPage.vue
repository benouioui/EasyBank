<template>
    <div class="py-20 px-40">
        <h1 class="text-4xl blue mb-12"> Latest Articles</h1>
        <div class="grid grid-cols-4 gap-8">
            <div class="bg-white">
                <img src="..\assets\images\image-currency.jpg" class="rounded h-48 w-full" alt="">
                <div class="px-6">
                    <p class="text-sm gray mb-3 mt-6" style="font-size: 0.70em">By Claire Robinson</p>
                    <h2 class="text-xl txthover cursor-pointer blue mb-3">Receive money in any currency with no fees</h2>
                    <p class="gray text-sm">The world is becoming smaller and we're becoming more mobile. So why should you be forced to receive money in a single...</p>
                </div>                
            </div>
            <div class="bg-white pb-6">
                <img src="..\assets\images\image-restaurant.jpg" class="rounded h-48 w-full" alt="">
                <div class="px-6">
                    <p class="text-sm gray mb-3 mt-6" style="font-size: 0.70em">By Wilson Hutton</p>
                    <h2 class="text-xl txthover cursor-pointer blue mb-3">Treat yourself without worrying about money</h2>
                    <p class="gray text-sm">Our simple budgeting features allows you to separate out your spending and set realistic limits each month. That means you...</p>
                </div>
            </div>
            <div class="bg-white pb-6">
                <img src="..\assets\images\image-plane.jpg" class="rounded h-48 w-full" alt="">
                <div class="px-6">
                    <p class="text-sm gray mb-3 mt-6" style="font-size: 0.70em">By Wilson Hutton</p>
                    <h2 class="text-xl txthover cursor-pointer blue mb-3">Take your Easybank card wherever you go</h2>
                    <p class="gray text-sm">We want you to enjoy your travels. This is why we don't charge any fees on purchases while you're abroad. We'll even show you...</p>
                </div>
            </div>
            <div class="bg-white pb-6">
                <img src="..\assets\images\image-confetti.jpg" class="rounded h-48 w-full" alt="">
                <div class="px-6">
                    <p class="text-sm gray mb-3 mt-6" style="font-size: 0.70em">By Claire Robinson</p>
                    <h2 class="text-xl txthover cursor-pointer blue mb-3">Our invite only beta accounts are now live</h2>
                    <p class="gray text-sm">After a lot of hard work by the whole team, we're excited to launch our closed beta. It's easy to request an invite through the site...</p>
                </div>
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

.txthover:hover{
    color: rgba(49,211,92, 0.6)
}

</style>