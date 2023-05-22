## About the project

* create realistic color markers using css.

## Tools used

* HTML
* CSS

## Learning 

* Linear gradient - The function is very flexible.
    * syntax : linear-gradient(gradientDirection, color1, color2, ...);
* gradientDirection is the direction of the line used for the transition. color1 and color2 are color arguments, which are the colors that will be used in the transition itself. These can be any type of color, including color keywords, hex, rgb, or hsl.
* RGB color - rgb(red, green, blue) 
    * Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.
* RGBA color - rgba(red, green, blue, alpha)
    * RGBA color values are an extension of RGB color values with an alpha channel.
    * The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all).
* HEX value - #rrggbb.
    * Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).
    * For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).
* HSL value - hsl(hue, saturation, lightness).
    * Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.
    * Saturation is a percentage value. 0% means a shade of gray, and 100% is the full color.
    * Lightness is also a percentage. 0% is black, 50% is neither light or dark, 100% is white.

* box shadow - property attaches one or more shadows to an element.
    * syntax : x-offset y-offset blur spread color;
* x-offset - The <length> value specifies the horizontal distance. Negative values place the shadow to the left of the element.
* y-offset - The <length> values specifies the vertical distance. Negative values place the shadow above the element.
* blur radius - This is a third <length> value. The larger this value, the bigger the blur, so the shadow becomes bigger and lighter. Negative values are not allowed. If not specified, it will be 0.
* spread redius - This is a fourth <length> value. Positive values will cause the shadow to expand and grow bigger, negative values will cause the shadow to shrink. If not specified, it will be 0.

## Production Link

https://color-markers.vercel.app/