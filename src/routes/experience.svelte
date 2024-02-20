<script>
    import FaRegCalendarAlt from "svelte-icons/fa/FaRegCalendarAlt.svelte";
    import FaMapMarkerAlt from "svelte-icons/fa/FaMapMarkerAlt.svelte";
    import GoChevronDown from 'svelte-icons/go/GoChevronDown.svelte'
</script>

<div class="flex w-full h-full flex-row" id="experience">
    <div class="w-[20%] h-full">
        <img src="img-3.png" alt="" class="w-full h-full object-cover" />
    </div>
    <div class="py-8 px-16 flex w-[80%] h-full flex-col justify-between">
        <div class="flex flex-col gap-8 w-full">
            <span class="text-4xl">My Work Experience</span>
            <div class="flex flex-row w-full justify-between items-between h-full gap-8">
                <div class="flex w-1/2 flex-col">
                    <div class="flex flex-col w-full mt-8 gap-4">
                        <div class="flex flex-col gap-1">
                            <span class="text-xl">MBBS Internship</span>
                            <span class="text-lg font-[600]"
                                >Dayanand Medical College and Hospital</span
                            >
                            <div class="flex flex-row gap-12 items-center">
                                <div class="flex flex-row items-center gap-2">
                                    <div class="w-4 h-4">
                                        <FaRegCalendarAlt />
                                    </div>
                                    <span class="text-base"
                                        >April 2022 &dash; May 2023</span
                                    >
                                </div>
                                <div class="flex flex-row items-center gap-2">
                                    <div class="w-4 h-4">
                                        <FaMapMarkerAlt />
                                    </div>
                                    <span class="text-base">Ludhiana</span>
                                </div>
                            </div>
                        </div>
                        <div class="flex flex-col gap-1 w-[60%]">
                            <ul class="pl-5 list-disc">
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >Community Medicine</span
                                        >
                                        <span>12 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >General Medicine</span
                                        >
                                        <span>6 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]">Psychiatry</span>
                                        <span>2 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]">Paediatrics</span>
                                        <span>3 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >General Surgery</span
                                        >
                                        <span>6 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >Anaesthesiology</span
                                        >
                                        <span>2 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]">Obs & Gynae</span>
                                        <span>7 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]">Orthopaedics</span>
                                        <span>2 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >Trauma/Casualty</span
                                        >
                                        <span>2 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]">Ophthalmology</span
                                        >
                                        <span>2 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >Radio diagnosis</span
                                        >
                                        <span>2 weeks</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >Respiratory Medicine</span
                                        >
                                        <span>1 week</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]"
                                            >Forensic Medicine</span
                                        >
                                        <span>1 week</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]">Yoga</span>
                                        <span>1 week</span>
                                    </div>
                                </li>
                                <li>
                                    <div class="flex flex-row justify-between">
                                        <span class="font-[500]">Dermatology</span>
                                        <span>1 week</span>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="flex w-1/2 flex-col">
                    <div class="flex flex-col h-full w-full mt-8 gap-1">
                        <span class="text-xl">Junior Resident Paediatrics</span>
                        <span class="text-lg font-[600]">Punjab Institue of Medical Sciences</span>
                        <div class="flex flex-row justify-between items-center">
                            <div class="flex flex-row items-center gap-2">
                                <div class="w-4 h-4">
                                    <FaMapMarkerAlt />
                                </div>
                                <span class="text-base">Jalandhar</span>
                            </div>
                        </div>
                    </div>
                    <div class="w-full flex justify-end">
                        <a class="w-10 h-10 bg-black text-white p-1" href="#skills">
                            <GoChevronDown />
                        </a>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</div>
