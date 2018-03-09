# Glossary

**WP Loop Template**

These are templates that are core to WordPress Loop. \(e.g. page.php, single.php, archive.php, 404.php, etc\) Wordpress looks for these specific files in the loop to deliver the appropriate content.

**Views**

Views are templates that will be extended to the Wordpress Loop templates. Templates will be constructed by the use of components.

**Components**

Components are the building blocks of a View / Template. The use of components helps isolate blocks of code that help understand and maintain site being worked on by various team members.

**Partials**

Partials are smaller building blocks that can help build components. The main purpose of using partials and not repeating the same code on multiple Components. If you have an item or functionality on more that one Component, it should be a partial that is extended to the Component.

**CPT \(Custom Post Type\)**

Custom post types are new post types you can create. A custom post type can be added to WordPress via the register\_post\_type\(\) function. This function allows you to define a new post type by its labels, supported features, availability and other specifics. [Codex](https://codex.wordpress.org/Post_Types#Custom_Post_Types)

