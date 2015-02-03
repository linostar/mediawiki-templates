# mediawiki-templates

## How to use

New: Widgets are now used (inside a template) instead of writing the code inside the template directly. That way, <html> tags can be disabled in the wiki (which is strongly recommended security-wise) and the html/javascript functionality of the widget will not be affected.

Create a new page called **Template:_templatename_** in your wiki, and paste the contents of corresponding template file inside it.

Create another page called **Widget:_widgetname_**, and paste the contents of the corresponding widget file inside it.

For more information, see http://en.wikipedia.org/wiki/Help:Template

## Templates

### CodeSelect

**Syntax:** {{CodeSelect|code=*actual_code_goes_here*}}

You can put single-line or multi-line code in place of *actual_code_goes_here*.
