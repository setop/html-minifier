# html-minifier
a minifier for html written in python

# Usage

from html_minifier.minify import Minifier
minifier = Minifier(html)
html = minifier.minify()

for a reuse is better 

from html_minifier.minify import Minifier
minifier = Minifier()
for i in range(100):
    minifier.html = html
    html = minifier.minify()
