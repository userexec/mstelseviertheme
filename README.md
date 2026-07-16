# Missouri S&T Elsevier Pure Theme

This is a working space for a theme for Missouri S&T's Elsevier Pure instance. It contains assets that should be used in the theme along with a ruleset combined from Elsevier's documentation and Missouri S&T's branding guidelines. Also included are examples of other Elsevier Pure instances for reference.

## Elsevier Theme requirements

Elsevier's customization guidelines can be found at https://digitalcommons.elsevier.com/setup-and-design/dc-design-customization-guide

This page should be referenced to ensure the design suggested is possible within the system.

## Missouri S&T Branding requirements

Missouri S&T's branding requirements can be found at https://brand.mst.edu, though are summarized here in the following headings. For any clarifications required, visit https://brand.mst.edu.

### Colors

Allowable colors other than white and black are divided into primary and secondary palettes.

#### Primary

The primary palette is all variations of green, with Forest and Miner being the most commonly used, and Lima and Kiwi used to set off Forest and Miner respectively.

 - Forest #154734
 - Miner #007A33
 - Lima #72BF44
 - Kiwi #BFD730

#### Secondary

The secondary palette can be used as needed to complement and support the primary colors when creating user interfaces.

##### Blues

Used to set off greens mostly. Blues are the most common secondary colors to greens in the palette.

 - Mist #B1E4E3
 - Scooter #2DCCD3
 - Lagoon #00858A
 - Orient #005F83
 - Cyprus #003B49

##### Grays and Golds

Used more often in alumni and print productions, but still useful in digital in rare cases such as setting off backdrops or fields.

 - Shuttle #63666A
 - Petra #ACA199
 - Pebble #D6D1CA
 - Vegas #CEB888
 - Gold #D9AB28
 - Silver #B3B4B2

##### Other colors

Often used in small UI features to denote statuses or highlighting.

 - Candle #FDD923
 - Tango #E77724
 - Ruby #AD2327
 - Amethyst #403A60

### Fonts

This one's easy, it's Libre Franklin. That's all. Headers and content alike, any weight, but all Libre Franklin.

Technically Orgon Slab is a font that can be used too, but as it must be manually added to systems instead of being pulled in via Google Fonts, it's rare for it to be used and it will likely not be used in this project.

### Logos

The library's allowable logos are provided under the logos folder as PNGs. Four variants are provided:

 - "horizontal brief.png" - Horizontal logo with only the unit identity
 - "horizontal full.png" - Horizontal logo with the unit and org identity
 - "vertical brief.png" - Vertical logo with only the unit identity
 - "vertical full.png" - Vertical logo with the unit and org identity

Any of the four logos are acceptable. Since these are presented as separate assets, you can assume they will be baked onto the cover photo when its final size and positioning is decided, or will go in a header bar separate from the cover photo. Either way at a conceptual stage it may be overlaid onto the cover photo if needed and the requirements of Elsevier's design document may be ignored here--in the final design it won't be a floating box outside their spec but added into the cover graphic if placement over the cover graphic is chosen.

### Patterns

Allowable graphic patterns can be found at https://brand.mst.edu/elements/ and consist of "blocks," "diagonal," "diamonds," "dots," "hexagonal," and "honeycomb." It is not necessary to use a pattern, but if one is used it should be one of these using the provided samples on that page as a reference for what the pattern should look like. The pattern may be faded out, as demonstrated in that page's header, if desired.

## Special Instructions

### Cover/header photo

By request of the unit, a photo that should be prominently featured in this design is in "images/cover.jpg". This is implemented as part of a slideshow instead of baked into the template to retain flexibility across collections and save screen space on pages where large graphics would be a distraction. Elsevier's support for slideshows is unknown--whatever is in the system should be used.

### Icons

The homepage should prominently feature an icon in its body area. The icons are provided in the "icons" folder and named according to the text that should accompany them. For example, the icon "Theses and Dissertations.png" should be labeled "Theses and Dissertations". Only 6 of the icons are used on the homepage. Others are presumably meant to feature on other pages as the system is populated.