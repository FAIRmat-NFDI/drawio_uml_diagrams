# draw.io UML diagrams for NOMAD sections in the schema
Repository containing the [draw.io](https://www.drawio.com/) generated UML diagrams for the NOMAD sections in the different schema. 

We will use simplified [UML diagrams](https://en.wikipedia.org/wiki/Unified_Modeling_Language) with the following rules:
* Use TitilliumWeb font: 14pt and bold for titles, 12pt for quantities (also known as Python class attributes) and functions definitions. 
* Use `+` for public quantities and functions, `-` for private ones. Note that private functions in Python are also defined with underscore before the name (e.g., `_set_value()`), so in those cases you can skip using the underscore in the UML diagram and simply use the `-` symbol.
* Add `type`, `shape` and `unit` in your quantities.
* If the quantity is a NOMAD `SubSection`, then specify the class name in bold.
* For functions, there is no need to specificy the input parameters and output type.
* For connections, specify if the sub-sections have the specific extra NOMAD attributes: `repeats`, `proxy`, etc.
* Color code for the class title: general base classes do not have any color, specific-field section definitions follow the [FAIRmat](https://www.fairmat-nfdi.eu/fairmat/) color code for Synthesis (![#FFCC07](https://placehold.co/15x15/FFCC07/FFCC07.png) #FFCC07), Characterization (![#669933](https://placehold.co/15x15/669933/669933.png) #669933), Computations (![#009999](https://placehold.co/15x15/009999/009999.png) #009999), or specific Use-Cases (![#663399](https://placehold.co/15x15/663399/663399.png) #663399).
