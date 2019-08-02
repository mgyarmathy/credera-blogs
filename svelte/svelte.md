# Svelte - Is This Next-Generation JavaScript Framework Production-Ready?

The selection of technologies available to build web applications is constantly evolving and ever-changing. If you follow the JavaScript community close enough, it seems as if every other month there is a shiny new framework that has caught people's attention. Most trends spark up and fizzle out quickly, but occasionally you'll come across something that has people asking, *"Is this the Next Big Thing?"*

Svelte happens to be one of those technologies.

## What is Svelte?

Svelte is a component-based JavaScript UI framework, similar to React or Vue. Component-based frameworks allow developers to build user interfaces by creating composible components that are re-usable across multiple contexts. Svelte is different that most frameworks, however, in that rather than using *runtime* techniques for DOM updates (e.g. virtual DOM), Svelte adds code at *compile time* to surgically update the DOM when the state of your application changes. Web applications built with Svelte tend to have smaller bundle sizes and significant performance gains due to the elimination of the overhead that comes with maintaining a virtual DOM.

![](quote.png)

In April 2019, Rich Harris, the author of Svelte, announced the major release of Svelte 3. During his talk, ["Rethinking Reactivity"](https://www.youtube.com/watch?v=AdNJ3fydeao) at YGLF Code Camp 2019, Rich explained the significance of this release: "Svelte 3 moves reactivity out of the component API and into the language". This dramatic overhaul of the framework included new features like Reactive Assignments, Reactive Stores, and Reactive Declarations, heavily inspired by Reactive Programming paradigms.

## Is Svelte Ready for Production?

<!-- ![](trial.png) -->

- Almost, but not yet
- Adopt, **Trial**, Assess, Hold
- Pros
  - simple component model
  - solid performance benchmarks
  - small bundle sizes
  - shallow learning curve
  - reactive declarations simplify the cascading changes to component state that are derived from other state values
- Cons
  - limited adoption for large-scale applications
  - immature developer tooling 
  - small selection of third-party component libraries (no svelte-bootstrap or svelte-material just yet)
  - doesn't play well with others (no official TypeScript support... yet [Svelte is written in TS though!])

## Recommended Use Cases

- small-to-medium SPAs
- interactives/visualizations requiring a large number of DOM elements
- web apps intended for low power devices
