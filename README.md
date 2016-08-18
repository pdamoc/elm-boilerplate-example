# Boilerplate example for the case where you have many small components that are unavoidably stateful

An exploration of the difference between an `elm-mdl` UI with `elm-parts` and one without. 


Clone this repository and then install the dependencies with `elm-package install -y`

Build the parts file `elm-make WithParts.elm --output parts.js`

Build the no-parts file `elm-make WithoutParts.elm --output noparts.js`

The functionality is identical and you can see them in action by opening `withParts.html` and `withoutParts.html`