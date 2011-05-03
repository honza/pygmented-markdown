# Markdown with syntax highlighting

If you write a lot of code in your Markdown files, you may wish to enable
syntax highlighting to make your code more readable. This script will convert
your markdown text as any other script, but it will parse your code with
[Pygments][pygments]. 

### Usage

In your markdown document, you need to add a string to the top of your code
that says what language your code is in:

    python
    from datetime import datetime

Easy! And then, you convert it to HTML:

    markdown.py yourfile

This will print the result to standard output. You can, of course, use this in
your Python scripts.

    from markdown import markdown
    html = markdown("*hello*")

### Dependencies

This script requires ony Pygments to be installed. 

    pip install pygments

### Credit

I need to give credit where credit is due. This script is a modified version of
Trent Mick's amazing [markdown2][markdown2] script.

### License

Licensed under the terms of the 2-clause BSD license.

[pygments]: http://pygments.org/
[markdown2]: http://code.google.com/p/python-markdown2/
