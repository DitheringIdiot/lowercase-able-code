# Examples of lowercase-able HTML code

## Doctype [13.1.1](https://html.spec.whatwg.org/multipage/syntax.html#the-doctype)

Doctype is case insensitive.

```html
<!DOCTYPE html>
```

```html
<!doctype html>
```

### Additional optimization

The HTML Standard requires **zero** or more ascii whitespace between between `doctype` and `html` meaning the space can be ommitted.

```html
<!doctypehtml>
```

## lang values [3.2.6.2](https://html.spec.whatwg.org/multipage/dom.html#the-lang-and-xml:lang-attributes)

While the HTML Standard doesn't specifically state that lang attribute values are case-insensitive, the examples it gives are lowercase. It also states that lang values must "valid BCP 47 language tag". [BCP 47](https://www.rfc-editor.org/info/bcp47) (Best Current Practices 47) is an RFC defining the best practices for language tags. It states that the tags should be treated as [case-insensitive](https://www.rfc-editor.org/rfc/pdfrfc/rfc4647.txt.pdf).

