---
layout: post
title: "Renderman is not ray tracing --> Six Myths About Ray Tracing"
description: ""
category: 
tags: []
---
{% include JB/setup %}

> 1. Ray Tracing is what they use in animated movies
> 
> Almost all animated movies are rendered using RenderMan, a program developed and maintained by Pixar.
> 
> RenderMan has a huge array of tools but by far the bulk of the work is done via a normal Scanline Renderer which supports dynamic subdivision and programmable shaders - much like is seen in modern video games. Whole scenes are rendered purely using this system and only for particular effects are the alternatives rolled out.
> 
> For global illumination, reflections, and other complicated effects RenderMan provides a type of Photon Mapping. The scene is subdivided recursively into blocks and photons emitted. Then there is a Ray Collection phase that happens independently for each block.
> 
> This system allows them to work on scenes with large polygon and texture data which normally would not fit in main memory (the main reason standard ray tracing was not an option).
> 
> Pixar show us that great looking results don't automatically mean Ray Tracing, which has major issues with memory and cache.:

link: [Six Myths About Ray Tracing](http://theorangeduck.com/page/six-myths-about-ray-tracing)