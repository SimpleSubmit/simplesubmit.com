---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
  <!-- Primary Menu -->
  <nav class="bg-white py-2">
    <div class="mx-auto px-2 sm:px-6 lg:px-14">
      <div class="relative flex items-center justify-between h-16">
        <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
          <!-- Mobile menu button-->
          <button class="inline-flex items-center justify-center p-2 rounded-md text-gray-900 hover:text-white hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
                  aria-expanded="false"
                  onclick="toggleNavbar('sbp-mobile-nav')">
            <span class="sr-only">Open main menu</span>
             <!-- Icon when menu is closed. -->
            <svg class="block h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"  aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" /></svg>
            <!-- Icon when menu is open. -->
            <svg class="hidden h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" /></svg>
          </button>
        </div>
        <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
          <div class="flex-shrink-0 flex items-center">
            <div class="block lg:hidden h-12 w-auto">
              <amp-img src="/assets/images/ss-logo-1.jpg"
                       alt="Simple Submit" width="187"
                       height="48"
                       layout="flex-item"></amp-img>
            </div>
            <div class="hidden lg:block h-12 w-auto">
              <amp-img src="/assets/images/ss-logo-1.jpg"
                       alt="Simple Submit"  width="187"
                       height="48"
                       layout="flex-item"></amp-img>
            </div>
          </div>
          <div class="hidden sm:block ml-auto">
            <div class="flex space-x-4">
              <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
              <a href="terms/index.html"
                 class="text-gray-900 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-semibold">Terms of Services</a>
              <a href="privacy/index.html"
                 class="text-gray-900 hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-semibold">Privacy Policy</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Mobile Menu-->
    <div id="sbp-mobile-nav"
         class="hidden sm:hidden sbp-mobile-nav">
      <div class="px-2 pt-2 pb-3 space-y-1">
        <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
        <a href="terms/index.html"
           class="text-gray-900 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-md text-base font-semibold">Terms of Services</a>
        <a href="privacy/index.html"
           class="text-gray-900 hover:bg-gray-700 hover:text-white block px-3 py-2 rounded-md text-base font-semibold">Privacy Policy</a>
      </div>
    </div>
    <!-- ./Mobile Menu-->
  </nav>

<!-- Top Section -->
  <div class="container mx-auto py-10 px-2 sm:px-0">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
      <div class="col-span-2">
        <h1 class="text-5xl font-bold leading-normal text-brand-primary">Why build an entire backend when all you need is one form.</h1>
        <h6 class="text-2xl pt-2 leading-normal">Simple Submit provides form endpoints as a service, so you can keep your site simple. <br />Simple Submit is a <a href="https://sbprod.net/"
             target="_blank"
             class="text-blue-700">Software Based Product.</a></h6>
      </div>
    </div>
  </div>
  <!-- ./Top Section -->
<div class="container mx-auto px-1 sm:px-14 py-10">
{% highlight html %}
<form action="https://form.simplesubmit.com/formid" method="post">
  <input type="hidden" name="_formmac" value="dsdsdfrjhdfsihdfjhwerjuhdsfadf">
  <label for="name">
  <input type="text" name="name" value="">
  <label for="message">
  <textarea name="message">
  
  </textarea>
  <input type="submit" name="Submit">
</form>
{% endhighlight %}
</div>
  <!-- Code -->
  <div class="bg-brand-primary px-2 sm:px-0">
    <div class="container mx-auto py-6 sm:px-6 lg:py-16 lg:px-8 lg:py-8">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="text-white">
          <h2 class="text-xl font-semibold pb-2">Build your form your way</h2>
          <p class="font-light">You already know HTML and CSS, so build your form exactly the way you want to. We don’t get in your way with JavaScript widgets, WYSIWYG editors, or janky iframes.</p>
        </div>
        <div class="text-white">
          <h2 class="text-xl font-semibold pb-2">Single payments, not subscriptions</h2>
          <p class="font-light">Why develop an entire backend, or take out a monthly subscription just for a simple contact form? Simple Submit provides a one off payment option, good for half a million submits.</p>
        </div>
        <div class="text-white">
          <h2 class="text-xl font-semibold pb-2">Build your form your way</h2>
          <p class="font-light">You already know HTML and CSS, so build your form exactly the way you want to. We don’t get in your way with JavaScript widgets, WYSIWYG editors, or janky iframes.</p>
        </div>
      </div>
    </div>
  </div>
  <!-- ./CTA -->

  <!-- Pricing -->
  <div class="px-2 sm:px-0 bg-gray-300">
    <div class="container mx-auto py-6 sm:px-6 lg:py-16 lg:px-8 lg:py-8">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <div class="col-span-3 text-center">
          <h2 class="font-bold text-3xl">Intended Pricing</h2>
        </div>
        <div class="rounded bg-white p-4">
          <h4 class="text-center font-bold text-lg pb-2">Once Off Payment</h4>
          <h2 class="text-center font-bold"><sup class="text-2xl">$</sup><span class="text-5xl">5</span></h2>
        </div>
      </div>
    </div>
  </div>
  <!-- ./Pricing -->

  <script>
    function toggleNavbar(collapseID) {
      document.getElementById(collapseID).classList.toggle("hidden");
      document.getElementById(collapseID).classList.toggle("block");
    }
  </script>