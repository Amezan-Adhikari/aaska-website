<script>
  import ProfileCard from "./ProfileCard.svelte";
import Title from "./Title.svelte";

</script>

<div class="relative pt-20">
    <img src="/images/bulbula.svg" alt="bubble background" class="absolute top-0 right-0 z-[-1]">
 
    <div class="flex flex-col md:flex-row-reverse">
        <div class="md:w-1/2 md:pt-20 md:px-20 px-7">
            <Title/>
            <div class="h-[2px] bg-gray-300 my-6 hidden md:block"></div>
            <div class="md:flex gap-2 items-center mt-7 hidden ">
                <img src="/images/github.svg" alt="github">
                <a href="https://github.com/AaskaKoirala" class="text-sm md:text-lg text-[#2A5C7B]">https://github.com/AaskaKoirala</a>
            </div>
            <div class="md:flex items-center gap-2 mt-3 hidden">
                <img src="/images/instagram.svg" alt="instargram">
                <a href="https://instagram.com/aaskakoirala" class="text-sm md:text-lg text-[#2A5C7B]">https://instagram.com/aaskakoirala</a>
            </div>


            <div class="md:flex flex-wrap gap-4 mt-20 hidden">
                <button class="flex items-center justify-center text-lg px-5 py-2 rounded-full text-[#A55217] border-2 border-[#A55217] hover:bg-[#A55217] hover:text-white active:scale-95">
                    Resume
                </button>
                <button class="flex items-center justify-center text-lg px-5 py-2 rounded-full text-[#A55217] border-2 border-[#A55217] hover:bg-[#A55217] hover:text-white active:scale-95">
                    Projects
                </button>
                <button class="flex items-center justify-center text-lg px-5 py-2 rounded-full text-white bg-[#1C69DD] hover:bg-white hover:border-2 border-[#1C69DD] hover:text-[#1C69DD] active:scale-95">
                    Connect
                </button>
           
            </div>
        
        </div>

        <div class="relative flex md:w-1/2 justify-center items-center mt-20 md:mt-0 h-[720px] overflow-hidden">
            <img src="/images/profile card bg.svg" alt="profile card background" class="absolute -left-1/3 sm:-left-0 z-[-1]">
            
            <div class="relative">
                <ProfileCard/>
                <img src="/images/bulbula profile.svg" alt="bubbles profile" class="scale-75 absolute -top-5 -right-16 lg:-right-40 lg:scale-100 lg:-top-20">
            </div>
        </div>
    </div>

<div class="px-5 mt-10 md:hidden">
    <h1 class="text-2xl text-[#373737] mb-2">Socials</h1>
    <div class="w-full h-[2px] bg-gray-300"></div>
    
    <div class="flex gap-2 items-center mt-7">
        <img src="/images/github.svg" alt="github">
        <a href="https://github.com/AaskaKoirala" class="text-sm text-[#2A5C7B]">https://github.com/AaskaKoirala</a>
    </div>
    <div class="flex items-center gap-2 mt-3">
        <img src="/images/instagram.svg" alt="instargram">
        <a href="https://instagram.com/aaskakoirala" class="text-sm text-[#2A5C7B]">https://instagram.com/aaskakoirala</a>
    </div>
</div>

<div class="px-5 my-20 md:hidden">
    <h1 class="text-2xl text-[#373737] mb-2">More</h1>
    <div class="w-full h-[2px] bg-gray-300 mb-6"></div>
    
    <div class="flex flex-wrap gap-4">
        <button class="flex items-center justify-center text-lg px-5 py-2 rounded-full text-[#A55217] border-2 border-[#A55217] hover:bg-[#A55217] hover:text-white active:scale-95">
            Resume
        </button>
        <button class="flex items-center justify-center text-lg px-5 py-2 rounded-full text-[#A55217] border-2 border-[#A55217] hover:bg-[#A55217] hover:text-white active:scale-95">
            Projects
        </button>
        <button class="flex items-center justify-center text-lg px-5 py-2 rounded-full text-white bg-[#1C69DD] hover:bg-white hover:border-2 border-[#1C69DD] hover:text-[#1C69DD] active:scale-95">
            Connect
        </button>
   
    </div>

</div>


</div>


<style>
    h1{
        font-family: "Poppins-Bold";
    }
</style>