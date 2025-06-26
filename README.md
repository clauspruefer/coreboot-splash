# Coreboot-Splash :gem:
A Stylish Splash Boot-Logo For Usage With Coreboot.

Use the following howto to integrate into *ThinkPad T420* or *ThinkPad X220*:
https://github.com/nenadstoisavljevic/t420-coreboot-guide.

## 1. Colourful Bootslash Logo

The Bootsplash Logo uses the following images:

- <a href="https://github.com/Thrilleratplay/bootsplash-coreboot">Black / White Coreboot Rabbit</a>
- <a href="https://www.vecteezy.com/vector-art/24739467-free-vector-abstract-colorful-geometric-shape-design-background">Colorful Background Image</a> by Indriyan Saputra

Visit <a href="https://www.vecteezy.com/free-vector/illustration">Illustration Vectors by Vecteezy</a> to get free / professional illustrations.

## 2. Coreboot Config

Copy `bootsplash.jpg` to `~/work/coreboot/bootsplash.jpg` and reference it inside config (`make nconfig`).

```
General
  [*] Add a bootsplash image
      bootsplash.jpg
```
## 3. Image

![Display Image](https://github.com/clauspruefer/coreboot-splash/blob/main/bootsplash.jpg?raw=true)
