-- el: #nav
-- title: Navigation

Navigation for adaptive web experiences can be tricky. Top navigations are typical on desktop sites, but mobile screen sizes don't give us the luxury of space. We're dealing with this situation by creating a simple menu anchor that toggles the main navigation on small screens. This is just one method. [Bagcheck(http://bagcheck.com/)] and [Contents Magazine(http://contentsmagazine.com/)] add an anchor in the header that jumps users to the navigation which is placed in the footer. This solution works well because it doesn't require any Javascript in order to work. Other methods exist too. For example, [ESPN's mobile navigation(http://m.espn.com/)] overlays the main content of the page.

The nav is only hidden when a certain level of javascript is supported in order to ensure that users with little/poor javascript support can still access the navigation. Once the screen size is large enough to accommodate the nav, we show the main navigation links and hide the menu anchor.

See also: [Responsive Navigation Patterns(http://bradfrostweb.com/blog/web/responsive-nav-patterns/) has no title attribute.