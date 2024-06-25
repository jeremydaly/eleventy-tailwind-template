---
title: Home
layout: home
tags: page
modified: 2022-01-09 00:00:00
order: 1
---

<h1 class="pt-24 pb-6 text-center">
	<span class="text-8xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500">
		Hello world!
	</span>
</h1>
<h2 class="pb-12 text-4xl font-bold text-center text-gray-500">
	{{ config.siteTitle }}
</h2>

<div class="container max-w-lg mx-auto text-xl text-center">
	<p>Starter template for building <a href="https://www.11ty.dev/" target="_blank">Eleventy</a> static sites with <a href="https://tailwindcss.com/" target="_blank">Tailwind CSS</a> automatically generating the corresponding styles and writing them to a static CSS file.</p>
	<p class="pt-3"><a href="https://github.com/jeremydaly/eleventy-tailwind-template#readme" class="text-2xl text-transparent bg-clip-text bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500">View the README</a></p>
</div>

{% include "navigation.njk" %}
