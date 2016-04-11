class:
background-image: url(img/s0.jpg)

---
name: about
class: left
background-image: url(img/about.jpg)

.right-column[

Open Minded

|> Science

|> Craftsman

.footnote[
<i class="fa fa-github-square fa-2x"></i> [cmg-dev](https://github.com/cmg-dev)

<i class="fa fa-twitter-square fa-2x"></i> [@codethonian](https://twitter.com/codethonian)
]
]

???
Coder in natural Environment

---
name: motivation
class: left
background-image: url(img/motivation.jpg)

.regular[
# Motivation

]

.footnote[
**Read the [Paper](http://www-01.ibm.com/common/ssi/cgi-bin/ssialias?infotype=PM&subtype=XB&htmlfid=GBE03620USEN)**
]
???

---
name: iot
class: left
background-image: url(img/iot.jpg)

.regular[
## Meet the IoT I - Problems

trust bla bla...

Internet of Bullshit reference...
]

---
name: iot
class: left
background-image: url(img/iot_development.jpg)

.regular[
## Worlds Collide
]

---
name: iot
class: left
background-image: url(img/iot_comparison.jpg)

.regular[
## Worlds Collide
]
???
The application of old world approaches to this field.

Apply "as a Service" does not increase product quality


---
name: iot
class: left
background-image: url(img/universe_1.jpg)

.regular[
## Use Cases

![bullshit1](img/bullshit1.jpg)
]

---
name: iot
class: left
background-image: url(img/iot_design_rules.jpg)

.regular[
## Design Rules
]

---
name: regular
class: left
background-image: url(img/bg1.png)

.right-column[

**IBM's conclusion**

``` plain
This first report of our study shows that a low-cost,
private-by-design “democracy of devices” will emerge
that will enable new digital economies and create new
value, while offering consumers and enterprises
fundamentally better products and user experiences.
```
]

---
name: regular
class: left
background-image: url(img/bg1.png)

.right-column[
# End of chapter I
]

---
name: nerves
class: left
background-image: url(img/electronics_1_rpi_vs_ardiuno_0.jpg)

---
name: nerves
class: left
background-image: url(img/electronics_1_rpi_vs_ardiuno_1.jpg)

---
name: nerves
class: left
background-image: url(img/electronics_1_rpi_vs_ardiuno_2.jpg)

---
name: nerves
class: left
background-image: url(img/embedded_linux_is_pain.jpg)

---
class: left
background-image: url(img/electronics_0_nerves-vs-raspbian.jpg)

.right-column[
]

---
class: left
background-image: url(img/electronics_1_partitioning.jpg)

.right-column[
]

---
class: left
background-image: url(img/universe_0.jpg)

.right-column[
## Y Elixir?

```elixir
  Functional
  |> Concurrent
  |> Pragmatic
  |> Fun
```
]

---
name: nerves
class: left
background-image: url(img/nerves_intro.jpg)

.footnote[
<i class="fa fa-rocket fa-2x"></i> [Homepage](http://nerves-project.org/)

<i class="fa fa-twitter-square fa-2x"></i> [@NervesProject](http://twitter.com/NervesProject)

<i class="fa fa-github-square fa-2x"></i> [Contribute!](https://github.com/nerves-project)
]

???
platform

Using a lean, custom cross-compiled linux, nerves boots directly to the battle hardened BEAM VM, starting your application in seconds.

framework

Most devices need to get on a network, get discovered, update firmware, and deal with I/O of various kinds. You're not on your own.

tooling

Cross-compliation can be a total drag. Our tools make it smooth as silk. Go from "mix new" to running code on your device in minutes.

---
class: left
background-image: url(img/nerves_build.jpg)

.right-column[
]

---
name: inverse
class: left
background-image: url(img/bakeware_0.jpg)

.example_page[

# Nerves and Buildroot

Nerves relies upon buildroot to build an embedded distribution

Find it [here](www.buildroot.org).

Buildroot is pain!
]

---
name: inverse
class: left
background-image: url(img/bakeware_1.jpg)

.right-column[
# Bakeware

**a tool and service to build your cross compiled firmware**

Configure, compile and share systems,
toolchains and firmware

Find it [here](http://www.bakeware.io/)
]

---
name: inverse
class: left
background-image: url(img/tools_0.jpg)

.example_page[
# Using bakeware

**Download a system**
```elixir
bake system get
```

**Download a toolchain**
```elixir
bake toolchain get
```
]

---
name: demo
class: left
background-image: url(img/solo_0.jpg)

.left-column[
# Livecoding Fun

**Demo time...**
]

---
name: inverse
class: left
background-image: url(img/tools_0.jpg)

.example_page[
# Using bakeware

**Compile firmware**
```elixir
bake firmware
```

**Burn to SD**
```elixir
bake burn
```
]

---
name: inverse
class: left
background-image: url(img/videos.jpg)

.example_page[
<i class="fa fa-youtube-play fa-2x"></i> [Embedded Elixir in Action](https://www.youtube.com/watch?v=kpzQrFC55q4)

<i class="fa fa-youtube-play fa-2x"></i> [Getting Started with Nerves](https://www.youtube.com/watch?v=kWXrct6nnGg)

<i class="fa fa-youtube-play fa-2x"></i> [SumoBots!](https://www.youtube.com/watch?v=tCg1LakJF3g&index=6&list=PLA9E5Lsig6GTBPb2BRf_2ONIcnRTU5Iy0)

]
