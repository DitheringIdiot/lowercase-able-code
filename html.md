# Examples of lowercase-able HTML code

## Doctype [13.1.1](https://html.spec.whatwg.org/multipage/syntax.html#the-doctype)

Doctype is case insensitive.

```html
<!DOCTYPE html>
```

```html
<!doctype html>
```

## `lang` attribute [3.2.6.2](https://html.spec.whatwg.org/multipage/dom.html#the-lang-and-xml:lang-attributes)

The HTML Standard doesn't specifically state that lang attribute values are case-insensitive — though the examples it gives are lowercase. It does state that lang values must be "valid BCP 47 language tag". [BCP 47](https://www.rfc-editor.org/info/bcp47) (Best Current Practices 47) is an RFC defining the best practices for language tags. It states that the tags should be treated as [case-insensitive](https://www.rfc-editor.org/rfc/pdfrfc/rfc4647.txt.pdf).

```html
<html lang="EN"></html>
```

```html
<html lang="en"></html>
```

## `sizes` attribute [4.2.4](https://html.spec.whatwg.org/multipage/semantics.html#the-link-element)

The HTML Standard explicitly states that the `sizes` attribute values are case-insensitive.

```
sizes="50VW"
```

```
sizes="50vw"
```

## Character encoding [4.2.5.4](https://html.spec.whatwg.org/multipage/semantics.html#charset)

The HTML Standard states that the character encoding must be 'an ASCII case-insensitive match for "utf-8"'.

```html
<meta charset="UTF-8">
```

```html
<meta charset="utf-8">
```

### Additional optimization

`<meta charset="utf-8">` should appear as early in the document as possible — and must appear in the first `1024 bytes` of the document.
The sooner the browser sees it, the sooner it can stop trying to work out what the character encoding is, saving some computation.



