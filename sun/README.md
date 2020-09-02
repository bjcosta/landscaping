<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-177071585-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-177071585-1');
</script>


# Thoughtful Solar Design

<https://www.permaculturenews.org/2015/10/23/charting-the-suns-motion-in-relation-to-your-home-and-permaculture-site/>

> For proper functioning and productivity gardens, greenhouses and orchards should be placed at specific locations based on the adequate availability of sunshine for the parts of the year in which the plants are growing or fruiting.


## Observation

I first created a timelapse of the shadows in the existing landscape. This is a base line and I used it to check any models I created below and see if they were correct. I was using my old mobile phone so the image quality isnt great but it gives a good idea of how the shadows track in the old yard:

<video width="480" height="320" controls="controls">
  <source src="timelapse.mp4" type="video/mp4">
</video>


## Sunpath 3D

There are many tools that can be used to visualize the path of the sun at various times in the year at your specific location (Its different depending on where you live). One of the better ones I found was: <https://drajmarsh.bitbucket.io/sunpath3d.html> (Info at: <http://andrewmarsh.com/software/sunpath3d-web/>)

![sunpath3d.png](sunpath3d.png)


However to get the most use out of it you really want to create a 3D model for showing the shadows cast. I did a really quick and likely incorrect mockup in Fusion 360 using cylinders to represent trees. You can see in the (deliberatly very low bitrate) video below the difference the shadows cast between summer and winter.

[sunpath3d_settings.json](sunpath3d_settings.json)

<video width="480" height="320" controls>
  <source src="summer_solstice_sunpath3d.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


<video width="480" height="320" controls="controls">
  <source src="winter_solstice_sunpath3d.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


## Landscaping Design Software

I roughly knew my site details already, it slopes downwards to the north so we get sunlight to all layers during winter if I have tall trees on the south short on the north. What I really wanted was more detailed view of shadows based on plantings and the location of houses. I wanted to answer questions like:

> If I plant a tree in a given spot does it prevent light getting to other plants in the back-yard that require it.

What I did find a little more useful was the software I used to model my overall landscape design. I really liked the interface and usability of "Realtime Landscaping Pro" from Ideaspectrum. It helps with modeling sloped terrain, houses, and the positioning of trees etc to evaluate where the shadows will be cast throughout the day and evaluate if we think a given plant has enough sunlight to thrive or not.

The biggest issue is that currently realtime Landscaping Pro only shows shadows as if the sun is directly overhead. I have sent in a feature request asking for the ability to configure latitude/longitude and they use an accurate model for the path of the sun in the rendering. Hopefully depending on how their software was written this could potentially be a very simple thing for them to implement if it is just modifying the path of the 3D lighting object.


You can see from the (deliberatly very low bitrate) video below, that most of the trees appear to have good access to sunlight except the understorey (and one of the aqaponic grow beds) is quite shaded. This is likely fine in real-life as the sun is not directly overhead but coming from the North for me which is more open.

I have read that ponds need either full sun (for ecosystem watergarden plants mostly) or a lot of shade (for Koi ponds and aquaponics to prevent algae growth and prevent the Koi getting sunburnt :-) ). So I have also modeled (though no veideo here) adding a lower height wide spreading shade tree/shrub on the north/west of the pond to provide this shading. I will start with the pond in full sun and if that is no good will plant some shading later.

The other benefit is that we can see how things change over time as the plants grow (there are options to change the age maturity of the trees in this software).

<video width="480" height="320" controls>
  <source src="summer_shadows.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

You can also compare the summer vs winter view.

<video width="480" height="320" controls>
  <source src="winter_shadows.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


# Using Vertical Space

## Vertical Gardens

Normal gardens are spread out horizontally and consume a large amount of realestate in a small suburban backyard. The key idea to get the highest density is to make better use of the vertical space and model such that this vertical space usage doesn't overly shade other areas.

Some common solutions to this include using:
* Arbours/Trellises
* Hanging pots
* Vertical hydroponic gardens

I experimented with designing a vertical hydroponic garden. The idea is to have a vertical cylinder hanging from a post or sitting on the ground with plants like leafy greens, strawberries etc planted all around it like a thin tower of plants that normally spread horizonally across the ground. The intent would be to have the tower rotate slowly through the day to permit equal sun access across plants on all sides of the container. The rotation may be possible using the inertia of the water flowing through the tube somehow to reduce any mechanical cost to run extra motors etc.

This was a prototype design that failed miserably :-) The first issue was the complexity, the cups can easily be inserted without requiring 3D printed sleeves. The mounts for the top and bottom of the tower worked well, ad the next part is to design the rotatio mechanism. However I lost some momentum on this and want to complete the larger part of the garden (retaining wall, pond and larger trees planted) before resuming.

![photos/hydro.png](photos/hydro.png)


TODO Much more I can add here
* Retaining wall impact on sunlight
* Potential glass-house location access to near full sun
* Thermal buffering using brick walls/concrete or water tubs
* Some ideas using reflective surfaces
* Floating structures for shading pond (water lillies, or floating plant pots or even decorative models)
* Using hard structure to provide controlled shading like a bridge over the pond
* Planting zone diversity:
  * Zone: Full shade (on south west very shaded/protected)
  * Zone: Shading summer/Sunny winter where table is
  * Zone: Full sun on grass
  * Zone: Open layered sunlight on southern boundary
