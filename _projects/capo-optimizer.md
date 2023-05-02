---
layout: page
title: Capo Optimizer
---

This is an algorithm I came up with that determines the best fret to put a guitar capo on for any given set of keys. The inspiration for this came to me when I played electric guitar with an orchestra and the songs involved many key changes. Figuring out which capo position would lead to the easiest way to transpose all of the keys in a song wasn't always a simple process, but I figured I could automate it.

Once I figured out the algorithm, this project turned into my "hello world" challenge for learning new languages. I have implemented this in various ways in all of these languages.

* Ruby in [Rails](https://github.com/RileyMathews/rhythm-ninja-capo-optimizer-rails) and [AWS Lambda](https://github.com/RileyMathews/rhythm-ninja-capo-optimizer-lambda-ruby) flavors.
* [Rust](It has been very interesting to be able to compare languages in this way. The core logic (seen here in the Kotlin version) is not overly complicated or long but uses just enough maps and filters to make it a solid challenge to be able to grasp the fundamental concepts of a new language.)
* [Kotlin](https://github.com/RileyMathews/rhythm-ninja-capo-optimizer-lambda-kotlin) which was for a time deployed as an API using AWS API Gateway and Lambda
* [C#/Dotnet](https://github.com/RileyMathews/rhythm-ninja-capo-optimizer-dotnet)

It has been very interesting to be able to compare languages in this way. The core logic (seen [here in the Kotlin version](https://github.com/RileyMathews/rhythm-ninja-capo-optimizer-lambda-kotlin/blob/57756a11104b16e074848c11e0e8dc845a376888/src/main/kotlin/com/rileymathews/services/CapoService.kt#L8)) is not overly complicated or long but uses just enough maps and filters to make it a solid challenge to be able to grasp the fundamental concepts of a new language.
