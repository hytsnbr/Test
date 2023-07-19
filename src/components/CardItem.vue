<template>
<div
  class="bg-[#853998] rounded-[3px] p-2.5 flex flex-row gap-2.5 items-center justify-center relative overflow-hidden"
  style="box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25)"
>
  <div
    class="rounded-[3px] flex flex-row gap-2.5 items-center justify-center shrink-0 relative overflow-hidden"
  >
    <div
      class="bg-[#d9d9d9] rounded-[3px] shrink-0 w-[100px] h-[100px] relative"
      style="box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25)"
    ></div>

    <img
      class="rounded-[3px] shrink-0 w-24 h-24 absolute left-[calc(50%_-_48px)] top-[calc(50%_-_48px)]"
      src="canvas-02.png"
    />
  </div>

  <div
    class="bg-[rgba(217,217,217,0.25)] rounded-[3px] pt-[15px] pr-1.5 pb-[15px] pl-1.5 flex flex-col gap-[30px] items-center justify-center shrink-0 relative overflow-hidden"
  >
    <div
      class="text-[#000000] text-center relative w-[140px] h-5 flex items-center justify-center"
      style="font: 400 12px 'Inter', sans-serif"
    >
      Test Placeholder
    </div>

    <div
      class="flex flex-row gap-4 items-center justify-center shrink-0 relative"
    >
      <div
        class="shrink-0 w-[76px] h-5 relative"
        style="box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25)"
      >
        <div
          class="bg-ストリーミングボタン rounded-[3px] w-[76px] h-5 absolute left-0 top-0"
        >
          <div
            class="text-[#ffffff] text-center absolute left-[calc(50%_-_38px)] top-[calc(50%_-_8px)] w-[76px] h-4 flex items-center justify-center"
            style="font: 400 12px 'Inter', sans-serif"
          >
            Button
          </div>
        </div>
      </div>

      <div
        class="shrink-0 w-[76px] h-5 relative"
        style="box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25)"
      >
        <div
          class="bg-購入ボタン rounded-[3px] w-[76px] h-5 absolute left-0 top-0"
        >
          <div
            class="text-[#ffffff] text-center absolute left-[calc(50%_-_38px)] top-[calc(50%_-_8px)] w-[76px] h-4 flex items-center justify-center"
            style="font: 400 12px 'Inter', sans-serif"
          >
            Button
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

  </div>
</template>

<style lang="scss" scoped>
.card {
  background: #853998;
  border-radius: 0.1875rem;
  padding: 0.625rem;
  display: flex;
  flex-direction: row;
  gap: 0.625rem;
  align-items: center;
  justify-content: center;
  position: relative;
  box-shadow: 0rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
  overflow: hidden;
}
.left {
  border-radius: 0.1875rem;
  display: flex;
  flex-direction: row;
  gap: 0.625rem;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  position: relative;
  overflow: hidden;
}
.jacket {
  background: #d9d9d9;
  border-radius: 0.1875rem;
  flex-shrink: 0;
  width: 6.25rem;
  height: 6.25rem;
  position: relative;
  box-shadow: 0rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
}
.canvas-img {
  border-radius: 0.1875rem;
  flex-shrink: 0;
  width: 6rem;
  height: 6rem;
  position: absolute;
  left: calc(50% - 3rem);
  top: calc(50% - 3rem);
  box-shadow: 0rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
}
.right {
  background: rgba(217, 217, 217, 0.25);
  border-radius: 0.1875rem;
  padding: 0.9375rem 0.375rem 0.9375rem 0.375rem;
  display: flex;
  flex-direction: column;
  gap: 1.875rem;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  position: relative;
  overflow: hidden;
}
.test-placeholder {
  color: #000000;
  text-align: center;
  font: 400 0.75rem "Inter", sans-serif;
  position: relative;
  width: 8.75rem;
  height: 1.25rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
.button-holder {
  display: flex;
  flex-direction: row;
  gap: 1rem;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  position: relative;
}
.buttons {
  flex-shrink: 0;
  width: 4.75rem;
  height: 1.25rem;
  position: relative;
  box-shadow: 0rem 0.25rem 0.25rem 0rem rgba(0, 0, 0, 0.25);
}
.button {
  background: var(--ストリーミングボタン, #01a9e8);
  border-radius: 0.1875rem;
  width: 4.75rem;
  height: 1.25rem;
  position: absolute;
  left: 0rem;
  top: 0rem;
}
.button-text {
  color: #ffffff;
  text-align: center;
  font: 400 0.75rem "Inter", sans-serif;
  position: absolute;
  left: calc(50% - 2.375rem);
  top: calc(50% - 0.5rem);
  width: 4.75rem;
  height: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
.button2 {
  background: var(--購入ボタン, #ff73b8);
  border-radius: 0.1875rem;
  width: 4.75rem;
  height: 1.25rem;
  position: absolute;
  left: 0rem;
  top: 0rem;
}
</style>
