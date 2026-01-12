https://w3c.github.io/mathml
https://www.w3.org/TR/2025/WD-mathml4-20251218

# Relation to MathML Core
https://www.w3.org/TR/2025/WD-mathml4-20251218/#intro_core

##
The specification of MathML is developed in two layers. 
##
MathML Core covers (most of) Presentation Markup, with the focus being the precise details of displaying mathematics in web browsers. 
##
MathML Full, this specification, extends MathML Core primarily by defining Content MathML, in 4. Content Markup. 
##
It also defines extensions to Presentation MathML consisting of additional attributes, elements or enhanced syntax of attributes. 
##
These are defined for compatibility with legacy MathML, as well as to cover 3.1.7 Linebreaking of Expressions, 3.6 Elementary Math and other aspects not included in level 1 of MathML Core but which may be incorporated into future versions of MathML Core.

# MathML and Namespaces
```html
<math xmlns="http://www.w3.org/1998/Math/MathML">
	<mrow>...</mrow>
</math>
```