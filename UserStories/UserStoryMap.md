User Story Maps
===============

What is it?
-----------

A User Story Map is a representation of a set of user stories along two axes:
- sequence
- priority

Purpose
-------

- Shows the flow of activities from the user's perspective
- Informs architecture/infrastructure needs
- Outlines stories' relationships to eachother

```
              .--------------------------------------------------------------------------------.
              |                            EPIC: Buy a plane ticket                            |
              `--------------------------------------------------------------------------------'
               
               earlier <--------------------------- SEQUENCE ---------------------------> later
              .---------------.  .---------------.  .----------.  .-------------.  .-----------.
              | THEME:        |  | THEME:        |  | THEME:   |  | THEME:      |  | THEME:    |
    +         | flight search |  | shopping cart |  | checkout |  | fulfillment |  | post-sale |
              `---------------'  `---------------'  `----------'  `-------------'  `-----------'
    ^  
    |         .---------------.  .---------------.  .----------.  .-------------.  .-----------.
    |         | STORY: search |  | STORY: pay by |  | STORY:   |  | STORY:      |  | STORY:    |
    |         | by city pair  |  | credit card   |  | insurance|  | e-ticket    |  | refunds   |
    |         `---------------'  `---------------'  `----------'  `-------------'  `-----------'
    |         .---------------.  .---------------.  .----------.  .-------------.  .-----------.
    |         | STORY: search |  | STORY: pay by |  | STORY:in-|  | STORY: paper|  |STORY:same-|
 PRIORITY     | by date       |  | online chq    |  |flt. ent. |  | ticket      |  |day exch.  |
    |         `---------------'  `---------------'  `----------'  `-------------'  `-----------'
    |         .---------------.  .---------------.                                 .-----------.
    |         | STORY: search |  | STORY: pay by |                                 |STORY:diff-|
    |         | by price      |  | P.O.          |                                 |day exch.  |
    |         `---------------'  `---------------'                                 `-----------'
    |         .---------------.                                                    .-----------.
    v         | STORY: complex|                                                    |STORY:diff-|
              | search        |                                                    |city exch. |
    -         `---------------'                                                    `-----------'
    ```
