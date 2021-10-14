# Web Component Community Priorities

Web Components Community Group

Status: DRAFT

## Introduction

The initial slate of APIs that browsers shipped with web components "v1" left many important features and use-cases on a future to-do list, to be finalized out after the core custom element and shadow DOM features landed. While the web components GitHub issues and face-to-face meets have tracked and discussed many of these features individually, there hasn't been a comprehensive overview of what's left to "finish" web components.

This document tries to highlight the main features that are lacking from the web components spec that either block adoption for more developers and frameworks, or cause pain points for existing developers.

It's worth noting that many of these pain points are directly related to shadow DOM's encapsulation. While there are many benefits to some types of widely shared components to strong encapsulation, the friction of strong encapsulation has prevented most developers from adopting shadow DOM, to the point of there being alternate proposals for style scoping that don't use shadow DOM. We urge browser vendors to recognize these barriers and work to make shadow DOM more usable by more developers.

## Priorities

### Critical

- Forms
- Cross-root ARIA
- Constructible style sheets
- CSS module scripts
- Scoped element registries
- Declarative Shadow DOM

### High

- Selection
- Declarative CSS modules
- Children changed callback
- Opens styling of shadow roots
- Declarative custom elements
- Theming (::theme)
- Custom CSS state

### Medium

- Styling children of slotted content
- Imperative slotting
- CSS Properties and values inside shadow roots
- DOM Parts (formerly Template Instantiation)
- Lazy custom element definitions
- HTML includes
- HTML modules

