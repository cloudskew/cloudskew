# CloudSkew

Create Azure architecture diagrams for free! Start [here](https://www.cloudskew.com/).

[![CloudSkew](https://cloudskewprod.azureedge.net/assets/misc/landing-page-hero-2.jpg)](https://www.cloudskew.com/)

## Available features :heavy_check_mark:

The following features are available in CloudSkew right now:

* Icons for Azure, GCP, CNCF and more are preloaded in the app. 
* Create a new diagram from a template (or simply a new empty diagram).
* Print a diagram and/or export it to `.png`, `.jpg` or `.bmp` formats.
* Lock an entire diagram or just individual symbols (locking make things read-only, preventing them from being edited or deleted).
* Adjust visual properties of any symbol via the `visual properties` window.
* Diagrams are auto-saved.
* Load icons/symbols from symbol palette onto diagram by single-clicking on it.
* Search for an icon by typing in the icon name (or a synonym or category) in the symbol search box.
* Undo & redo actions.
* Access frequent commands via context menu (cut, copy, paste, delete etc).
* Adjust z-index of any symbol on the diagram (via context menu).
* Zoom in & out of a diagram.
* Import custom images into a diagram (.png, .jpg formats only, file size must be < 512 KB).
* Any selected symbol's information is displayed via tooltip on hover.
* Attach text labels to any symbol. Labels can be re-positioned, re-sized, rotated and styled (via properties window).

## Planned features :calendar:

In the near team, the following features are on the roadmap:

* View & adjust z-index of diagram symbols via a separate control.
* Group multiple symbols together.
* Save checkpoints/snapshots (along with ability to restore-from/rollback-to a previous checkpoint).  
* Keyboard shortcuts for commonly performed actions.
* More icons, shapes and diagram templates. You can always request specific ones [here](https://github.com/cloudskew/cloudskew/issues/new/choose). You can view existing open requests [here](https://github.com/cloudskew/cloudskew/issues?q=is%3Aopen+is%3Aissue+label%3Aicon-request).

The relative priorities of these planned features will depend on the volume of user requests received. If you have a feature request that's not listed up here, you can file a new one [here](https://github.com/cloudskew/cloudskew/issues/new/choose).

You can see all the [planned milestones](https://github.com/cloudskew/cloudskew/milestones) and [release annoucements](https://github.com/cloudskew/cloudskew/releases).

## Found a bug? :beetle:

Please report it [here](https://github.com/cloudskew/cloudskew/issues/new/choose).

## Pricing :dollar:

CloudSkew will remain free for individual users. There are plans to add premium features for teams & enterprises in the future.

## Icon attribution :clap:

A big thanks to all the icon creators for all their hard work!

* [Azure icons](https://www.microsoft.com/en-in/download/details.aspx?id=41937)
* [Auth0 icons](https://identicons.dev/) ([github](https://github.com/auth0/identicons))
* [AWS icons](https://aws.amazon.com/architecture/icons/)
* [CNCF icons](https://github.com/cncf/artwork)
* [DevIcons](https://konpa.github.io/devicon/) ([github](https://github.com/konpa/devicon/))
* [Elasticsearch icons](https://www.elastic.co/brand)
* [GCP icons](https://cloud.google.com/icons/)

## Frequently asked questions :grey_question:

**Why can't the diagram canvas be resized?**

The diagram size is restricted to 900px x 500px (landscape mode). While it's possible to zoom in/out, it's not possible to change a diagram's height, width & orientation.

Custom diagram sizes might be enabled at a future point as a premium/paid feature.

**Any plans to auto-generate diagrams from existing infrastructure?**

Not in the [near-term future](#planned-features-calendar).

**Any plans to improve the experience on mobile devices?**

No plans. The web app is best used on laptops and desktops (screen resolutions higher than 960 x 540, landscape mode).

**Why doesn't the app work correctly in Internet Explorer (IE)?**

To be honest, I haven't tested it in IE. No plans to add support for IE since it is [now deprecated](https://support.microsoft.com/en-in/help/17454/lifecycle-faq-internet-explorer).

**Is this an open source project?**

No. However, would love to open source parts of it in the future to invite community contributions around:

* icons from different cloud providers.
* templates for some frequently created diagrams.

However not there yet, lot of features have to be added before all this can be enabled.

**Why are users required to login?**

The diagrams are auto-saved, which requires users to be logged in. Auto-save was a convenience feature requested by many of the initial test users. 

Also some upcoming features (checkpoints, restoring from checkpoints etc) will require users to be authenticated.

**What does the CloudSkew architecture look like?**

Take a [look](https://assets.cloudskew.com/assets/misc/cloudskew-architecture-20200116.png).
