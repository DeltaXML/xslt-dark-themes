<img src="deltaxigniaLogoSmall.png">

# XSLT Dark Themes

A set of popular dark color themes extended to enhance support for XSLT/XPath [Semantic Highlighting](https://code.visualstudio.com/api/language-extensions/semantic-highlight-guide).

These themes are for use with the [XSLT/Path for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=deltaxml.xslt-xpath) and [XPath Notebooks](https://marketplace.visualstudio.com/items?itemName=deltaxml.xpath-notebook) extensions maintained by [DeltaXignia](https://deltaxignia.com).

## Themes

The following themes are included. The 'X' prefix is used to distinguish the XSLT/XPath extended variant. Links are to the VS Code marketplace entries for the original themes.
- X [Darcula From IntelliJ](https://marketplace.visualstudio.com/items?itemName=trinm1709.dracula-theme-from-intellij)
- X [Gruvbox Material Dark](https://marketplace.visualstudio.com/items?itemName=sainnhe.gruvbox-material)
- X [Gruvbox Material Dark - Borders](https://marketplace.visualstudio.com/items?itemName=sainnhe.gruvbox-material)
- X [Iceberg](https://marketplace.visualstudio.com/items?itemName=cocopon.iceberg-theme)
- X [Moegi Dark Vitesse](https://marketplace.visualstudio.com/items?itemName=ddiu8081.moegi-theme)
- X [Nord Dark](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code)
- X [Nord Darker](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code)
- X [Tokyo Night Storm](https://marketplace.visualstudio.com/items?itemName=enkia.tokyo-night)
- X [Zenburn](https://marketplace.visualstudio.com/items?itemName=ryanolsonx.zenburn)
- X [Oxygen Graphite](https://www.oxygenxml.com/)

## Screenshots
---
### X Darcula from IntelliJ
<p><img src=https://raw.githubusercontent.com/DeltaXML/xslt-dark-themes/5748bd37f3c545e083763210b7635bcd05852e3d/images/darcula.png style="width:600px; padding-top:10px">

---
### X Gruvbox Material Dark
<p><img src=https://github.com/DeltaXML/xslt-dark-themes/raw/5748bd37f3c545e083763210b7635bcd05852e3d/images/gruvbox.png style="width:600px; padding-top:10px">

---
###  X Nord Dark
<p><img src=https://github.com/DeltaXML/xslt-dark-themes/raw/5748bd37f3c545e083763210b7635bcd05852e3d/images/nord.png style="width:600px; padding-top:10px">

###  X Nord Darker
<p><img src=https://github.com/DeltaXML/xslt-dark-themes/raw/5748bd37f3c545e083763210b7635bcd05852e3d/images/nord-darker.png style="width:600px; padding-top:10px">

---
### X Tokyo Night
<p><img src=https://github.com/DeltaXML/xslt-dark-themes/raw/5748bd37f3c545e083763210b7635bcd05852e3d/images/tokyo-night.png style="width:600px; padding-top:10px">

---
### X Iceberg
<p><img src=https://github.com/DeltaXML/xslt-dark-themes/raw/5748bd37f3c545e083763210b7635bcd05852e3d/images/iceberg.png style="width:600px; padding-top:10px">

---
### X Zenburn
<p><img src=https://github.com/DeltaXML/xslt-dark-themes/raw/5748bd37f3c545e083763210b7635bcd05852e3d/images/zenburn.png style="width:600px; padding-top:10px">

---
### X Oxygen Graphite
<p><img src=https://raw.githubusercontent.com/DeltaXML/xslt-dark-themes/master/images/oxygen.png style="width:600px; padding-top:10px">

---

##  Project Goal

The immediate goal of this extension is to add support for language-specific XSLT and XPath semantic tokens for a range of popular themes.

These theme enhancements are provided as a convenient alternative to managing custom user settings.

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

## Additional Notes

1. Alongside adding support for XSLT/XPath Semantic Tokens, for some themes there may have been slight adjustments. Specifically:

    - Ensure active indent-guide-line has sufficient contrast with non-active lines
    - For XPath Notebooks, ensure the code cell background color is different to the general background color

2. For some themes it was necessary to adjust colors for semantic tokens that are not specific to XSLT/XPath




