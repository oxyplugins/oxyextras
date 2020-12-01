=== OxyExtras ===
Contributors: David Browne, Gagan Goraya, Sridhar Katakam
Tags: oxygen builder
Requires at least: 4.7
Tested up to: 10.0.0
Requires PHP: 5.6
Stable tag: trunk
License: GPL3
License URI: http://www.gnu.org/licenses/gpl-3.0.txt

Lightweight component library for Oxygen Builder

== Description ==

Current Components:

1. Adjacent Posts
2. Alert Box
3. Author Box
4. Back to Top
5. Burger Trigger
6. Carousel Builder
7. Cart Counter
8. Circular Progress
9. Content Switcher
10. Copyright Year
11. Counter
12. Extras Login Form
13. Fluent Form
14. Gutenberg Reusable Block
15. Header Search
16. Infinite Scroller
17. Lottie Animation
18. Mini Cart
19. Off Canvas
20. Post Modified Date
21. Post Terms
22. Preloader
23. Pro Accordion
24. Pro Media Player
25. Mega Menu / Dropdown
26. Read More / Less
27. Reading Progress Bar
28. Reading Time
29. Slide Menu
30. Social Share
31. Toggle Switch

== Installation ==

1. Click on the download link in your purchase confirmation email if you have not already downloaded it after your purchase.

2. Download the plugin's zip file.

3. Go to Plugins > Add New in your WordPress admin. Click "Add New" button, then "Upload Plugin" button, then "Choose File", browse to and select the plugin's zip file.

4. Activate the plugin.

5. Enter the license key and activate your plugin license at Oxygen > OxyExtras > License.

Valid license key should be entered for the plugin to function and to receive automatic updates.

== Changelog ==

= 1.2.5 ( December 01, 2020 ) =
* [Mega Menu] -  New component for adding mega menu style dropdowns in header builder.
* [General] - Slight JS adjustments to ensure full support for jQuery 3.5.1.
* [Fluent Form] - Added separate style controls for GDPR.
* [Social Share] - Customisable share URL's and more control over the text in email title and body.
* [Slide Menu] - New "mega menu list" option for displaying columned menu lists inside Mega Menus.
* [Pro Media Player] - Removed aspect ratio setting for Vimeo (now automatic).
* [Carousel Builder] - Added option for auto cell grouping and percentage cell grouping.
* [Carousel Builder] - Carousel now horizontally scrollable inside builder while in edit mode.
* [Off Canvas] - Built-in support for linking offcanvas' to ensure both offcanvas' close together.
* [Off Canvas] - Auto-close when hashlink clicked is now optional.
* [Pro Media Player] - Fixed PHP warning "Undefined variable: vime_player_selector".

= 1.2.4 ( November 11, 2020 ) =
* [Carousel Builder] - Hotfix for making parallax work again.

= 1.2.3 ( November 11, 2020 ) =
* [Carousel Builder] - No longer need to specify cell selector when using Repeaters.
* [Carousel Builder] - Added option to disable pause Auto Play On Hover.
* [Carousel Builder] - Performance improvements inside the builder. Preview mode works faster.
* [Carousel Builder] - Added "Prioritize property" option for Galleries for choosing either dynamic height or widths.
* [Pro Accordion] - Added support for ACF option pages and using fields from specific page IDs.
* [Pro Media Player] - Added loop option for videos.
* [Pro Media Player] - Fixed dynamic data button not working correctly for Audio URL field.
* [Carousel Builder] - Fixed incorrect description text, "image URL" replaced with "image ID" for ACF galleries.
* [Slide Menu] - Fixed issue with schema markup sometimes preventing the menu text being clickable.
* [Read More] - Fixed gradient sometimes remaining visible when fade gradient disabled.

