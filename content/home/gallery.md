+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Artwork"
subtitle = "Click on an image to view caption and open gallery"

# Order that this section will appear in.
weight = 15

+++
{{< load-photoswipe >}}
{{< gallery hover-effect="none" caption-position="none" >}}
# {{< gallery dir="/img/memes/" >}}
{{< figure src="/img/memes/nlp-thumb.jpg" link="/img/memes/nlp.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
# {{< figure link="/img/me_two.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
# {{< figure link="/img/me_two.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
# {{< figure link="/img/me_two.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
# {{< figure link="/img/me_two.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
# {{< figure link="/img/me_two.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
# {{< figure link="/img/me_two.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
{{< /gallery >}}