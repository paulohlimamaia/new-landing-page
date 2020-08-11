<template>
  <div id="features" class="mb-6">
    <div class="bg-main-white">
      <div class="container mx-auto px-6 pt-32">
        <h1 class="text-center text-black font-semibold text-2xl">Last Episodes</h1>
        <hr class="border border-blue-light" style="width: 10%;" />
        <div class="flex md:flex-no-wrap xs:flex-wrap items-center justify-center mt-24">
          <div class="tabbed justify-center">
            <input type="radio" name="tabs" id="tab-nav-1" checked />
            <label for="tab-nav-1">ALL</label>
            <input type="radio" name="tabs" id="tab-nav-2" />
            <label for="tab-nav-2">DEVELOPMENT</label>
            <input type="radio" name="tabs" id="tab-nav-3" />
            <label for="tab-nav-3">DESIGN</label>
            <input type="radio" name="tabs" id="tab-nav-4" />
            <label for="tab-nav-4">PROJECT MANAGEMENT</label>
            <div class="tabs">
              <br><br>
              <div>
                <h2>HTML</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet nulla tortor, a posuere urna. Praesent urna quam, semper ut ultricies et, mollis ac elit.</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet nulla tortor, a posuere urna. Praesent urna quam, semper ut ultricies et, mollis ac elit. Suspendisse tempor, lacus id consectetur sagittis, lorem odio dignissim nulla, a condimentum sem neque sed ligula. Maecenas id risus eros, eget porttitor metus. Quisque pellentesque neque dignissim nisl pellentesque vitae tempus urna eleifend. Nullam egestas, neque id placerat luctus, nibh velit pharetra nulla, vel pretium justo massa ut elit. Vivamus nec auctor nunc.</p>
              </div>
              <div>
                <h2>CSS</h2>
                <p>Maecenas dictum, urna ut consequat condimentum, est dui commodo diam, ac pretium dui ante eu quam. Curabitur posuere metus nec tellus venenatis placerat. Ut egestas neque in odio vulputate gravida. In at justo ac est laoreet eleifend vel quis arcu. Aliquam erat volutpat. Proin vitae vehicula neque. Nam tempus erat ac ante tincidunt tincidunt. Pellentesque eu nibh sapien. Nunc augue magna, lacinia eget congue eget, mattis id tortor. Fusce id vestibulum neque. Proin tincidunt tellus ut risus lobortis cursus. Duis sit amet urna vel sapien ullamcorper varius.</p>
              </div>
              <div>
                <h2>Javascript</h2>
                <p>Duis luctus dolor ac erat luctus hendrerit. Aenean id congue magna. Proin sit amet elit vel lacus ornare dignissim imperdiet nec odio. Maecenas condimentum egestas lorem et laoreet. Donec ut leo non purus rutrum euismod vel faucibus nunc. Curabitur vel mauris nisi, vitae laoreet erat. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Maecenas ipsum odio, iaculis id vulputate vitae, vestibulum at nunc. Integer non nisl lorem. Quisque lobortis congue semper. Nunc neque nisi, consequat id egestas vitae, porta vel sem.</p>
              </div>
              <div>
                <h2>Output</h2>
                <p>Fusce vel eros eu lectus ultricies fermentum vestibulum adipiscing odio. Suspendisse ultricies, metus nec dapibus pharetra, quam arcu vulputate nisl, a pretium nisi velit id ante. Nunc auctor augue sit amet orci vestibulum id placerat nulla pellentesque. Duis vel quam velit. Ut auctor ipsum quis lacus semper non pretium mi dignissim. Morbi ultrices augue eget nisi hendrerit placerat. Mauris rhoncus urna quis metus congue quis condimentum risus interdum. Nam lobortis lectus et enim laoreet mattis. Integer faucibus ullamcorper erat, at rhoncus leo bibendum sed. Mauris libero urna, placerat non pretium ac, elementum et arcu. Aliquam non tellus diam, vel scelerisque odio. Etiam a quam et enim vehicula feugiat posuere at dui. Phasellus at nisl quam. Integer nisi mi, varius vitae placerat viverra, dapibus vitae massa. Nullam ut orci vitae nisi ornare aliquam in eget orci.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="flex md:flex-no-wrap xs:flex-wrap items-center justify-center lg:mt-64 xs:mt-0">
          <div class="flex-1">
            <div class="px-12 py-12 m-4 text-center">
              <img src="./../assets/compass.svg" alt="compass image" class="h-16 mb-4" />
              <h3 class="mb-4">Compass</h3>
              <p
                class="text-black font-thin text-xs opacity-50"
              >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dignissim urna eu eros facilisis commodo. Pellentesque nec sem.</p>
            </div>
            <div class="px-12 py-12 m-4 text-center">
              <img src="./../assets/canteen.svg" alt="canteen image" class="h-16 mb-4" />
              <h3 class="mb-4">Canteen</h3>
              <p
                class="text-black font-thin text-xs opacity-50"
              >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dignissim urna eu eros facilisis commodo. Pellentesque nec sem.</p>
            </div>
          </div>
          <div class="xs:hidden lg:block md:flex-2 lg:flex-2">
            <img src="./../assets/iphone.png" alt="iphone image" class="h-iphone" />
          </div>
          <div class="flex-1">
            <div class="px-12 py-12 m-4 text-center">
              <img src="./../assets/forest.svg" alt="forest image" class="h-16 mb-4" />
              <h3 class="mb-4">Forest</h3>
              <p
                class="text-black font-thin text-xs opacity-50"
              >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dignissim urna eu eros facilisis commodo. Pellentesque nec sem.</p>
            </div>
            <div class="px-12 py-12 m-4 text-center">
              <img src="./../assets/pines.svg" alt="pines image" class="h-16 mb-4" />
              <h3 class="mb-4">Pines</h3>
              <p
                class="text-black font-thin text-xs opacity-50"
              >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed dignissim urna eu eros facilisis commodo. Pellentesque nec sem.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <svg
      id="curveDownColor"
      xmlns="http://www.w3.org/2000/svg"
      version="1.1"
      width="100%"
      height="100"
      viewBox="0 0 100 100"
      preserveAspectRatio="none"
    >
      <path style="fill: #f8fafc;" d="M0 0 C 50 100 80 100 100 0 Z" />
    </svg>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style scoped>

