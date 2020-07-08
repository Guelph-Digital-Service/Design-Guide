---
layout: colours
title: Colour
group: styles
permalink: /styles/color
description: Colour styles define how colour is used in the design system.

brand-colours:
  - name: --cog-primary
    value: '#00a5e1'
  - name: --cog-secondary
    value: '#58a618'
  - name: --cog-comp1
    value: '#003150'
  - name: --cog-comp2
    value: '#6D5047'
  - name: --cog-comp3
    value: '#1A2155'
  - name: --cog-comp4
    value: '#BA6F2E'
  - name: --cog-comp5
    value: '#752864'

basic-colours:
  - name: --color-navy
    value: '#21759b'
  - name: --color-navy-dark
    value: '#195794'

neutral-colours:
  - name: --color-white
    value: '#fff'
  - name: --color-gray-02
    value: '#f9f9f9'
  - name: --color-gray-04
    value: '#f5f5f5'
  - name: --color-gray-07
    value: '#eee'
  - name: --color-gray-10
    value: '#e5e5e5'
  - name: --color-gray-13
    value: '#ddd'
  - name: --color-gray-27
    value: '#bbb'
  - name: --color-gray-50
    value: '#808080'
  - name: --color-gray-60
    value: '#666'
  - name: --color-gray-67
    value: '#595959'
  - name: --color-gray-73
    value: '#444'
  - name: --color-gray-80
    value: '#333'
  - name: --color-gray-86
    value: '#282828'
  - name: --color-gray-93
    value: '#131313'
  - name: --color-black
    value: '#000'

---

Colours in the Guelph Design System are defined in the `colour-palette.css` file. Site specific colours such as font-colours or header colours are set in the `variables.css` file and are based off these available colours. As a general rule, any new component, element, or design pattern should reference these colours by utilizing their relative variable name and **not** by using a raw RGB or hex value.


&nbsp;