= 1.2.2 ( November 04, 2020 ) =
* [Carousel] - Added fade transition carousel type.
* [Carousel] - Added support for WP media library galleries.
* [Carousel] - Added option to remove pause-on-hover when using ticker mode.
* [Slide Menu] - Added current menu item styles and the ability to have the current menu item visible on page load.
* [Header Search] - Added expand form, slide reveal and accessibility controls options.
* [Read More] - Allow expanding inside builder for easier access to elements inside.
* [Read More] - Now dynamic. If content isn't taller than the expanded height, read more button (and gradient) will automatically not be visible.
* [Read More] - Can now be used inside Repeaters without issue.
* [Read More] - Added icons for the read more link, a fade transition and more control over the gradient overlay.
* [Infinite Scroller] - Now dynamic. If not enough posts found for there to be a second page, infinite scroll won't run (and read more button automatically hidden),
* [Alert Box] - Added click trigger and show/hide alert functions for programmatically triggering alerts.
* [Alert Box] - Added "header notice" alert type.
* [Adjacent Post] - Added alt tags to post images.
* [Accordion Pro] - Added option to turn off automatic sibling accordion item closing.
* [Pro Accordion] Fixed issue with accordion buttons being triggered too quickly when scrolling on iOS.
* [Slide Menu] - Fixed issue with hash links not triggering the sub menu.
* [Carousel] - Fixed issue with force equal heights being overridden by other CSS.
* [Carousel] - Fixed issue with high z-index on dots causing them to be visible over the top of modals.

= 1.2.1 ( October 26, 2020 ) =
* [General optimization] - Less default CSS output for multiple components where possible.
* [General optimization] - Improved reliability/usability of some components inside the builder.
* [General optimization] - Added browser-performance setting to carousel / Off Canvas for smoother transforms.
* [Carousel Builder]  - Added support for lazy loading images in cells when using Repeaters or Easy Posts.
* [Pro Accordion] - Dynamic mode will now show demo content inside builder if no ACF data found for each field (only in the builder for easier styling).
* [Pro Accordion] - Can now preview toggle animation and active style changes inside the builder by clicking the accordion header.
* [Burger Trigger] - Burger animation will now always be previewable inside the builder.

= 1.2.0 ( October 21, 2020 ) =
* [Pro Accordion] - New component for adding dynamic accordions.
* [Circular Progress] - Drop Shadows & Inner circle control added for more fancy styling.
* [Pro Media Player] - Added custom poster image option when using YouTube & Vimeo.
* [Pro Media Player] - Added new UI layout with custom play / pause icons.
* [Pro Media Player] - Added autoplay, autopause & more Vimeo options.
* [Carousel Builder] - ACF gallery image now automatically the same height.
* [Carousel Builder] - Add option to force equal height for cells.
* [Carousel Builder] - Fixed issue when heights overriding fullscreen mode.
* [Preloader] - Fixed pre-loader being visible if used on pages editable in Gutenberg.
* [Author Box] - Fixed issue with website link not displaying.
* [Offcanvas] - Fixed issue with inner-animations sometimes not resetting.

= 1.1.9 ( October 07, 2020 ) =
* [Circular Progress] - New component for adding animated circular progress bars.
* [Pro Media Player] - New component for adding lazy loading videos & audio with customizable UI.
* [Carousel Builder] - Added support for ACF gallery.
* [Carousel Builder] - Added 'fullscreen' option.
* [Carousel Builder] - Added styles for disabled navigation (when no more cells to navigate to).
* [Counter] - Counter will now show end number instead of start number inside the Oxygen builder.
* [Post Terms] - CPT taxonomies now included in taxonomy dropdown.
* [Fluent Form] - Fixed issue with characters no being visible inside form dropdown.
* [Slide Menu] - Fixed issue with arrow triggering menu link when viewing on Chrome mobile view.
* [Adjacent Posts] - Fixed issue with 'stack posts' setting causing some CSS from components to not be included.
* [Read More / Less] - Added gradient fade option.

= 1.1.8 ( September 15, 2020 ) =
* [Infinite Scroller] - New component for applying infinite scrolling to Easy Posts/ or Repeaters or Products Lists.
* [Carousel Builder] - Added carousel "ticker" option for allowing continuous movement.
* [OffCanvas] - Fixed an issue with hash links not scrolling after closing offcanvas.
* [OffCanvas] - Fixed staggered animations not resetting when revealing offcanvas from the top.
* [General] - Support for dynamic data added to multiple components.
* [General] - Selector fields now support attribute selectors, eg .class[attr=value]
* [General] - Components list on the plugin settings page now in alphabetical order.