* {
  box-sizing: border-box;
}

body {
  background: url(https://subtlepatterns.com/patterns/use_your_illusion.png);
  color: #eee;
  font: 1em "PT Sans", sans-serif;
}

.tabbed {
  width: 700px;
  margin: 50px auto;
}

.tabbed > input {
  display: none;
}

.tabbed > label {
  display: block;
  float: left;
  padding: 12px 20px;
  margin-right: 5px;
  cursor: pointer;
  transition: background-color 0.3s;
}

.tabbed > label:hover,
.tabbed > input:checked + label {
  border-bottom: 2px solid black;
}

.tabs {
  clear: both;
  perspective: 600px;
}

.tabs > div {
  width: 700px;
  position: absolute;
  padding: 10px 30px 40px;
  line-height: 1.4em;
  opacity: 0;
  transform: rotateX(-20deg);
  transform-origin: top center;
  transition: opacity 0.3s, transform 1s;
  z-index: 0;
}

#tab-nav-1:checked ~ .tabs > div:nth-of-type(1),
#tab-nav-2:checked ~ .tabs > div:nth-of-type(2),
#tab-nav-3:checked ~ .tabs > div:nth-of-type(3),
#tab-nav-4:checked ~ .tabs > div:nth-of-type(4) {
  transform: rotateX(0);
  opacity: 1;
  z-index: 1;
}

@media screen and (max-width: 700px) {
  .tabbed {
    width: 400px;
  }
  .tabbed > label {
    display: none;
  }
  .tabs > div {
    width: 400px;
    border: none;
    padding: 0;
    opacity: 1;
    position: relative;
    transform: none;
    margin-bottom: 60px;
  }
  .tabs > div h2 {
    border-bottom: 2px solid #4ec6de;
    padding-bottom: 0.5em;
  }
}
</style>
