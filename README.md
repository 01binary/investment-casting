# Investment Casting for Makers

Three years ago I decided to setup a foundry for producing high-detail aluminum casts using the investment casting process. After enduring trial and error and compiling resources & tips from experts in the field, I can help you get started using this process for your projects.

## Advantages

| Investment Casting                               | Sand Casting                                                                       | Cold Casting                                                        | Metal 3D Printing                                                                           |
|--------------------------------------------------|------------------------------------------------------------------------------------|---------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| Highly detailed parts, little finishing required | Grainy surface, satisfactory for functional parts where appearance is not a factor | Partially composed of resin, deforms at 90°F, not fire proof        | Grainy surface requires finishing                                                           |
| Temperature resistant (deforms at 550°F)         | Does not reproduce very small details                                              | Requires finishing for seamless metal appearance                    | Mechanically weaker than cast metal parts (1% elongation)                                   |
| Mechanically strong (3.5% elongation)            |                                                                                    | [read more...](https://www.smooth-on.com/product-line/metal-powder/)| [read more...](https://www.protolabs.com/services/3d-printing/direct-metal-laser-sintering/)|

## Minimum cost to get started

| Investment Casting | Sand Casting       | Cold Casting                                       | Metal 3D Printing         |
|--------------------|--------------------|----------------------------------------------------|---------------------------|
| $1500              | $200               | $50                                                | $100                      |
| Small parts        | Use common tools   | Per part, for small parts; one batch of tiny parts | Per part, for small parts |

## The Process

The original model is cast four times (two positives and two negatives), with the final positive cast out of the chosen alloy.

[ilustration]

The first negative is a rubber mold, with the original model released and the resulting cavity filled with wax. The wax positive is then removed from the rubber mold, attached to a rubber base with sprues, and put inside of a steel container called "flask". The flask is then filled with specially formulated plaster called "investment".

When the investment sets, the wax is steamed or flash-fired, leaving a hard mold. This mold, still inside a flask, is fired in a kiln to evacuate water and strengthen the investment before metal can be poured. Flasks used in investment casting are perforated to enable vacuum-assist casting, which forces the air out of the mold and pulls the metal in to fill intricate details.

See the budget presets at the end of this article for a complete list of all tools mentioned here. Several price breaks are included for most tools to help you control the costs.

## Producing the model

With investment casting you can reproduce every detail of the master model, such as polished surfaces and sharp features. The only finishing required is cutting off sprues and restoring lost detail in places where the sprues used to connect.

You can make a master model by:
* 3D printing with manual finishing either by priming and sanding or by using [XTC-3D](https://www.smooth-on.com/product-line/xtc-3d/). 3D printing is also possible [directly with wax](https://www.riogrande.com/product/digitalwax-009j-jewelry-making-rapid-prototype-machine/700930), although wax printers are still too expensive.
* CNC machining out of wood, styrene, or [machinable wax](https://www.amazon.com/Flexbar-Machinable-Wax-3-1-5/dp/B001C1929G). Stacked profile layers are a popular way to produce complex models using a conventional 3-axis wood CNC.
* Separating a complex model into sub-parts for machining by hand, then combining and finishing with Bondo/primer to produce one seamless object.

> Note that aluminum casts can be up to 5% smaller than the original, depending on the alloy. This only matters when they are combined with other parts produced through a different method – otherwise they fit into each other like the master models.

## Producing the rubber mold

To make a rubber mold, build a wooden or plastic box slightly larger than the model, fix the model in the box, and pour rubber over it. If you keep the box walls as separate components, you can quickly build boxes of any pre-determined size.

If you simply cut the master model out of the mold with an X-Acto knife you will produce a one-part mold, but releasing a fragile wax pattern cast from this mold could be next to impossible without breaking it. For this reason, complex models require two-part molds.

You can also create additional geometry at this stage to aid degassing or to add strength to the wax pattern cast from the mold:

* Cut vents directly into the rubber mold in concave areas where you find large bubbles collecting and preventing a complete fill.
* Add supports to strengthen thin areas that would break when de-molding.

Remove these additional features after casting with a wax pen.

## Selecting rubber

Choose a rubber compound depending on the size of the parts to be cast:
* Smaller parts (about 6" or less in all dimensions) can use wax injection, which doesn’t require high-temperature rubbers. RTV rubbers used in jewelry casting can be selected, for example [Ditto RTV](https://www.riogrande.com/product/ditto-clear-rtv-mold-rubber-kit-1-1-lb/701025) or [LiquaFast RTV](https://www.riogrande.com/product/liquafast-ice-rtv-silicone-molding-compound-1kg/701043) silicone.
* Large parts require degassing inside of a vacuum oven where the rubber will be subjected to temperatures in excess of 400°F. This requires a heat-resistant silicone like [DragonSkin](https://www.smooth-on.com/product-line/dragon-skin/).

## Degassing rubber

Entrapped gas is a concern with rubber molds as any bubbles held at the surface of the model by surface tension will become filled spheres on a cast positive. To prevent this, spray the model with a mold release compound before pouring the rubber.

Degass the rubber before pouring by placing the container in a vacuum chamber until full vacuum is reached and the rubber "boils over". To remove the remaining bubbles after pouring, vibrate the mold 1 to 3 hours until the rubber sets by using an oscillator/shaker.

## Selecting wax

Select a pattern wax based on mechanical strength and expansion ratio, which are directly related. With "machinable" wax every mold can be a simple one-part mold because the casts are less likely to break when pulled out of the mold. On the other hand, investment will be cracked by expanding wax during flash-firing or autoclaving if the wax has a high enough expansion ratio.

## Casting a wax pattern

The tools and process required to cast wax patterns from rubber molds depend on the size of the parts:
* Small parts can be cast using a wax injector commonly used for jewelry casting. Many feature levels are available with advanced models able to vacuum the mold before injecting to ensure a perfect fill and an absence of bubbles. A wax injector consists of a pot where the wax is melted and a thick needle through which wax enters the mold when a foot switch is pressed.
* Large parts require several iterations of pouring wax into the mold and degassing in a vacuum oven. Vacuum ovens are often used in pharmaceutical labs and so are priced on an industrial budget, requiring continuous and expensive maintenance. When using a vacuum oven, wax can be melted in a Presto pot and poured directly into the mold. Casting in a vacuum oven is usually done at 200-300 F, with molds pre-heated before the first pour.

## Spruing and Gating

After you "chase" the wax pattern by removing any vents and supports with a wax pen, attach it to a rubber base using sprues. When you invest the flask later, the rubber base will give the top of the flask a funnel shape for pouring metal.

You can sprue patterns faster by using bulk-extruded wax sprues and breaking off pieces of any required length. Connecting sprues to the rubber base and the model with "sticky wax" will also reduce re-work and form stronger connections. A poorly attached wax pattern will break off the base and float to the surface as the flask is being invested.

Use fewer sprues and place them at strategic points ("gates") following thin sections, which will give the metal alternate pathways for filling the mold before solidifying. Placing too many gates in close proximity will cause turbulence from several streams of molten metal colliding under pressure and wasting energy otherwise used to fill mold details, which will result in incomplete fills. Turbulence can also break off small internal features of the mold and they will end up being embedded in the casting as "inclusions".

## Selecting investment

Select your investment based on the metal alloy (ferrous or non-ferrous) and extra features like less dust while mixing. Examples include [UltraVest](https://www.riogrande.com/Product/ransom--randolph-ultra-vest-investment-100-lbs/702313), [FOV](https://www.riogrande.com/product/fov-premium-blend-investment-44-lbs/701699), [Advantage](https://www.riogrande.com/product/ransom-and-randolph-advantage-investment-50-lbs/702327), and [Kerr Satin](https://www.riogrande.com/product/kerr-satin-cast-20-investment-100-lbs/702099). Investment powder is sold by weight in boxes or drums, and mixed with de-ionized water based on a ratio prescribed by the manufacturer. I prefer UltraVest for aluminum casting.

## Mixin investment

De-ionize the water before mixing it with investment to filter out mineral particles that weaken the mold. Portable de-ionizers are easy to get because they are also used for washing cars.

I prefer using rubber bowls for mixing; plastic containers become consumables, requiring continuous replacement. Calculate the volume of investment required to fill the flask an inch above the model. Then, consult the table provided by the manufacturer to determine the weight of investment and water required for mixing. When several mix ratios are available, start in the middle and then select a ratio resulting in the strongest mold (more investment) while providing enough working time (more water).

Fill one rubber bowl with water and another one with investment, using a digital scale for weighing. Then, sift the investment into the water with a whisk. Blend any clumps quickly, leaving enough time to vacuum and pour the investment. If the mixture thickens before the process is complete it will not fill the whole flask. Large amounts of investment set faster than small amounts.

## Degassing investment

Degass the liquid investment in a vacuum chamber twice while vibrating it with an oscillator: first after mixing and then after pouring into the flask. The vacuum chamber and pump must be well maintained to reach full vacuum before the investment starts thickening.

If the investment molds still have bubbles after vacuuming, spray a layer of anti-sticking compound on the wax patterns before investing. One example is Rio VacuFilm, which can be mixed into a gallon of methyl alcohol using a gradated beaker.

## Investing

Place the flask on top of a rubber base with a wax pattern, and attach it using enough painter’s tape to ensure it won’t detach when vibrated. You can wind the rest of the flask with the same tape, or purchase a sleeve along with the flask and use it to immediately cover the whole flask.

Pour investment into the flask at an angle to avoid creating more bubbles and use a funnel to reduce spillage. Store in a dry, vibration free area after the last degassing. Investment sets in 6-8 hours, then you can remove the rubber base and the painter’s tape. Lastly, scrape the flask with a fettling knife to remove any investment overhangs that could cause it to get stuck in the vacuum-assist chamber.

## Flash-firing and Autoclaving

You can remove the wax from from the invested mold by flash-firing or autoclaving:
* During flash-firing, the wax is carbonized inside the mold before it has a chance to expand. This process generates thick black smoke, which leaves tiny particles of carbonized wax on every surface if not removed properly by a fan paired with an after-burner. Transfer the flasks into a hot furnace quickly to prevent cracks in the investment molds due to wax expansion.
* Autoclaving requires a pressure cooker and a stove but only generates water vapor, which can be removed with a small ventilation system, leaving no residue to cleanup. The steam causes the outer layer of wax to permeate into the mold, leaving enough space for the wax to expand and trickle out. Evacuated wax then collects on the bottom of the canner in a flat donut shape, making it easy to remove in one piece.

## Burnout

Following autoclaving or flash-firing, burn out the molds in a kiln using the schedule provided by the investment supplier in order to evacuate water and fuse silica particles in the micro-structure of the mold. Molds with intricate details require a longer burnout to achieve higher strength. Large molds require more time due to the amount of material to undergo transformation.

A manual kiln requires constant and close monitoring as mistakes result in cracked molds. Programmable kilns are expensive because they are marketed to dentists and jewelers, but they save time and increase quality. Another option popular with makers is adding thermocouples and a controller to a used manual kiln.

> Running a kiln requires a metal desk, a room with a stone floor, all non-ceramic surfaces covered with sheet rock, corners sealed with fire foam, and a ventilation system. Large kilns run on 220-240V and require converting a 120V circuit, installing fuses, and routing through a fusible safety switch. These changes should be included in budget and feasibility analysis.

Transfer autoclaved molds directly into a pre-heated kiln to avoid cracking from rapid cool-down. When using flash-firing the burnout can start immediately in the same kiln.

## Selecting metal

Choose an alloy designed for casting rather than machining, for example 356 instead of 6061. The [356](https://www.makeitfrom.com/material-properties/356.0-SG70A-A03560-Cast-Aluminum) alloy is used for car engine blocks and computer heat sinks, so it’s easy to acquire on the Internet in the form of de-drossed and degassed ingots.

## Metal casting

Your goal when casting is to transfer the flask from the kiln to the vacuum assist chamber and pour metal in 2 minutes or less. This avoids a thermal shock that can destroy intricate mold details as the flask rapidly cools to room temperature, causing them to break off and become embedded in the casting.

Keep the flasks in the kiln at 700°F, the recommended casting temperature for Aluminum 356, until you are ready to pour. Position the vacuum-assist chamber close the burnout kiln so that the flasks can be transferred quickly. Take the crucible out of the forge and place it nearby before opening the kiln to remove a flask. Allow the metal to cool for 1 to 3 minutes from the melting temperature (800°F-1000°F) down to 700°F to match the flask. Use a thermocouple probe for taking measurements.

Once the metal in the crucible reaches the casting temperature, transfer the flask into the
vacuum-assist chamber with a running vacuum pump. Use a temperature resistant O-ring to seal the flask flange to the top of the chamber. This will generate vacuum around the outside of the flask, drawing gases inside the flask out through the walls. While the small gas particles can permeate the mold due to its porous microstructure, the metal cannot. Instead the metal will be pulled toward the walls of the mold, precisely capturing surface details.

If the vacuum is not enough to achieve a complete fill, you can attach a "riser" to the top of the flask to increase the weight of metal pushing down into the mold. Risers also let you pour quickly because they buffer the metal and feed it at a slower rate while keeping it hot. Install a ceramic filter inside the riser to prevent pieces of forge refractory, dust, and other unwanted particles from entering the mold and becoming inclusions.

Finally, tilt the crucible with a shank to pour metal into the flask. I will cover running the forge and building the vacuum-assist chamber in future articles. The vacuum-assist chamber is simply a [do-it-yourself](https://www.youtube.com/watch?v=3BikL2yIDic) version of a [vacuum casting machine](https://products.riogrande.com/content/Instruction-Sheets/Neutec-Catalog.pdf) pioneered by Neutec.

## Finishing

You can use metal files, sanding wheel, and sand paper to finish cast pieces after you snip sprues with a sprue cutter. For intricate detailing, try using a flex shaft tool.

## Tools and Consumables

In this section I list all tools and consumables mentioned throughout the article with a few budget presets for each. The items I use are highlighted in yellow.

### Tools

| Tool          | $$$$$ | $$$$ | $$$ | $$ | $ |
| Burnout Kiln  | $2750