= 1.1.7 ( September 02, 2020 ) =
* [Carousel Builder] - Added support for Easy Posts, Woo Components or using custom elements as cells.
* [Carousel Builder] - Added the ability to turn off carousel functionality at any breakpoint.
* [Carousel Builder] - Added Scale & transition controls for page dots.
* [Carousel Builder] - Added support for parallax elements (using the Repeater).
* [Lottie] - JSON now lazy loaded (can be disabled).
* [Off Canvas] - Added 'staggered animation' option for inner elements using Oxygen's scroll animation.
* [Preloader] - Fixed a rare issue where some elements would appear before preloader.
* [Burger Trigger] - Fixed an issue with some unpredictable behavior when used with slide menu.
* [Fluent Form] - Fixed hover opacity for submit button.
* [General] - Fixed an issue with the text fields not allowing quotes.

= 1.1.6 ( August 17, 2020 ) =
* [Carousel Builder] - New component for visually building carousels (for use with repeater component).
* [Offcanvas] - Any elements inside the offcanvas can now make use of Oxygen's scroll animations, triggered when the offcanvas is opened (rather than on page load).
* [Slide Menu] - Added new menu alignment controls and focus controls for the sub menu buttons.
* [Lottie] - Added option to render animation as <canvas> instead of <svg> (to prevent rare cases of some animations flickering in Safari).

= 1.1.5 ( August 06, 2020 ) =
* [Fluent Form] - Fixed padding issue on phone/mobile field when flag is disabled.
* [Cart Counter] - Fixed issue with cart number not updating (present only in v1.1.4).

