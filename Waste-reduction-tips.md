# Waste Reduction Tips

These tips are based on a paper found in [this book](https://doi.org/10.1007/978-3-030-75235-4). Source: (Sandhu et al., 2022)

An important concept is that of **Design for 3D Printing/Additive Manufacturing** (Df3DP/DfAM).
It means that the designer of a part should optimize their print for the additive manufacturing process to reduce waste.

One can create 3 levels in which the designer can optimize their parts:
- [System Level](#system-level)
- [Process Level](#process-level)
- [Part level](#part-level)

## System Level
### Topology optimization
This means that the designed part has to be as functional as possible while being as minimal as possible. So no fancy unneeded features.

Also, reduce the amount of overhangs by using more slanted faces. Keep in mind that less overhangs means less supports needed.

Another trick is to model your own break-away supports.

Here is an interesting video about optimizing your designs.  

[![Beyond Trinkets: Why the 3D Printer is Now a Production Tool](http://img.youtube.com/vi/80-YoGyvQyQ/0.jpg)](http://www.youtube.com/watch?v=80-YoGyvQyQ)  
(Here is the link if the video does not redirect you: https://www.youtube.com/watch?v=80-YoGyvQyQ)

## Process Level
### Generative Design
By defining the potentials and constraints of your part, you can let your CAD tool generate the part for you with less volume and the same strength.
Here is an example of a [generative design tool in Fusion 360](https://www.autodesk.com/solutions/generative-design/manufacturing).

## Part Level

### Lattice structure filling
Don't use 100% infill, but rather use a lattice structure. Here is an interesting site of Prusa in which they explain the different [types of infill patterns](https://help.prusa3d.com/article/infill-patterns_177130).

### Internal geometries
Since you use Additive Manufacturing, you can add more complex features in your part that were previously not possible as a single part with other manufacturing methods. You could, for example, add integrated fluid channels into your part.

### Printed permeability
Some parts do not need a clean solid wall. You could save material by making them more porous.

### Functional material complexity
You could use multi material prints (MMU) to combine material properties (like soluble support structures or a flexible bit in your part). But you have to still keep in mind that MMU prints also create a lot of waste because it needs to transition in between the materials. So if your part's lifetime and functionality extends by using MMU, it could be a good choice.

### Assembly and part integration
Sometimes you can reduce the number of parts by combining them. This could reduce the amount of supports needed. A downside is that you reduce reparability and if your print fails, the whole part is lost.
