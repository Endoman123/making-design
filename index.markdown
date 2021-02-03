---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: makings
layout: default
---
# what have i learned from making?

## process making / testing process
It is important to continally make, and incorporate making throughout our processes of thinking, desiging, and creating.

Making is continually experimental, groundbreaking within the design process, allowing us to access solutions and alternate modes of thought.

Each making experience has something to teach us about our process, product, ideas, or [selves](/).
<br>
<br>
<br>
<br>
<br>
<br>
{% capture cell1 %}
# chain box
{% endcapture %}
{% capture cell2 %}
## mix material

Take two unsuspecting materials and mash them together.
The materials can be found in an old box in your room, outside, in an unclaimed lost and found bucket,
int the clearance section of the craft store, online.

How can you make them interact? what techniques are involved in this interaction?

Focus on your construction techniques involved in the making process. Focus on your expected final form versus reality.
focus on how you solve the new challenge you've given yourself.
{% endcapture %}
{% capture grid %}
    {% include gridcell.html content=cell1 width=2 height=2 %}
    {% include gridcell.html content=cell2 width=2 height=2 %}
    {% include gridcell.html type="image" content="https://m.media-amazon.com/images/I/716z67aFfTL._AC_UL1500_.jpg" width=2 height=2 %}
{% endcapture %}
{% include grid.html content=grid %}