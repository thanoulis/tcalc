----

**tCalc** is a simple calculator written in core [Tcl/Tk](https://www.tcl.tk).

----

### Features

* On Top
* History
* Editable entry
* Resizable Buttons
* Full Tcl math support
* Command Line support
* Customizable precision
* Runs in GNU/Linux, MS-Windows and Unix (MacOS not tested)

----

#### Constants & Functions

| Constants | Description  |
|-----------|--------------|
| `p()`     | PI           |
| `e()`     | Euler number |

| Function      | Description          |
|---------------|----------------------|
| `exp(x)`      | exponential          |
| `sqrt(x)`     | square root          |
| `pow(x,y)`    | x power y (`x**y`)   |
| `fmod(x,y)`   | remainder of `x/y`   |
| `hypot(x,y)`  | hypotenuse           |
| `abs(x)`      | absolute \|x\|       |
| `round(x)`    | convert to integer   |
| `ceil(x)`     | next smallest int    |
| `floor(x)`    | previous largest int |
| `max(x,y,..)` | greatest number      |
| `min(x,y,..)` | smallest number      |
| `log(x)`      | natural logarithm    |
| `log10(x)`    | base 10 logarithm    |
| `randr`       | random number (0,1)  |
| `srandr(x)`   | random with seed     |

| Trigonometric | Functions          | Type    |
|---------------|--------------------|---------|
| `sind(x)`     | sine               | degrees |
| `cosd(x)`     | cosine             | degrees |
| `tand(x)`     | tangent            | degrees |
| `asind(x)`    | arc sine           | degrees |
| `acosd(x)`    | arc cosine         | degrees |
| `atand(x)`    | arc tangent        | degrees |
| `sin(x)`      | sine               | radians |
| `cos(x)`      | cosine             | radians |
| `tan(x)`      | tangent            | radians |
| `asin(x)`     | arc sine           | radians |
| `acos(x)`     | arc cosine         | radians |
| `atan(x)`     | arc tangent        | radians |
| `sinh(x)`     | hyperbolic sine    | radians |
| `cosh(x)`     | hyperbolic cosine  | radians |
| `tanh(x)      | hyperbolic tangent | radians |

----

### Screenshot

![Screenshot](screenshot.png "Screenshot")

----

### Dependencies

**Tcl** version 8.6 or later.

**Tk** version 8.6 or later.

##### For Microsoft Windows users:

[ActiveTcl](https://www.activestate.com/activetcl) version 8.6 or later.

Executable can be found in the [Releases](https://github.com/thanoulis/tcalc/releases) section.

To run it, after download, right-click->Properties->Unblock.

----

### License

**tEdit** is licensed under the **MIT License**.

Read [LICENSE](LICENSE) for details.

----
