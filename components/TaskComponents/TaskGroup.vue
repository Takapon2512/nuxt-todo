<template>
    <div class="flex mt-4 px-4">
        <div class="w-[320px] bg-gray-100 shadow p-2">
            <div class="flex justify-between">
                <h3 class="font-semibold">タスク1</h3>
                <button>
                    <img src="/svg/more_horiz.svg" alt="">
                </button>
            </div>
            <button class="flex justify-center bg-white mt-4 w-full rounded-md">
                <div class="p-2">
                    <span class="block mb-1">
                        <img class="block m-auto" src="/svg/add.svg" alt="タスク追加">
                    </span>
                    <p class="text-sm text-blue-500">
                        タスク追加
                    </p>
                </div>
            </button>
            <!-- 詳細のタスクを繰り返し表示 -->
        </div>
    </div>
</template>