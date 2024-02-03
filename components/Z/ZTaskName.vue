<template>
    <div class="flex justify-between px-4 mt-8">
        <div>
            <h2 class="text-lg font-semibold">営業チーム</h2>
        </div>
        <div class="flex">
            <ul class="flex mr-4">
                <li class="mr-[-8px] z-40">
                    <span class="block bg-blue-400 h-8 w-8 rounded-full"></span>
                </li>
                <li class="mr-[-8px] z-30">
                    <span class="block bg-red-400 h-8 w-8 rounded-full"></span>
                </li>
                <li class="mr-[-8px] z-20">
                    <span class="block bg-yellow-400 h-8 w-8 rounded-full"></span>
                </li>
                <li class="z-10">
                    <span class="block bg-slate-400 h-8 w-8 rounded-full"></span>
                </li>
            </ul>
            <ul class="flex">
                <li class="flex w-8 h-8 p-1 mr-1 bg-stone-200 shadow rounded-sm">
                    <button>
                        <img src="/svg/filter.svg" alt="">
                    </button>
                </li>
                <li class="flex w-8 h-8 p-1 mr-1 bg-stone-200 shadow rounded-sm">
                    <button>
                        <img src="/svg/search.svg" alt="">
                    </button>
                </li>
                <li class="flex w-8 h-8 p-1 bg-stone-200 shadow rounded-sm">
                    <button>
                        <img src="/svg/more_horiz.svg" alt="">
                    </button>
                </li>
            </ul>
        </div>
    </div>
</template>