<template>
  <div class="w-full bg-white p-8 mt-8 mb-4">
    <div class="w-full flex flex-wrap pb-4 border-b">
      <div class="w-1/2">
        <p class="text-gray-400 text-sm font-light">12 July 1995</p>
      </div>
      <div class="w-1/2">
        <a href="#" class="float-right text-sm font-light hover:underline">Graphic</a>
      </div>
    </div>

    <div class="w-full py-6">
      <h1 class="text-4xl font-bold hover:underline"><a href="#">Lorem ipsum dolor sit amet consectetur.</a></h1>
    </div>

    <div class="article">
      <p>
        Now that we have our view and component layer, we need something to manage state and the lifecycle of our application. Redux is
        also a clear winner here.
      </p>
      <p>
        Alongside React, Facebook presented a design pattern for one way data flow called Flux. Flux largely delivered on its promise of
        simplifying state management, but it also brought with it more questions, such as how to store that state and where to do Ajax
        requests. To answer those questions, countless frameworks were built on top of the Flux pattern: Fluxible, Reflux, Alt, Flummox,
        Lux, Nuclear, Fluxxor and many, many more. One Flux-like implementation eventually caught the community’s attention, and for
        good reasons: Redux.
      </p>

      <blockquote>
        One thing to be careful is the natural instinct to try and abstract away the Redux boilerplate. There’s good reasons behind all
        those pieces. Make sure you tried it and understand the <strong>“why”</strong> before trying to blindly improve on it.
      </blockquote>

      <h2>Why Javascript?</h2>
      <p>
        JavaScript is the standard language of the web platform.
        Learning it will allow you to build any app you want for any device or
        platform you want. Watch this 1 minute video to learn more about what
        JavaScript can do for you:
      </p>

      <h3>The essentials in order:</h3>

      <ul>
        <li>
          <span class="fst-italic">Newbie friendly:</span>
          Make a Star Wars Game with Hour of Code (free website)
        </li>
        <li>
          <span class="fst-italic">Newbie friendly:</span>
          “JavaScript for Cats”, Max Ogden (free website)
        </li>
        <li>
          <span class="fst-italic">Newbie friendly:</span>
          FreeCodeCamp’s 10-hour Basic JavaScript track You can come back to FCC for
            more practice while you explore the rest of these resources. I recommend that you dedicate time to study other resources
            and do some fresh FCC exercises every day. There are hundreds of hours of exercises, in total, covering a lot more than
            just JavaScript.
        </li>
        <li>
          <span class="fst-italic">Newbie friendly:</span>
          “JavaScript for Cats”, Max Ogden (free website)
        </li>
        <li>
          “Eloquent JavaScript: Second Edition”, Marijn Haverbeke (book with free online edition)
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {

}
</script>
