# Plotly Dash

Experimental setup of [Plotly Dash](https://dash.plot.ly/)

Example scripts from: https://dash.plot.ly/getting-started

### Instructions from Dash microsite

There are a few important differences between the dash_html_components and the HTML attributes:

* The style property in HTML is a semicolon-separated string. In Dash, you can just supply a dictionary.
* The keys in the style dictionary are camelCased. So, instead of text-align, it's textAlign.
* The HTML class attribute is className in Dash.
* The children of the HTML tag is specified through the children keyword argument. By convention, this is always the first argument and so it is often omitted.

Besides that, all of the available HTML attributes and tags are available to you within your Python context.

### Dash Documentation

https://dash.plot.ly/
