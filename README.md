[Missofis Front-End Templates](http://missofis.com)

# Particals Branch

Particals Branch is added to template to maintain other developers' websites. Use this Branch as an abstraction for newly added or maintained parts of website. It has a `particals.css`, `__particals.less`, `particals.js` files to add outer styles and scripts to maintained website.

Main purpose of Particals Branch is to provide an abstraction for maintained old f*ckin' websites, projects.

### The Logic

Particles maintaining behaviour follows a basic logic:

* add a semantic wrapper CSS class like `.prtcl-main-nav` to current particle (ie. new navigation of site)
* select inner elements of `.prtcl-main-nav` class with CSS selectors (like `.prtcl-main-nav ul li`)
* write new styles of element
* test & publish

Keep in mind to:

* Save old holder components' positioning info.
* Copy old holders' behaviour, which `<script>` parts are related to this container and it's childs.

### An Appropriate Naming Convention

* Using the naming convention `{{.|#}}`-`{{PARTICLE_IDENTIFIER_STRING}}`-`{{OLD_NAME_OR_ID}}` for #id's and .classes of newly maintained holders is a good practise to remember which part of site is mintained before. This convention remembers both old class and newly created maintaining class.















[url_missofis]: http://missofis.com  "we're missophisticated!"