# Markdown with syntax highlighting

If you write a lot of code in your Markdown files, you may wish to enable
syntax highlighting to make your code more readable. This script will convert
your markdown text as any other script, but it will parse your code with
[Pygments][pygments]. 

### Usage

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


[pygments]: http://pygments.org/
[markdown2]: http://code.google.com/p/python-markdown2/
