# Popular Movies
> An app that allows users to discover the most popular movies playing.

[![Crates.io](https://img.shields.io/crates/l/rustc-serialize.svg?maxAge=2592000)]()

The purpose of this project was to built an app, optimized for tablets, to help users discover popular and highly rated movies on the web. It displays a scrolling grid of movie trailers, launches a details screen when a particular movie is selected, allows users to save favorites, play trailers, and read user reviews. This app utilizes core Android user interface components and fetches movie information using themoviedb.org web API.


<img width="40%" src="https://cloud.githubusercontent.com/assets/22068784/18801249/7e116c0e-8196-11e6-99f6-ca888cfc0788.png" /><img width="40%" src="https://cloud.githubusercontent.com/assets/22068784/18801249/7e116c0e-8196-11e6-99f6-ca888cfc0788.png" />

<img width="80%" src="https://cloud.githubusercontent.com/assets/22068784/18801363/38a94654-8197-11e6-87d3-07f25ccdceb8.png" />

### Project review
> In my perspective, you have done a perfect job implementing popular movie stage 1 and the format of your codes is extremely standard and your codes are easy to be understood. Great job for your popular movie stage 1! Hope to see your stage 2 codes soon! :)
> -- <cite>[Udacity Project Reviewer][1]</cite>

[1]:https://review.udacity.com/#!/reviews/229500

### Getting Started
App uses The Movie Database API. You have to enter your API key in order to run the app. You can create your own one very easy! https://www.themoviedb.org/account/signup. When you get it, just set it here:  "popular-movies-app/gradle.properties"

<img src="https://lh5.googleusercontent.com/lcrd9OzPlFfhviXWKaSQflMMsDvOtzKRtdzCWP_vrERg-k3bqgRxeK3vm-vvxJkFOfZQPvO_1qksMCl7PBDlX336ZLftEWFOxpeeqIxid-3RrCayH0klSAMQkG1UvqO6cvB48ho" width="300">

## Gradle
```
compile 'com.android.support:appcompat-v7:23.4.0'
compile 'com.squareup.picasso:picasso:2.5.2'
compile 'com.android.support:support-v4:23.4.0'
compile "com.android.support:recyclerview-v7:23.0.1"
compile project(":volley")
```
Use Git to checkout the source code for Volley, preferably to the filesystem where your Android project lives.
```
git clone https://android.googlesource.com/platform/frameworks/volley
```

## Powered by
<img src="https://assets.tmdb.org/assets/c9dbe2292fb5eea61788571fbd96fa67/images/v4/logos/208x226-stacked-blue.png" width="80">

## License
```
Copyright 2016 Julia Kozhukhovskaya

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
