
#External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.
An external style sheet can be written in any text editor, and must be saved with a .css extension.

The external .css file should not contain any HTML tags.


# Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.

# Inline CSS
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

# Cascading Order
What style will be used when there is more than one style specified for an HTML element?

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

>- Inline style (inside an HTML element)
>- External and internal style sheets (in the head section)
>- Browser default
>- So, an inline style has the highest priority, and will override external and internal styles and browser defaults.

# CSS reference
Use this CSS reference to browse an alphabetical index of all of the standard CSS properties, pseudo-classes, pseudo-elements, data types, functional notations and at-rules. You can also browse key CSS concepts and a list of selectors organized by type. Also included is a brief DOM-CSS / CSSOM reference. 
For a beginner-level introduction to the syntax of selectors, see our guide on CSS Selectors. Be aware that any syntax error in a rule definition invalidates the entire rule. Invalid rules are ignored by the browser. Note that CSS rule definitions are entirely (ASCII) text-based, whereas DOM-CSS / CSSOM (the rule management system) is object-based

