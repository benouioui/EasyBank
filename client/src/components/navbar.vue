<template>
    <div>
        <div class="w-full" id="lgNav">
            <div class="flex justify-center py-6 items-center relative">
                <div class="flex-1 justify-self-start">
                    <img src="..\assets\images\logo.svg" alt="">
                </div>
                <div class="flex-1 flex justify-around">
                    <a class="link" href="#">Home</a>
                    <a class="link" href="#">About</a>
                    <a class="link" href="#">Contact</a>
                    <a class="link" href="#">Blog</a>
                    <a class="link" href="#">Careers</a>
                </div>
                <div class="flex-1 flex justify-center">
                    <button class="text-white gradient p-3 px-10" style="border-radius: 3em"> Request Invite </button>
                </div>
            </div>
        </div>
        <smNavbar id="smNav" class="hidden w-full"/>
    </div>
</template>

<script>

import smNavbar from './smNavbar'

export default {
    components: {
        smNavbar
    }
    
}
</script>

<style scoped>

a.link
{
    position: relative;
}

a.link:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 0;
  bottom: -150%;
  left: 0;  
  background: rgb(49,211,92);
  background: linear-gradient(90deg, rgba(49,211,92,1) 0%, rgba(43,183,218,1) 100%);
  visibility: hidden;
  transition: all 0.1s ease-in-out;
}

a.link:hover:before {
  visibility: visible;
  height: 3px;
}

.gradient {
    background: rgb(49,211,92);
    background: linear-gradient(90deg, rgba(49,211,92,1) 0%, rgba(43,183,218,1) 100%);
}

.gradient:hover {
    background: rgb(129,228,155);
    background: linear-gradient(90deg, rgba(129,228,155,1) 0%, rgba(126,211,232,1) 100%);
}

@media (max-width: 400px) {
  #smNav {
    display:block;
  }

  #lgNav {
      display: none;
  }
}
</style>