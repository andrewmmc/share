# Why we build our UI library?
Show Me The Code Meetup #9 • 2019

Andrew Mok - Software Engineer, Frontend

[andrew.mok@lalamove.com](andrew.mok@lalamove.com)

## Background
* Inconsistencies thoughout the products in Lalamove at beginning
* Rebuild Web App
  * From jQuery project to React project
* Opportunity to build our internal UI library

## What is a Design system?
* Collection of reusable components, guided by clear standards
* Can be **assembled together to build any applications**

## Why we need to build our own UI library?
* Improve customer experience
  * Provide consistency and familiarity to the users

* Allow cross-functional efficiency
  * Allow designers and engineers reuse elements already been created
  * More scalable, not thorugh hiring only

* Reduce learning time, Increase maintainability
  * Engineers may have their own prefernces
  * No right / wrong, but:
  * Learning curve is higher if multiple products use different library
  * When new team members join, they need to learn another library usage

* Update faster
  * Updates to the library components
  * Changes applied to all applications if they got new version

## How we build that?
Two parts from Design team and Enginering team
* Design (Sketch library / UI Kit)
* Code (React UI library / Documentation)

## Code (Tech stack)
* React
* Styled-components
* Babel 7
* Jest + Enzyme

## Code Demo
* Storybook
* Styleguidist

## Lessons Learned
* Build something small first
  * It is all about process
* Start with one company project
  * Long-term investment
  * Lack of resources to prioritize UI library for small startup
  * Not always align with business value
  * So it is hard to find one responsible product team
* How to slove dependency issue
  * Communication
  * Build in your application first, move it to library later

## Open source
* https://ui.lalamove.com
* https://ui.lalamove.com/storybook
* https://github.com/lalamove/karang

## Special Thanks (Alphabetical order)
* Alfonso Rodriguez
* Andrew Mok
* Dennis Tse
* Don Kim
* Ignatius Baptista
* Jake Choi
* Jay Pun
* Karan Grover
* Samuel Kwok
* Vincent Pun
