# family-tree

A Data Structure-focused example on how to implement a family tree in Java. Good for university students ;) This is kept simple for a reason.

- There's a CSV file that can be parsed that only contains either information on a family member's gender, or its relationship with another family member, B. The relationship is included only if they are B's spouse, or parent, since _all other relationships can be inferred_
- There's a record file that gets populated with each person's name and gender
- The key thing; the ability to determine whether two persons are related given their name, and how
- There's the ability to create a [GraphViz](https://graphviz.org/) file with the family tree encoded in [DOT](https://graphviz.org/doc/info/lang.html) because, why not

If you've come this far, I _have_ to reward you with the amazing https://stackoverflow.com/questions/6163683/cycles-in-family-tree-software. Fun read!