= 1.1.4 ( August 05, 2020 ) =
* [Toggle Switch] New component for switching content or toggling classes.
* [Content Switcher] New component allowing to switch between two elements (for use with the toggle switch).
* [Burger Trigger] - Added 'scale' changing size of burger independent of size of the button.
* [Cart counter] - Accessibility improvement -  Dropdown cart now can be accessed by keyboard.
* [Counter] - Number fields now accept dynamic data.
* [Off Canvas] - Accessibility improvement - Now able to change the focus when offcanvas opened to any selector inside.
* [Off Canvas] - Trigger can now be from inside dynamically added content.
* [Slide Menu] - Added site navigation schema markup option.
* [Fluent Form] - Colour controls added for Invalid input state.
* [Fluent Form] - Label Typography font weight issue fixed.
* [Fluent Form] - Smart UI checkbox issue fixed on iPhone.
* [Fluent Form] - Fixed issue with form dropdown not appearing in Oxygen if a form name contained disallowed words.
* [Fluent Form] - Added Form ID control which accepts dynamic data.
* [Social Share] - Added Support for Pinterest, WhatsApp & Telegram.
* [Social Share] - Fixed issue with email share link when post titles contained certain characters.
* [Header Search] - Fixed a W3C Validator issue.
* [Lottie] - ACF field can now be used to get the JSON URL.
* [Lottie] - Cursor position control can now be relative to any container element.
* [Lottie] - Added MouseOver control (similar to hover but with frame control & reverse animation when use stops hovering.
* [General] Small performance improvements for users on Oxygen v3.4+ (less inline JS output where possible).
* [General] In-builder performance improvements (loading less JS).
* [General] Added support ready for Oxygen v3.5 (new preset code).

= 1.1.3 ( June 25, 2020 ) =
* Added checkboxes in the plugin's settings page so that only selected components can be added to the Oxygen editor.

= 1.1.2 ( June 24, 2020 ) =
* [Alert Box] - Can now be used as a header notification bar, with 'SlideUp' close option added.
* [Fluent Form] - Compatibility with v3.6.0.
* [Header Search] - More control over icon positioning.
* [Mini Cart] - Fixed scrollbar issue, more controls for positioning of inner elements.
* [Off Canvas] - Added z-index controls for both backdrop & inner content.

= 1.1.1 ( June 18, 2020 ) =
* [Off Canvas] - Fixed an issue with chosen selector not triggering Off Canvas.
* [Preloader] - Fixed slight glitchy animation on iPhones.

= 1.1 ( June 18, 2020 ) =
* [Cart Counter] - New component for displaying Woocommerce Cart Count.
* [Mini Cart] - New component for displaying Woocommerce Mini Cart.
* [Preloader] - New component for building preloaders to hide FOUC or FOUT.
* [Fluent Form] - Added style controls for Payment Summary and Checkable Grids.
* [Fluent Form] - Added "General Styles" for overall form typography, button transitions.
* [Off Canvas] - Slide from Top/Button now available.
* [Off Canvas] - Can now be triggered from inside a modal if click trigger is also a trigger for closing the modal.
* [Slide Menu] - Prevent issue with browsers auto-scrolling with hashlinks & sub menu items collapsing height.

= 1.0.9 ( June 13, 2020 ) =
* [Fluent Form] Added support for Smart UI styling, added more style options and renamed controls to match official Fluent Forms.
* [Fluent Form] Fixed code issue if FF not active.
* [Reading Time] Added "Text After (Singular)" and "Text After (Plurarl)" settings for customizable After text.
* [Off Canvas] Menu items with hash links inside Off Canvas can now open submenu by clicking entire menu item.
* Fixed license activation/deactivation issue especially after site has been migrated to a new location.
* A few other general code polishes.

= 1.0.8 ( June 10, 2020 ) =
* [Adjacent Posts] Fixed an issue with the next post showing even if empty.

= 1.0.7 ( June 09, 2020 ) =
* [Fluent Form] Added a check to ensure that there will be no errors if Fluent Forms is not active.

= 1.0.6 ( June 09, 2020 ) =
* [Fluent Form] Added dropdown for selecting form by name, instead of ID
* [Lottie Animation] Added Click Animation Trigger with optional reverse second clicks.
* [Lottie Animation] Easier controls with sliders for frames and speed & width / height.
* [Back to Top] Added ability to include any element inside button to build manually.
* [Back to Top] Added option to be visible only when scrolling up.
* [Off Canvas] Fixed issue with iPhone 5/6 with backdrop.
* [Off Canvas] Added auto close if any hash links clicked from inside off canvas.
* [Adjacent Posts] Prev/next posts can now be split across two components for more flexible positioning.
* [Alert Box] Now can add divs inside without issue.

= 1.0.5 ( June 05, 2020 ) =
* [Fluent Form] Added more focus styles to forms (& more style options for multi step forms).
* [Lottie Animation] Added Top/Bottom offset controls to scroll animations.
* [Lottie Animation] Added cursor position based animation.
* [Lottie Animation] Added the ability for sync scrolling to any container.
* [Lottie Animation] Added the ability to toggle loop on/off.
* [Lottie Animation] Fixed an issue with scrolling not working with multiple animations.

= 1.0.4 ( June 04, 2020 ) =
* Fixed - Button hover issue in Back to Top.
* Fixed - Off Canvas builder visibility causing elements to be unclickable.
* New - Option to add custom aria label to Burger Trigger button.
* Fixed - Prevent duplicate IDs on search icons.
* Edit - Removed the ability to change Slide Menu type in media queries to prevent issues.

= 1.0.3 ( June 03, 2020 ) =
* Fixed duplicate ID on icons in the Adjacent Posts component.
* Fixed a bug in the Slide Menu component causing it not to function properly when hidden by default.
* Moved "Open / Close Trigger selector" setting in Off Canvas component to the Primary tab for easier access.
* Changed container elements' tags from "span" to "div" in Back to Top component's output.
* Added a screenshot under the License Key form showing where the extras added by the plugin can be found.

= 1.0.2 ( June 02, 2020 ) =
* Fixed Burger Trigger and Off Canvas components not appearing.

= 1.0.1 ( June 02, 2020 ) =
* Added a link to Settings under the plugin name.

= 1.0.0 ( June 02, 2020 ) =
* Initial release
