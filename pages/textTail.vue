<template>
  <div>
    <!-- 第一部分 -->
    <section>
      <!-- Navbar -->
      <nav class="relative container mx-auto p-6">
        <div class="flex items-center justify-between">
          <!-- logo -->
          <div class="pt-2">
            <img src="../assets/image/img/logo.svg" alt="" />
          </div>
          <!-- 菜单部分 -->
          <!-- 到md宽度就会弹性布局 负责不显示 -->
          <div class="hidden md:flex flex space-x-6">
            <a href="#" class="hover:text-darkGrayishBlue">Pricing</a>
            <a href="#" class="hover:text-darkGrayishBlue">Product</a>
            <a href="#" class="hover:text-darkGrayishBlue">About Us</a>
            <a href="#" class="hover:text-darkGrayishBlue">Careers</a>
            <a href="#" class="hover:text-darkGrayishBlue">Community</a>
          </div>
          <!-- 按钮 -->
          <a
            href="#"
            class="hidden md:block text-white p-3 px-6 pt-2 bg-brightRed rounded-full baseline hover:bg-brightRedLight"
            >Get Started</a
          >
        </div>
      </nav>
      <!-- 主要部分 -->
      <div
        class="container flex flex-col-reverse md:flex-row items-center px-6 mx-auto mt-10 space-y-0 md:space-y-0"
      >
        <!-- 左边 -->
        <div class="flex flex-col mb-32 space-y-12 md:w-1/2">
          <h1
            class="max-x-md text-4xl font-bold text-center md:text-5xl md:text-left"
          >
            Bring everyone together to build better products
          </h1>
          <p class="max-w-sm text-center text-darkGrayishBlue md:text-left">
            Manage makes it simple for software teams to play day-to-day tasks
          </p>
          <div class="flex justify-content md:justify-start">
            <a
              href="#"
              class="p-3 px-6 pt-2 text-white bg-brightRed rounded-full baseline hover:bg-brightRedLight"
              >Get Started</a
            >
          </div>
        </div>
        <!-- 右边 -->
        <div class="md:w-1/2">
          <img src="../assets/image/img/illustration-intro.svg" alt="" />
        </div>
      </div>
    </section>

    <!-- 第二部分 -->
    <section id="features">
      <div
        class="container flex flex-col px-4 mx-auto mt-10 space-y-10 md:space-y-0 md:flex-row"
      >
        <!-- whats diffferent -->
        <!-- space-y-12 margin-top和margin-bottom都是3rem 48px -->
        <div class="flex flex-col space-y-12 md:w-1/2">
          <!-- max-w-md 设置元素的最大宽度是28rem -->
          <h2 class="max-w-md text-4xl font-bold text-center md:text-left">
            Whats different about manage?
          </h2>
          <p class="max-w-sm text-center text-darkGrayishBlue md:text-left">
            Our software is tailor-made for modern product teams
          </p>
        </div>
        <!-- number list -->
        <div class="flex flex-col space-y-8 md:w-1/2">
          <!-- item 1 -->
          <!-- space-x-数字 通过margin-left和margin-right控制元素水平间距,间距为数字*4 -->
          <div
            class="flex flex-col space-y-3 md:space-y-0 md:space-x-6 md:flex-row"
          >
            <!-- heading -->
            <!-- rounded-l-full设置左边上下两个角都是圆的 -->
            <div class="rounded-l-full bg-brightRedSupLight md:bg-transparent">
              <div class="flex items-center space-x-2">
                <!--px-4 py-2  rounded-full制作药丸形状-->
                <div
                  class="px-4 py-2 text-white rounded-full md:py-1 bg-brightRed"
                >
                  01
                </div>
                <!-- text-base 字体16px 行高24px-->
                <h3 class="text-base font-bold md:mb-4 md:hidden">
                  Track company-wide
                </h3>
              </div>
            </div>
            <div>
              <!-- 这个h3通常不显示  在中等屏幕大小才会显示md:block-->
              <!--text-lg 字体18px 行高28px  -->
              <h3 class="hidden mb-4 font-bold text-lg md:block">
                Track company-wide
              </h3>
              <p class="text-darkGrayishBlue">
                See how your day-to-day tasks fit into the wider version.Go from
                the mail to track your progess.
              </p>
            </div>
          </div>
          <!-- item 2 -->
          <div
            class="flex flex-col space-y-3 md:space-y-0 md:space-x-6 md:flex-row"
          >
            <!-- heading -->
            <div class="rounded-l-full bg-brightRedSupLight md:bg-transparent">
              <div class="flex items-center space-x-2">
                <div
                  class="px-4 py-2 text-white rounded-full md:py-1 bg-brightRed"
                >
                  02
                </div>

                <h3 class="text-base font-bold md:mb-4 md:hidden">
                  Advanced report
                </h3>
              </div>
            </div>
            <div>
              <h3 class="hidden mb-4 font-bold text-lg md:block">
                Advanced report
              </h3>
              <p class="text-darkGrayishBlue">
                See how your day-to-day tasks fit into the wider version.Go from
                the mail to track your progess.
              </p>
            </div>
          </div>
          <!-- item 3 -->
          <div
            class="flex flex-col space-y-3 md:space-y-0 md:space-x-6 md:flex-row"
          >
            <!-- heading -->
            <div class="rounded-l-full bg-brightRedSupLight md:bg-transparent">
              <div class="flex items-center space-x-2">
                <div
                  class="px-4 py-2 text-white rounded-full md:py-1 bg-brightRed"
                >
                  03
                </div>

                <h3 class="text-base font-bold md:mb-4 md:hidden">
                  Everything you need
                </h3>
              </div>
            </div>
            <div>
              <h3 class="hidden mb-4 font-bold text-lg md:block">
                Everything you need
              </h3>
              <p class="text-darkGrayishBlue">
                See how your day-to-day tasks fit into the wider version.Go from
                the mail to track your progess.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="testimonials">
      <div class="max-w-6xl px-5 mx-auto mt-32 text-center">
        <!-- heading -->
        <h2 class="text-4xl font-bold text-center">Whats different</h2>
        <!-- md:space-x-6各个模块之间间隔为6*4个px -->
        <div class="flex flex-col mt-24 md:flex-row md:space-x-6">
          <!-- 推荐1 -->
          <div
            class="flex flex-col items-center p-6 space-y-6 rounded-lg bg-veryLightGray md:w-1/3"
          >
            <img
              src="../assets/image/img/avatar-anisha.png"
              class="w-16 -mt-14"
              alt=""
            />
            <h5 class="text-lg font-bold">Anisha</h5>
            <p class="text-sm text-darkGrayishBlue">
              "Manage has supercharged out team's workflow"
            </p>
          </div>
          <!-- 推荐2 -->
          <div
            class="hidden md:flex flex-col items-center p-6 space-y-6 rounded-lg bg-veryLightGray md:w-1/3"
          >
            <img
              src="../assets/image/img/avatar-ali.png"
              class="w-16 -mt-14"
              alt=""
            />
            <h5 class="text-lg font-bold">Ali</h5>
            <p class="text-sm text-darkGrayishBlue">
              "We have been able to cancle so many other description since using
              this app"
            </p>
          </div>
          <!-- 推荐3 -->
          <!-- hidden md:flex 在小屏幕会隐藏，中等屏幕才显示 -->
          <div
            class="hidden md:flex flex-col items-center p-6 space-y-6 rounded-lg bg-veryLightGray md:w-1/3"
          >
            <img
              src="../assets/image/img/avatar-richard.png"
              class="w-16 -mt-14"
              alt=""
            />
            <h5 class="text-lg font-bold">Richard</h5>
            <p class="text-sm text-darkGrayishBlue">
              "Manage has supercharged out team's workflow"
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script></script>
<style scoped></style>
