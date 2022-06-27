# CodyFrame CSS
Experimental, CSS-only version of the [CodyHouse framework](https://codyhouse.co/ds/docs/framework).

CSS files import order:

```css
/* reset */
@import 'reset.css';

/* globals */
@import 'globals/colors.css';
@import 'globals/spacing.css';
@import 'globals/shared-styles.css';
@import 'globals/typography.css';
@import 'globals/icons.css';
@import 'globals/buttons.css';
@import 'globals/forms.css';
@import 'globals/z-index.css';

/* import here the components 👈 */

/* utility classes */
@import 'util.css';
```