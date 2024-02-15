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
* Runs in GNU/Linux, [Microsoft Windows](#for-microsoft-windows-users) and Unix (MacOS not tested)

----

#### Constants & Functions

| Constants | Description            |
|-----------|------------------------|
| `c()`     | speed of light         |
| `G()`     | gravitational constant |
| `g()`     | gravity acceleration   |
| `e()`     | <span>&#8455;</span>   |
| `pi()`    | <span>&pi;</span>      |
| `phi()`   | <span>&phi;</span>     |

| Generic          | Description              | Altenative    |
|------------------|--------------------------|---------------|
| `inv(x)`         | inverse x                | `1/x`         |
| `sqrt(x)`        | <span>&#8730;</span>x    |
| `pow(x,y)`       | x<sup>y</sup>            | `x**y`        |
| `fmod(x,y)`      | remainder of `x/y`       | `x%y`         |
| `hypot(a,b)`     | hypotenuse               |
| `quadf(a,b,c)`   | quadratic formula        |
| `abs(x)`         | \|x\|                    |
| `exp(x)`         | e<sup>x</sup>            |
| `factorial(x)`   | x!                       |               |
| `ln(x)`          | ln(x)                    |
| `log(x)`         | log<sub>10</sub>(x)      | `log10(x)`    |
| `logb(base,x)    | log<sub>base</sub>(x)    |
| `am(a,b,..)`     | arithmetic mean          | `avg(a,b,..)` |
| `gm(a,b,..)`     | geometric mean           |
| `hm(a,b,..)`     | harmonic mean            |
| `qm(a,b,..)`     | quadratic mean           | `rms(a,b,..)` |
| `round(x)`       | nearest integer          |
| `ceil(x)`        | next smallest integer    |
| `floor(x)`       | previous largest integer |
| `min(x,y,..)`    | smallest number          |
| `max(x,y,..)`    | greatest number          |
| `median(x,y,..)` | median number            |
| `fib(x)`         | fibonacci number         |

| Trigonometric | Description        | Type    |
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
| `tanh(x)`     | hyperbolic tangent | radians |

| Economy                              | Description            |
|--------------------------------------|------------------------|
| `interest(capital,interest,period)`  | calculate simple ROI   |
| `cinterest(capital,interest,period)` | calculate compound ROI |

| Date/Time      | Description                         |
|----------------|-------------------------------------|
| `days(x,y)`    | calculate days<br/>format: `%d%m%Y` |
| `hours(x,y)`   | calculate hours<br/>format: `%H%M`  |
| `dec2deg(x,y)` | decimals to degrees                 |

| Convert        | Description           |
|----------------|-----------------------|
| `c2f(x)`       | Celcius to Fahrenheit |
| `f2c(x)`       | Fahrenheit to Celcius |
| `c2k(x)`       | Celcius to Kelvin     |
| `k2c(x)`       | Kelvin to Celcius     |
| `inch2cm(x)`   | inches to centimeters |
| `cm2inch(x)`   | centimeters to inches |
| `yd2m(x)`      | yards to meters       |
| `m2yd(x)`      | meters to yards       |
| `ft2m(x)`      | feet to meters        |
| `m2ft(x)`      | meters to feet        |
| `mi2km(x)`     | miles to kilometers   |
| `km2mi(x)`     | kilometers to miles   |
| `btu2watt(x)`  | BTU to Watt           |
| `watt2btu(x)`  | Watt to BTU           |

----

### Screenshot

![Screenshot](screenshot.png "Screenshot")

----

### Dependencies

**Tcl** version 8.6 or later.

**Tk** version 8.6 or later.

##### For Microsoft Windows users:

[ActiveTcl](https://www.activestate.com/activetcl) version 8.6 or later.

For executables go to [Releases](https://github.com/thanoulis/tcalc/releases) section, or download the [latest](https://github.com/thanoulis/tcalc/releases/latest/download/tcalc.exe).

To run it, after download, right-click->Properties->Unblock.

----

### License

**tEdit** is licensed under the **MIT License**.

Read [LICENSE](LICENSE) for details.

----
