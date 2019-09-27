## What is VPML? 
VPML stand for ViewPoint Markup Language, which is a template language designed to declaratively lay out the interface of ViewPoint Web Template.   

## How it work? 
VPML files have the extension of .vpml and it mix of standard HTML code and VPML code, eventually transpile into HTML file. This make comfortable immediately to anyone who has spent time working with HTML or XML. 

## Getting Started 
You can simply create a plaintext file with vpml extension, example, demo.vpml.   

# VPML Syntax  

## Root Element – vp:Application 
A VPML file must have only one root element - vp:Application, in order to be both a well-formed XML file and a valid VPML file. The following example shows the root element of a typical VPML file. 
```html
<vp:Application xmlns:vp="http://www.goviewpoint.com/2018/vpml" countryCode="EN" formCode='demo2' formCat='6' formType='WT' langCode='ENG' description="VPML template"  >
...
</vp:Application>
```
