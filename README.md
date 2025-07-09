# Avone - Multipurpose Shopify Theme by adornthemes

![Avone - Multipurpose Shopify Theme](https://github.com/user-attachments/assets/ae2ab4e6-4ce8-460d-999a-b8353b0a6fe5)

**Avone - Multipurpose Shopify Theme**  
- **Total Downloads:** 10,700+
- **Ratings:** 5 on 5
- **Estimated Earnings:** $958,085+ (based on avg $89/theme)  
- **Top Features:** Modern multipurpose design, built-in mega menu, fast loading, product quick view, mobile optimization, and RTL support.
- **Store Link:** https://themeforest.net/item/avone-multipurpose-shopify-theme/24276567

## What went wrong?
**[Avone](https://themeforest.net/item/avone-multipurpose-shopify-theme/24276567)** has gone for good criteria to protect their theme from being nulled. But dingoooooo. Here's a way for you to use this $89 premium theme for free for a **Shopify Store**.

This activation screen dynamically loaded by the theme and contains the obfuscated license activation logic from https://www.adornthemes.com/api/mustneed.js

And this code which is in `theme.js` is liable for the dynamic purchase activation screen.

<pre>
if (Shopify.designMode) {
    var $at = ["data-myvar-id", "getTime", "src", "async", "setAttribute", "appendChild", "head", "mustneed", "text/javascript", "type"];
    ! function(t, e) {
        ! function(e) {
            for (; --e;) t.push(t.shift())
        }(++e)
    }($at, 214);
    var x = function(t, e) {
        return $at[t -= 0]
    };
    ! function() {
        var t, e;
        (t = document.createElement("script"))[x("0x5")] = x("0x4"), t[x("0x9")] = !0, t.id = x("0x3"), t[x("0x0")](x("0x6"), (new Date)[x("0x7")]()), e = ["d", "e", "m", "t", "a", "/", "r", "u", ".", "s", "t", "?", "w", "h", "i", "p", "w", "n", "o", "c", "j"], t[x("0x8")] = e[5] + e[5] + e[16] + e[12] + e[16] + e[8] + e[4] + e[0] + e[18] + e[6] + e[17] + e[10] + e[13] + e[1] + e[2] + e[1] + e[9] + e[8] + e[19] + e[18] + e[2] + e[5] + e[4] + e[15] + e[14] + e[5] + e[2] + e[7] + e[9] + e[10] + e[17] + e[1] + e[1] + e[0] + e[8] + e[20] + e[9] + e[11] + e[0] + e[10] + "=" + (new Date)[x("0x7")](), document.getElementsByTagName(x("0x2"))[0][x("0x1")](t)
    }()
}
</pre>
- To use this theme for free, you can download this repository.
- If you have got file already and stuck in the purchase activation screen, follow steps below:
  - Take any code editor and open `theme.js`.
  - search for `Shopify.designMode` or any attribute from `$at`.
  - look for the similar code i provided above. and remove everything in <pre>
    if (Shopify.designMode) {
      // remove everything here
    }
  </pre>
  
  - save it. And you are good to go with the customization.

> [!NOTE]
> I will keep updating this repo according to their security implements. Feels free to create issue if you figure out any.
  