# Client Side MVWTF

---

## Our Presenters

## David Luecke

* GitHub: [daffl.github.com](http://daffl.github.com), Twitter: [@daffl](http://twitter.com/daffl)

## Eric Kryski

* GitHub: [ekryski.github.com](http://ekryski.github.com), Twitter: [@ekryski](http://twitter.com/ekryski)

---

## Our Sponsors

## Assembly Co-working Space

![Assembly](images/sponsors/assembly_logo.png)

## PetroFeed

![PetroFeed](images/sponsors/pf-logo.png)

---

## Our Sponsors

## Village Brewery

![Village Brewery](images/sponsors/village_brewery_logo_inverted.png)

---

## Last Month

### Node Authentication and Structuring

* NodeJS authentication using Passport
* How to better restructure your Express app
* Basic validation/middleware
* A realtime blog in 7 lines with Olives

---

## Library vs. Framework

__Library__:

* A set of tools to reduce overhead and improve application consistency by providing reusable pieces of code.
* A library provides useful tools for a specific purpose (functions, helper libs) so you can build your app your way.

__Framework__:

* A **more opinionated** set of tools to reduce overhead and improve application consistency by providing reusable pieces of code.
* Inversion of control. Frameworks specify how you should write your app.

---

## MVC, MVVM, MVP, MOVE? WTF?

* Quite a few different patterns being used in client side JS.
* Most are based off of MVC in some fashion.
* They are all really based on the [Observer Pattern](http://en.wikipedia.org/wiki/Observer_pattern).


---

## Client side MVC

Separates the representation of information from the user's interaction with it
<img src="images/mvc.png" alt="MVC overview" style="float: right; margin: 2em;" />

* __Controller__: Updates both, view and model according to user interaction
* __Model__: The data/domain model
* __View__: Creates a representation of the model

---

## [TodoMVC](http://todomvc.com/)

The same Todo application implemented using MV\* concepts in most of the popular JavaScript MV\*
frameworks of today.
<img src="images/todomvc.png" alt="TodoMVC" style="float: right; margin: 3em;" />

* Backbone
* CanJS
* Ember
* AngularJS
* Spine
* KnockoutJS
* DOJO
* ...
---

## [CanJS](http://canjs.com)

Client side MVC framework for building rich web applications. Supports *jQuery*, *Zepto*, *Mootools*,
*Dojo*, *YUI*.

* Evolved from [JavaScriptMVC](http://javascriptmvc.com) (since 2007)
* Focus on performance and ease of use
* __Construct__, __Observe__, __Model__, __view__, __EJS__, __Control__, __route__


![CanJS logo](images/canjs.png)

---

## Backbone

<img src="images/backbone_logo.png" alt="Backbone" style="float: right; margin: 3em; width: 200px; height: 200px;" />

* Very un-opinionated framework
* MVC-ish but more MVWhateverthehellyouwant
* Great community and lots of plugins

# Pitfalls
* Lots of files. Views, models, templates for everything
* Can really hang yourself if your not careful
* Prone to memory leaks
* Always need to call render

---

## Component
<img src="images/component_logo.jpeg" alt="Component" style="float: right; margin: 3em; width: 400px; height: 200px;" />

* A collection of components and a build system
* You pick and choose what you want
* Components are self contained with minimal styling
* Lots of components already

    ```
    component install
    ```

* Uses `component.json` which leverages github

---

## Next Month

* Testing!!
* Buzzwords
* Frameworks
* Writing some tests
* CI Integration
