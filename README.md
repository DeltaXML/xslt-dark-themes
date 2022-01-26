# XSLT Dark Themes

Popular dark themes with [Semantic Highlighting](https://code.visualstudio.com/api/language-extensions/semantic-highlight-guide) support extended specifically for the XSLT and XPath languages.

These themes can enhance the [XSLT/Path for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=deltaxml.xslt-xpath) and [XPath Notebooks](https://marketplace.visualstudio.com/items?itemName=deltaxml.xpath-notebook) extensions maintained by DeltaXML.

## Themes
- X Darcula From IntelliJ
- X Gruvbox Material Dark
- X Iceberg
- X Nord
- X Tokyo Night Storm

## Examples
---
### X Darcula from IntelliJ
<p><img src=images/darcula.png style="width:600px; padding-top:10px">

---
### X Gruvbox Material Dark
<p><img src=images/gruvbox.png style="width:600px; padding-top:10px">

---
###  X Nord
<p><img src=images/nord.png style="width:600px; padding-top:10px">

---
### X Tokyo Night
<p><img src=images/tokyo-night.png style="width:600px; padding-top:10px">

---
### X Iceberg
<p><img src=images/iceberg.png style="width:600px; padding-top:10px">

---

##  Project Goal

Visual Studio Code color themes provide support for a range of languages, there is however no support for token types that are only found in XSLT and XPath. The goal of this extension is to add support for language-specific XSLT and XPath tokens for a range of popular themes.

## User Customisation

You can override specific XSLT token colors in user settings, as in the following example:

```JSON
  "editor.semanticTokenColorCustomizations": {
    "[Kimbie Dark]": {
      "enabled": true,
      "rules": {
        "simpleType": "#98676a",
        "anonymousFunction": "#889b4a",
				"axisName": "#98676a",
      }
    }
  }
```

Property names like `simpleType` correspond to the XSLT/XPath-specific Semantic Tokens names. Here's a full list:

### XSLT Semantic Tokens

    attributeName,
    attributeEquals,
    attributeValue,
    xmlnsName,
    dtd,
    elementName,
    elementValue,
    processingInstrName,
    processingInstrValue,
    entityRef,
    xmlComment,
    xmlPunctuation,
    xslElementName,
    xmlText

### XPath Semantic Tokens

    attributeNameTest,   
    comment*,
    number*,
    operator*,
    variable*,   
    string*,
    uriLiteral,
    nodeType,  
    simpleType,
    axisName, 
    nodeNameTest,
    functionNameTest,
    complexExpression,
    function*,
    entityRef,
    anonymousFunction,
    mapKey

\* *'Standard' semantic tokens - used by other languages*




