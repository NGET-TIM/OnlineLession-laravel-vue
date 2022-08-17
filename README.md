<p align="center">Laravel Vue App Configurations</p>

## Install Laravel
- composer  composer create-project laravel/laravel example-app

## Install Package And composer
- npm install vue@next vue-router vue-loaders laravel-mix

## Config webpack.mix.js 
-  const mix = require('laravel-mix')
    
    mix
    .js('resources/js/app.js', 'public/js')
    .vue()
    .postCss('resources/css/app.css', 'public/js')
## Register vuejs           
- resource/js/app.js       
  import {createApp} from 'vue'
  import App from 
  createApp(App).mount("#myApp")

## Call app.js to index.blade.php


<script src="{{ mix('js/app.js') }}"></script>
## Route any for all routes
Route::get('/{any?}', IndexController::class)->where('any', '.*');
