# Immediate2D Drawing Framework
A C++ drawing framework for Windows that makes simple graphics programming as fun and easy as the days when computers booted directly to a BASIC prompt.

Made for beginners and classrooms.  To use this framework just drop "drawing.cpp" and "drawing.h" into a new "Win32" Visual Studio project and declare a `void main()` function.  Immediate2D will take care of the rest.

There is **absolutely zero setup** or initialization.  (By default you get a 5x scaled-up 160x120 window and can draw to it in your very first line of code:
```C++
#include "drawing.h"

void main() {
  SetPixel(80, 20, LightBlue);
}
```

Includes a nice set of examples with exercises taking a student from drawing a single dot (shown above) all the way to simple games and physics simulations.

Everything you need is documented in [drawing.h](/drawing.h) and a [Quick Reference](/QuickReference.pdf) is supplied that fits everything on one page.


---

### Example 1 - Hellow World
A one-line example with exercises to familiarize the student with the "y goes down" computer graphics convention.

<img alt="Example 1" src="images/example1.png" height="240">

---

### Example 2 - Blink
Demonstrates simple animation in a `while` loop.

<img alt="Example 2" src="images/example2.png" height="240">

---

### Example 3 - Button
Shows a little bit of mouse interaction and uses the exercises to build up some rudimentary UI concepts.

<img alt="Example 3" src="images/example3.png" height="240">

---

### Example 4 - Paint
More mouse interaction through a simple paint example.

<img alt="Example 4" src="images/example4.png" height="240">

---

### Example 5 - Graphing
A graphing calculator in 8 lines of code.

<img alt="Example 5" src="images/example5.png" height="240">

---

### Example 6 - Text
Demonstrates how little you really need to do something like draw text to the screen (by packing each glyph into a single int).

<img alt="Example 6" src="images/example6.png" height="240">

---

### Example 7 - Nibbles
An adaptation of the classic NIBBLES.BAS snake game example that was included with QBASIC.

<img alt="Example 7" src="images/example7.png" height="240">

---

### Example 8 - Smoke
An implementation of Joe Stam's 2003 paper "[Real-Time Fluid Dynamics for Games](http://www.dgp.toronto.edu/~stam/reality/Research/pub.html)" that fits in about 250 lines of C++.

<img alt="Example 8" src="images/example8.png" height="240">

---

### Example 9 - Raytracer
An adaptation of Kevin Beason's [smallpt](http://www.kevinbeason.com/smallpt/) ray tracer.

<img alt="Example 9" src="images/example9.png" height="240">
