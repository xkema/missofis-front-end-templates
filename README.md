[Missofis Front-End Templates](http://missofis.com)

# Particals Branch

Particals Branch is added to template to maintain other developers' websites. Use this Branch as an abstraction for newly added or maintained parts of website. It has a `particals.css`, `__particals.less`, `particals.js` files to add outer styles and scripts to maintained website.

Main purpose of Particals Branch is to provide an abstraction for maintained old f*ckin' websites, projects.

> Particles sınıflarını `<html>` içine nasıl import edeceğini de yaz dokümanlara. 

### The Logic

When maintaining a website that you do not design it's structure follow this flow with particles logic:

1. Find the part of HTML markup that your customer wants to be revised 
2. From the deepest element start to step up HTML tags until you find a correct markuped and styled block.

    > If we're responsible for changing a background image of a navigation link this correct block is probably an `<a>` element and we do not have to step up outer blocks
    
    > If we're dealing with a corrupted navigation itself, probably our target block is whole navigation holder block. (like _`#corrupted-nav-block-to-be-replaced-with-particles`_)
3. Replace _.class_ and _#id_'s with particles prefix you choose
4. Re-style and test new block

Particles maintaining behaviour follows these steps:

* add a semantic wrapper CSS class like `.prtcl-main-nav` to current particle (ie. new navigation of site)
    * `main-nav` is old _.class_ or _#id_ name. Use a `prtcl`-like prefix as a namespace.
* select inner elements of `.prtcl-main-nav` class with CSS selectors (like `.prtcl-main-nav ul li`)
* write new styles of element
* test & publish

Keep in mind to:

* Save old holder components' positioning info.
* Copy old holders' behaviour, which `<script>` parts are related to this container and it's childs.

### An Appropriate Naming Convention

* Using the naming convention `{{.|#}}`-`{{PARTICLE_IDENTIFIER_STRING}}`-`{{OLD_NAME_OR_ID}}` for #id's and .classes of newly maintained holders is a good practise to remember which part of site is mintained before. This convention remembers both old class and newly created maintaining class.















[url_missofis]: http://missofis.com  "we're missophisticated!"