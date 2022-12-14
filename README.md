# web-components

# Main building blocks are:
1.Custom Elements
2.Shadow Dom
3.Html Template

# Create custom Elements
syntax:
class AppDrawer extends HTMLElement {...}
window.customElements.define("app-drawer",AppDrawer); //  hipon is important

Life cycle:
* constructor - called when an element is created or upgraded.
* connectedCallBack()  -  Called everytime when the element is inserted into the DOM.
* disconnectedCallBack() - called everytime the element is removed from the DOM.
* attributeChangedCallBack(attributeName,oldValue,newValue) - called when an attribute is added,removed,updated or replaced. 

# Shadow DOM
* Used for self contained components
* Encapsulate styles and markup
* Create with element.attachShadow({mode: open})
* Creates a shadowRoot that we can reference and interact with.

# HTML Templates
* Define the encapsulated markup of our web component.
* Template tag store markup on page.
* Include both HTML and CSS in template
* Use slots to add custom text. 



