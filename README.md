# Investment Casting for Makers

Three years ago I set out to build a foundry for producing high-detail aluminum casts using the investment casting process. After enduring trial and error and compiling resources & tips from experts in the field, I can help you get started using this process for your projects.

## Advantages

<table style="table-layout:fixed">
	<tbody>
		<tr>
			<th>Investment Casting</th>
			<th>Green Sand Casting</th>
			<th>Cold Casting</th>
			<th>Metal 3D Printing</th>
		</tr>
		<tr>
			<td>
				<ul>
					<li>Highly detailed parts, little finishing required</li>
					<li>Temperature resistant (deforms at 500°F <a target="__blank" href="https://www.makeitfrom.com/material-properties/356.0-SG70A-A03560-Cast-Aluminum">*</a>)</li>
					<li>Mechanically strong (3.5% elongation <a target="__blank" href="https://www.makeitfrom.com/material-properties/356.0-SG70A-A03560-Cast-Aluminum">*</a>)</li>
				</ul>
			</td>
			<td>
				<ul>
					<li>Grainy surface, requires advanced techniques and extensive finishing to improve</li>
					<li>Does not reproduce very small or complex details</li>
				</ul>
				<a target="__blank" href="http://www.foundry101.com/new_page_7.htm">read more...</a>
			</td>
			<td>
				<ul>
					<li>Partially composed of resin, deforms at 90°F, not fire proof</li>
					<li>Requires finishing for seamless metal appearance</li>
				</ul>
				<a target="__blank" href="https://www.smooth-on.com/product-line/metal-powder/">read more...</a>
			</td>
			<td>
				<ul>
					<li>Grainy surface requires finishing</li>
					<li>Mechanically weaker than cast metal parts (1% elongation <a target="__blank" href="https://www.protolabs.com/media/1011285/aluminum-alsi10mg-material-spec-data-sheet.pdf">*</a>)</li>
				</ul>
				<a target="__blank" href="https://www.protolabs.com/services/3d-printing/direct-metal-laser-sintering/" target="__blank">read more...</a>
			</td>
		</tr>
		<tr>
			<td colspan="4">
				Minimum cost to get started (high quality and precise casts)
			</td>
		</tr>
		<tr>
			<td>
				<h2>$1500</h2>
				Foundry for producing small parts (build the forge yourself)
			</td>
			<td>
				<h2>$200</h2>
				Foundry for producing small parts (build most tools yourself)<br><br>
			</td>
			<td>
				<h2>$50</h2>
				Per part, for small parts<br><br><br>
			</td>
			<td>
				<h2>$180</h2>
				Per part, for small parts<br><br><br>
			</td>
		</tr>
	</tbody>
</table>

## The Process

The original model is cast four times (two positives and two negatives), with the final positive cast out of the chosen alloy.

[illustration]

1. The first negative is a rubber mold, with the original model released and the resulting cavity filled with wax.
2. The wax positive is then removed from the rubber mold, attached to a rubber base with sprues, and put inside of a steel container called "flask". The flask is then filled with specially formulated plaster called "investment".
3. When the investment sets, the wax is steamed or flash-fired, leaving a hard negative mold. This mold, still inside a flask, is fired in a kiln to evacuate water and strengthen the investment.
4. Finally, metal is poured to cast the final positive. Flasks used in investment casting are perforated to enable vacuum-assist casting, which forces the air out of the mold and pulls the metal in to fill intricate details.

See the budget presets at the end of this article for a complete list of all tools mentioned here.

## Producing the model

With investment casting you can reproduce every detail of the master model, such as polished surfaces and sharp features. The only finishing required is cutting off sprues and restoring lost detail in places where the sprues used to connect.

You can make a master model by:
* 3D printing with manual finishing either by priming and sanding or by using [XTC-3D](https://www.smooth-on.com/product-line/xtc-3d/). 3D printing is also possible [directly with wax](https://www.riogrande.com/product/digitalwax-009j-jewelry-making-rapid-prototype-machine/700930), although wax printers are still expensive.
* CNC machining out of wood, styrene, or [machinable wax](https://www.amazon.com/Flexbar-Machinable-Wax-3-1-5/dp/B001C1929G). Stacked profile layers are a popular way to produce complex models using a conventional 3-axis wood CNC.
* Separating a complex model into sub-parts for machining by hand, then combining and finishing with Bondo/primer to produce one seamless object.

Aluminum casts can be up to 5% smaller than the original, depending on the alloy. This only matters when they are combined with other parts produced through a different method – otherwise they fit into each other like the master models.

## Producing the rubber mold

To make a rubber mold, build a wooden or plastic box slightly larger than the model, fix the model in the box, and pour rubber over it. If you keep the box walls as separate components, you can quickly build boxes of any pre-determined size.

If you simply cut the master model out of the mold with an X-Acto knife you will produce a one-part mold, but releasing a fragile wax pattern cast from this mold could be next to impossible without breaking it. For this reason, complex models require [two-part molds](https://www.youtube.com/watch?v=DEVi0mEaJJQ).

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

Select your investment based on the metal alloy (ferrous or non-ferrous) and extra features like less dust while mixing. Examples include [UltraVest](https://www.riogrande.com/Product/ransom--randolph-ultra-vest-investment-100-lbs/702313), [FOV](https://www.riogrande.com/product/fov-premium-blend-investment-44-lbs/701699), [Advantage](https://www.riogrande.com/product/ransom-and-randolph-advantage-investment-50-lbs/702327), and [Kerr Satin](https://www.riogrande.com/product/kerr-satin-cast-20-investment-100-lbs/702099). Investment powder is sold by weight in boxes or drums, and mixed with deionized water based on a ratio prescribed by the manufacturer. I prefer UltraVest for aluminum casting.

## Mixing investment

Deionize the water before mixing it with investment to filter out mineral particles that weaken the mold. Portable deionizers are easy to get because they are also used for washing cars.

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

Once the metal in the crucible reaches the casting temperature, transfer the flask into the vacuum-assist chamber with a running vacuum pump. Use a temperature resistant O-ring to seal the flask flange to the top of the chamber. This will generate vacuum around the outside of the flask, drawing gases inside the flask out through the walls. While the small gas particles can permeate the mold due to its porous microstructure, the metal cannot. Instead the metal will be pulled toward the walls of the mold, precisely capturing surface details.

If the vacuum is not enough to achieve a complete fill, you can attach a "riser" to the top of the flask to increase the weight of metal pushing down into the mold. Risers also let you pour quickly and avoid dangerous spills because they buffer the metal and feed it at a slower rate while keeping it hot. Install a ceramic filter inside the riser to prevent pieces of forge refractory, dust, and other unwanted particles from entering the mold and becoming inclusions.

Finally, tilt the crucible with a shank to pour metal into the flask. I will cover running the forge and building the vacuum-assist chamber in future articles. The vacuum-assist chamber is simply a [do-it-yourself](https://www.youtube.com/watch?v=3BikL2yIDic) version of a [vacuum casting machine](https://products.riogrande.com/content/Instruction-Sheets/Neutec-Catalog.pdf) pioneered by Neutec.

## De-vesting

Wait a total of 20 minutes after the pour before quenching the flask in a bucket filled with water. You can remove the flask from the vacuum-assist chamber when the portion of metal visible from the outside solidifies.

The top of the flask will blow out a chunk of investment on contact with water. Use a fettling knife to increase the size of the resulting hole, scooping investment out of the flask while dipping it in water.

You can grab the cast by the sprue with pliers and wiggle it out of the flask, making it easier to scoop out remaining investment. Used investment can be stored in the same bucket or in a thick plastic bag until it's taken to the dump.

## Finishing

You can use metal files, sanding wheel, and sand paper to finish cast pieces after you snip sprues with a sprue cutter. For intricate detailing, try using a flex shaft tool.

## Tools and Consumables

In this section I list all tools and consumables mentioned throughout the article with a few budget presets for each. You can build any of these tools yourself to save on the cost, if you are willing to spend the time.

### Tools

<table>
	<tbody>
		<tr>
			<th>Tool</th>
			<th>$$$$$</th>
			<th>$$$$</th>
			<th>$$$</th>
			<th>$$</th>
			<th>$</th>
		</tr>
		<tr>
			<td>Burnout Kiln</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-extra-large-programmable-oven/703017">
						$2750
					</a>
				</h3>
				+$300 shipping<br>
				18"x18"x18"<br>
				programmable<br>
				[new]
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-large-programmable-oven/703022">
						$2400
					</a>
				</h3>
				+$300 shipping<br>
				14”x14”x14”<br>
				programmable<br>
				[new]
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Programmable-Fiber-Furnace/253236407481">
						$1250
					</a>
				</h3>
				+$300 shipping<br>
				10.5”<br>
				x10.5”x7.5”<br>
				programmable
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/RapidFire-TableTop-Programmable-Ceramic-Precious-Metal-Clay-Jewelry-Kiln-Furnace/381553072012">
						$500
					</a>
				</h3>
				free shipping<br>
				6”x5”x6”<br>
				programmable<br>
				[used]<br>
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/p/Compact-Electrical-Muffle-Kiln-with-Digital-Temperature-Controller-Two-Movable-Tile-shelves-R14-Q/1956318322?iid=312064015894">
						$300
					</a>
				</h3>
				+$55 shipping<br>
				7”x4”x4”<br>
				programmable<br>
				[used]
			</td>
		</tr>
		<tr>
			<td rowspan="2">
				Vacuum Oven<br><br>
				or<br><br>
				Wax Injector<br>
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00BEIH65O?ref=emc_b_5_t">
						$2190
					</a>
				</h3>
				free shipping<br>
				16”x14.5”x14"
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B009WSJNNQ?ref=emc_b_5_t">
						$1390
					</a>
				</h3>
				free shipping<br>
				12”x12”x11”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Value-Vacs-0-9CF-Vacuum-Degassing/dp/B072JNQ271">
						$1100
					</a>
				</h3>
				free shipping<br>
				12”x12”x11”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/OrangeA-Sterilizing-temperature-Controller-Extraction/dp/B01NCP1RTD">
						$670
					</a>
				</h3>
				free shipping<br>
				12”x12”x11”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B075ZMPN4H/">
						$655
					</a>
				</h3>
				free shipping<br>
				12”x12”x11”
			</td>
		</tr>
		<tr>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-digital-vacuum-wax-injectors/700914gp">
						$2100
					</a>
				</h3>
				+$30 shipping<br>
				vacuum 3 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/dura-bull-four-quart-air-pressure-wax-injector/700057">
						$625
					</a>
				</h3>
				+$30 shipping<br>
				4 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-four-quart-air-pressure-wax-injector/700125">
						$575
					</a>
				</h3>
				+$30 shipping<br>
				4 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Digital-Vacuum-Wax-Injector-Jewelry-Casting-Machine-for-Jeweler-Tools-220V/332460625503">
						$538
					</a>
				</h3>
				free shipping<br>
				vacuum 3kg
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-mini-hand-wax-injector-with-thermostat/700047">
						$225
					</a>
				</h3>
				+$30 shipping<br>
				1 pint
			</td>
		</tr>
		<tr>
			<td>Vacuum Pump</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.bestvaluevacs.com/pro-series-11-3cfm-corrosion-resistant-two-stage-vacuum-pump.html">
						$2300
					</a>
				</h3>
				+$60 shipping<br>
				two stage<br>
				11.3 cfm<br>
				[no-corrosion]
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.bestvaluevacs.com/best-value-vacs-ve2100-12cfm-two-stage-vacuum-pump-4007.html">
						$410
					</a>
				</h3>
				+$35 shipping<br>
				two stage<br>
				12 cfm
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.bestvaluevacs.com/best-value-vacs-ve280-9cfm-two-stage-vacuum-pump-4006.html">
						$365
					</a>
				</h3>
				+$35 shipping<br>
				two stage<br>
				9 cfm
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00SXGOXFG/">
						$306
					</a>
				</h3>
				free shipping<br>
				single stage<br>
				7 cfm
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Value-Brand-Single-Stage-Vacuum/dp/B013ENREW6/">
						$180
					</a>
				</h3>
				free shipping<br>
				single stage<br>
				7 cfm
			</td>
		</tr>
		<tr>
			<td>Vacuum Chamber</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Gallon-300mm450mm-Stainless-Degassing-Chamber/dp/B072LSX379/">
						$174
					</a>
				</h3>
				free shipping<br>
				8.4 gallon
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01NAH0EWN/ref=sspa_dk_detail_2?psc=1">
						$105
					</a>
				</h3>
				free shipping<br>
				5 gallon
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01N9FGDTY/">
						$95
					</a>
				</h3>
				free shipping<br>
				3 gallon
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01NAGN0AT/">
						$78
					</a>
				</h3>
				free shipping<br>
				1.5 gallon
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01AO0P5NW/">
						$56
					</a>
				</h3>
				free shipping<br>
				1.5 quart
			</td>
		</tr>
		<tr>
			<td>Vacuum Assist Chamber</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/neutec-j-2r-casting-machine-ce-certified/710040ce">
						$7195
					</a>
				</h3>
				$300 shipping<br>
				4”x9” flasks
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/v-i-c-12-tabletop-solid-and-perforated-flask-casting-machine-with-the-rio-assistant-110-volt/70511814">
						$1925
					</a>
				</h3>
				+$30 shipping<br>
				5”x7” flasks
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Superland-Combination-Mini-Vacuum-Investing-Investment/dp/B072KDMYX1">
						$656
					</a>
				</h3>
				free shipping<br>
				4”x7” flasks
			</td>
			<td colspan="2">
				<h3>
					$50
					<a target="__blank" href="https://www.youtube.com/watch?v=3BikL2yIDic">
						do it yourself
					</a>
				</h3>
				steel plate and pipe, RTV silicone<br>
				up to 16” diam. flasks, any height
			</td>
		</tr>
		<tr>
			<td>Vacuum Assist Riser Fixture</td>
			<td colspan="5">
				<h3>
					$20 - $100
					<a target="__blank" href="https://www.youtube.com/watch?v=HV-b1_D8RJs">
						do it yourself
					</a>
					option for do it yourself vacuum assist chamber
				</h3>
				<strong>parts</strong>: steel plate, steel pipe, ceramic blanket<br>
				<strong>tools</strong>: steel cutter, lathe and welder required (or talk to your local welding contractor)
			</td>
		</tr>
		<tr>
			<td>Forge</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B0197A24RU">
						$745.50
					</a>
				</h3>
				free shipping<br>
				table top<br>
				2.56”x4.92”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Metal-Melting-Furnace-FB2M-Propane-Foundry-Kwik-Kiln-Forge-Gold-Silver-Copper/251901919391">
						$600
					</a>
				</h3>
				free shipping<br>
				outdoor<br>
				8”x10”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Metal-Melting-Furnace-FB1S-Propane-Foundry-Kwik-Jewelry-Gold-Silver-Copper/261498065505">
						$380
					</a>
				</h3>
				free shipping<<br>
				outdoor<br>
				4”x7.4”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/VEVOR-Capacity-Refining-Precious-Aluminum/dp/B071FSSX68">
						$360
					</a>
				</h3>
				free shipping<br>
				table top<br>
				2.56”x4.92”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/p/Metal-Melting-Furnace-FB1Sb-Propane-Foundry-Kwik-Jewelry-Gold-Silver-Copper/1153096501">
						$250
					</a>
				</h3>
				free shipping<br>
				outdoor<br>
				6”x7.6”
			</td>
		</tr>
		<tr>
			<td>Crucible</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Salamander-Clay-Graphite-Morgan-Crucibles-Super-A-16-Furnace-Melt-Non-Ferrous/200636865881">
						$92.87
					</a>
				</h3>
				free shipping<br>
				outdoor
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Pure-Graphite-Crucible-Metal-Melting-Gold-Silver-Scrap-Casting-Ingot-Mould-5KG/222691515940">
						$48.47
					</a>
				</h3>
				free shipping<br>
				table top
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/8-10-KG-Clay-Graphite-Foundry-Crucible-Melting-Furnace-Refining-Gold-Silver-CU/321201746624">
						$39.95
					</a>
				</h3>
				free shipping<br>
				outdoor
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B07415C5C4">
						$33.99
					</a>
				</h3>
				free shipping<br>
				table top
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Graphite-Crucible-Melting-Silver-Casting/dp/B01934GVQK">
						$16.90
					</a>
				</h3>
				free shipping<br>
				table top
			</td>
		</tr>
		<tr>
			<td>Propane Tank</td>
			<td colspan="5">
				<h3>
					<a target="__blank" href="https://www.lowes.com/pd/Blue-Rhino-15-lb-Pre-Filled-Propane-Tank/4781957">
						$48.22
					</a>
				</h3>
				15 lb
			</td>
		</tr>
		<tr>
			<td>Fan</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B003T9CKR0">
						$309.01
					</a>
				</h3>
				$30 shipping<br>
				12” 820 cfm
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00903HDK8">
						$152.61
					</a>
				</h3>
				14 shipping<br>
				10” 810 cfm
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01M13M24R">
						$147.75
					</a>
				</h3>
				free shipping<br>
				4” 100 cfm
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Vortex-Powerfans-VTX400-172-Powerfan/dp/B0055F6Z7C/">
						$115.94
					</a>
				</h3>
				free shipping<br>
				4” 172cfm
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/gp/product/B0043235K8">
						$66.85
					</a>
				</h3>
				$13 shipping<br>
				10” 500cfm
			</td>
		</tr>
		<tr>
			<td>Oscillator</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/ELMI-DOS-20M-Digital-Orbital-Platform/dp/B008XRLZCE">
						$909.22
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B008XRM0XM">
						$678.83
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Adjustable-Speed-Orbital-Shaker-Rotator/dp/B002TEQI42">
						$120
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Dental-Vibrator-Round-Dentist-Equipment/dp/B00S0X7QHO">
						$59.00
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Frankford-Arsenal-Quick-n-EZ-Case-Tumbler/dp/B001MYGLJC">
						$39.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Scale</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/USA-Digital-Shipping-Stainless-Platform/dp/B01LXRW17R">
						$129.99
					</a>
				</h3>
				+$10 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/ZIEIS-Capacity-Stainless-Platform-Accuracy/dp/B0042L04PO/">
						$94.97
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/digital-investment-scale-11-lb-5kg/702108">
						$41.25
					</a>
				</h3>
				+$13 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B0171DN6R2">
						$12
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/1byone-Digital-Kitchen-Cooking-Baking/dp/B01D9XKDNS/">
						$8.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>
				Pressure Cooker
				(autoclaving)
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/All-American-2-Quart-Pressure-Cooker/dp/B0002808ZM">
						$499.99
					</a>
				</h3>
				free shipping<br>
				41.5 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00MCLRFQW">
						$349.99
					</a>
				</h3>
				free shipping<br>
				30 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B0002808YS">
						$299.99
					</a>
				</h3>
				free shipping<br>
				25 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Presto-01781-23-Quart-Pressure-Canner">
						$70.39
					</a>
				</h3>
				+$10 shipping<br>
				23 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Mirro-Polished-Aluminum-Pressure-Cookware/dp/B000RNH7PQ">
						$61.99
					</a>
				</h3>
				free shipping<br>
				22 quart
			</td>
		</tr>
		<tr>
			<td>Deionizer</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Go-Spotless-Portable-Dual-Deionizer/dp/B00KVPO21C/">
						$420
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/CR-Spotless-Deionized-Water-System/dp/B0056HDCUM">
						$249.88
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B0144MFPOA">
						$99.95
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00523AMBC">
						$44.94
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B0024E6V30">
						$17.64
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Pyrometer</td>
			<td colspan="4" rowspan="3">
				<h3>
					<a target="__blank" href="http://mifco.com/shop/pyrometers/mt-400-portable-hand-lance-pyrometer/">
						$340 (Pyrometer with Probe and Lance)
					</a>
				</h3>
				$10 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Various-K-Type-Thermocouple-Probe-Sensor-Temperature-Controller-50-to-1200/282579316824">
						$4.29
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Probe</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Various-K-Type-Thermocouple-Probe-Sensor-Temperature-Controller-50-to-1200/282579316824">
						$4.35
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Lance</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.lowes.com/pd/Common-1-2-in-Actual-50-In-Metallic-Emt-10-ft-Conduit/3129551">
						$3.00
					</a>
				</h3>
				do it yourself
			</td>
		</tr>
		<tr>
			<td>Rubber Bowls</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rubber-Mixing-Bowl-1-Gal/702132">
						$17.75
					</a>
				</h3>
				+$5 shipping<br>
				1 gallon
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rubber-Mixing-Bowl-1-12-Qt/702131">
						$9.25
					</a>
				</h3>
				+$5 shipping<br>
				1.5 quart
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Dental-Lab-Hygienist-Flexible-Mixing-Bowl-Rubber-Size-Large-Green-for-Impression/180428891851">
						$5.15
					</a>
				</h3>
				+$5 shipping<br>
				1 pint
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Dental-Lab-Hygienist-Flexible-Mixing-Bowl-Rubber-Size-Large-Green-for-Impression/180428891851">
						$6.00
					</a>
				</h3>
				free shipping<br>
				1 pint
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/New-10cm-Dental-Lab-Hygienist-Flexible-Mixing-Bowl-Rubber-Dental-Emporium/152860196168">
						$1.05
					</a>
				</h3>
				+$3.3 shipping<br>
				9.5cm x 7cm
			</td>
		</tr>
		<tr>
			<td>Waxer Pen</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/kerr-ultra-waxer-2/700574">
						$325
					</a>
				</h3>
				+$8 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/foredom-wax-carving-pen/700331">
						$195.50
					</a>
				</h3>
				+$8.00 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/giles-precision-wax-pen-tool/700391">
						$165
					</a>
				</h3>
				+$8 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-benchmount-ii-wax-pen-system/700457">
						$149
					</a>
				</h3>
				+$8 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Dental-Electric-Wax-Waxer-Carver-Double-Carving-Pen-pencil-6-Tip-Pot-2018-NEW/121308997601">
						$31.11
					</a>
				</h3>
				+$7.9 shipping
			</td>
		</tr>
		<tr>
			<td>Wax Warmer (sticky wax)</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Dental-Lab-BesQual-S800-Digital-Multi-Wax-Pot-3-x-Digital-Dipping-Pots/272867180222">
						$167.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/BesQual-E100-Digital-Wax-Pot-4-Compartment-Dental-Lab/292274197663">
						$117.50
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/digital-three-well-wax-melting-pot-with-lid/700101">
						$99.95
					</a>
				</h3>
				$8 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/wax-melting-or-treeing-pot/700607">
						$35.50
					</a>
				</h3>
				$8 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Dental-Lab-Electric-Wax-Waxer-3-Well-Analog-Melting-Dipping-Heater-Pot-Machine/122642117908">
						$28
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Wax Pot (pattern wax)</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/PRESTO-POT-X-LARGE-WAX-MELTER-CANDLE-MAKING-WITH-SPOUT-WAX-MELTING/332118767581">
						$199.95
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/PRESTO-POT-X-LARGE-WAX-MELTER-CANDLE-MAKING-WITH-SPOUT-WAX-MELTING/231339863625">
						$99.95
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/PRESTO-POT-WAX-MELTER-WAX-MELTING-WITH-SPOUT-LIFETIME-WARRANTY/230422075172">
						$78.83
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/PRESTO-POT-8lb-WAX-MELTER-LIFETIME-WARRANTY-FREE-SHIPPING/182567297772">
						$62.95
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Ingot Mold</td>
			<td>
				<h3>
					<a target="__blank" href="http://www.budgetcastingsupply.com/product-p/6172-008.htm">
						$39.00
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/50oz-1-5KG-Cast-Iron-Ingot-Mould-Silver-Gold-Bar-Foundry-Melting-Casting-Metal/302624064470">
						$23.42
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Lee-Precision-Ingot-Mold/292315094262">
						$13.81
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/SODIAL-Melting-Casting-Refining-Graphite/dp/B074FST7LW">
						$9.05
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					$5
				</h3>
				do it yourself
			</td>
		</tr>
		<tr>
			<td>Crucible Shank</td>
			<td>
				<h3>
					<a target="__blank" href="http://mifco.com/shop/shanks-bails/s890se-adjustable-latching-single-end-shank/">
						$603
					</a>
				</h3>
				+$30 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="http://www.budgetcastingsupply.com/Crucible-Pouring-Shank-p/6080-s1.htm">
						$295
					</a>
				</h3>
				+$30 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="http://mifco.com/shop/shanks-bails/s16h-latching-hand-shank/">
						$224
					</a>
				</h3>
				+ $20 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="http://mifco.com/shop/shanks-bails/020705-ladle-shank-9-dia-id-ring/">
						$101
					</a>
				</h3>
				+$15 shipping
			</td>
			<td>
				<h3>
					$10
				</h3>
				do it yourself
			</td>
		</tr>
		<tr>
			<td>Crucible Tongs</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="http://www.budgetcastingsupply.com/Crucible-Lifting-Tongs-p/6061-t1.htm">
						$225
					</a>
				</h3>
				+ $20 shipping
			</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.amazon.com/Carbon-Foundry-Crucible-Casting-Precious/dp/B019QR8DG0/">
						$34
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Flask Tongs</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.amazon.com/Crucible-Graphite-Refinery-Crucibles-Refining/dp/B00EUG5NJI">
						$59.99
					</a>
				</h3>
				free shipping
			</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B075QNVW2X">
						$19.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Perforated Flask</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Neutec-SuperPerf-Flanged-Flask-with-Cross-Bar-6-dia/702198N">
						$96.85
					</a>
				</h3>
				+$13 shipping<br>
				6”x9”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Neutec-SuperPerf-Flanged-Flask-with-Cross-Bar-5-dia/702196N">
						$76.90
					</a>
				</h3>
				+$10 shipping<br>
				5”x9”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Neutec-SuperPerf-Flanged-Flask-with-Cross-Bar-4-dia/702194N">
						$59.75
					</a>
				</h3>
				+$8 shipping<br>
				4”x9”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Neutec-SuperPerf-Flanged-Flask-with-Cross-Bar-3-12-dia/702199N">
						$52.60
					</a>
				</h3>
				+$8 shipping<br>
				3.5”x8”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Neutec-SuperPerf-Flanged-Flask-with-Cross-Bar-2-12-dia/702184N">
						$34.25
					</a>
				</h3>
				+$8 shipping<br>
				2.5”x4”
			</td>
		</tr>
		<tr>
			<td>Rubber Base</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/neusprue-base-assembly-6-dia/710914">
						$9.50
					</a>
				</h3>
				+$8 shipping<br>
				6”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rubber-Round-Button-C-Style-Sprue-Base-5-dia/702710">
						$4.95
					</a>
				</h3>
				+$8 shipping<br>
				5”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rubber-Round-Button-C-Style-Sprue-Base-4-dia/702709">
						$4.05
					</a>
				</h3>
				+$8 shipping<br>
				4”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rubber-Round-Button-C-Style-Sprue-Base-3-12-dia/702708">
						$3.75
					</a>
				</h3>
				+$8 shipping<br>
				3.5”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rubber-Round-Button-C-Style-Sprue-Base-2-12-dia/702706">
						$3.50
					</a>
				</h3>
				+$8 shipping<br>
				2.5”
			</td>
		</tr>
		<tr>
			<td rowspan="2">
				Flask Sleeve<br><br>
				or<br><br>
				Painter's Tape
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Disposable-Shrink-Band-for-6-Perforated-Flask/702065">
						$109.95
					</a>
				</h3>
				+$8 shipping<br>
				6”x12”x1200
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Disposable-Shrink-Band-for-5-Perforated-Flask/710969">
						$84.20
					</a>
				</h3>
				+$8 shipping<br>
				5”x9”x1200
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Disposable-Shrink-Band-for-4-Perforated-Flask/710963">
						$65.80
					</a>
				</h3>
				+$8 shipping<br>
				4”x8”x1200
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Disposable-Shrink-Band-for-3-12-Perforated-Flask/710958">
						$60.50
					</a>
				</h3>
				+$8 shipping<br>
				3.5”x8”x1200
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rubber-Flask-Sleeve-9H-x-4-dia/702308">
						$20.25
					</a>
				</h3>
				+$8 shipping<br>
				4”x9” rubber
			</td>
		</tr>
		<tr>
			<td colspan="3">
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B0747YRSSR">
						$108.95
					</a>
					x 24
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B075VP6RRZ">
						$14.99
					</a>
					x 3
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/XFasten-Professional-Painters-Yards-Single/dp/B01F2UYER2">
						$8.97
					</a>
					x 1
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Flask O-Ring</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Silicone-Flask-Gasket-6-dia/710394">
						$69.00
					</a>
				</h3>
				+$8 shipping<br>
				6” diameter
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Silicone-Flask-Gasket-5-dia/710405">
						$67.50
					</a>
				</h3>
				+$8 shipping<br>
				5” diameter
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Silicone-Flask-Gasket-4-dia/710393">
						$67.50
					</a>
				</h3>
				+$8 shipping<br>
				4” diameter
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Silicone-Flask-Gasket-3-12-dia/710392">
						$61.50
					</a>
				</h3>
				+$8 shipping
				3.5” diameter
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Silicone-Flask-Gasket-2-12-dia/710390">
						$52.50
					</a>
				</h3>
				+$8 shipping
				2.5” diameter
			</td>
		</tr>
		<tr>
			<td>Bulk Extruded Sprues</td>
			<td colspan="3">
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Bulk-Extruded-Red-Sprue-Wax-38-dia/700017">
						$30.25
					</a>
				</h3>
				+$8 shipping<br>
				3/8” diameter
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Bulk-Extruded-Red-Sprue-Wax-12-dia/700020">
						$28.25
					</a>
				</h3>
				+$8 shipping<br>
				1/2” diameter
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Bulk-Extruded-Red-Sprue-Wax-14-dia/700014">
						$28.25
					</a>
				</h3>
				+$8 shipping<br>
				1/4" diameter
			</td>
		</tr>
		<tr>
			<td>Sprayer</td>
			<td colspan="5">
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00YY8Q5R6">
						$13
					</a>
					x 2
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Flex Shaft</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/foredom-k-2845-system-with-lx-motor-h-15-and-h-18-handpieces-and-c-sxr-foot-control/117608">
						$523.60
					</a>
				</h3>
				+$13 shipping<br>
				hi-HP motor
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/foredom-txh440-industrial-system/117552">
						$389.30
					</a>
				</h3>
				+$13 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/foredom-sr-motor-with-h-20-quick-change-handpiece-flex-shaft-systems/117535gp">
						$305.15
					</a>
				</h3>
				+$13 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/prodigy-flex-shaft-system-with-quick-change-handpiece/117097">
						$119
					</a>
				</h3>
				+$13 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Shaft-System-Horsepower-Motor-HDP-150-00/dp/B00OV9BJU6/">
						$93.25
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Fireproof Boots</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/gp/product/B001L8P7A8">
						$130
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.shoes.com/carolina-ca3630/522396/1099805">
						$109.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/gp/product/B06XGGYCKJ">
						$94.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://workboots.com/iron-age-6-ground-breaker-st-black">
						$89.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/Mens-Work-Safety-Welder-Steel-Toe-High-Top-Boots-Leather-Wearproof-Work-Shoes-/391485574058">
						$39.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Fettling Knife</td>
			<td colspan="5">
				<h3>
					<a target="__blank" href="https://www.amazon.com/Art-Advantage-8-Inch-Fettling-Knife/dp/B0027A7A86">
						$6.54
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>X-Acto Knife</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00004Z2UB">
						$20.18
					</a>
				</h3>
				free shipping
			</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.amazon.com/X-ACTO-2-Knife-Safety-Cap/dp/B000V1QV7O">
						$5.40
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Sprue Cutter</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-heavy-duty-pneumatic-sprue-cutter/706039">
						$500
					</a>
				</h3>
				$15 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00FARY81U/">
						$122.10
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/heavy-duty-pro-cutters/111018">
						$25.85
					</a>
				</h3>
				+$8 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/DIAGONAL-PLASTIC-CUTTING-CV-STEEL-NOVELTOOLS/dp/B010GJTBXG">
						$15.87
					</a>
				</h3>
				+$4 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Jonard-Carbon-Steel-Flush-Cutter/dp/B00AIBH45K">
						$10.08
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Sander</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/foredom-polishing-bench-lathe-with-hoods/334015">
						$299
					</a>
				</h3>
				+$30 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Zorvo-Function-Electrical-Grinding-Polishing/dp/B0798MQBQK">
						$159.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Neiko-10205A-6-Inch-Grinder-Buffing/dp/B000T0F1QO">
						$77.95
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/rio-variable-speed-lathe/330031">
						$59
					</a>
				</h3>
				+$13 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Benchtop-Buffer-Heavy-buffing-wheels/dp/B005R57J34/">
						$56.89
					</a>
				</h3>
				+$13 shipping
			</td>
		</tr>
	</tbody>
</table>

### Consumables

<table>
	<tbody>
		<tr>
			<th>Consumable</th>
			<th>$$$</th>
			<th>$$</th>
			<th>$</th>
		</tr>
		<tr>
			<td>Investment (non-ferrous)</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/kerr-satin-cast-20-investment-100-lbs/702099">
						$98
					</a>
				</h3>
				+$30 shipping<br>
				100 lb drum
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01K7H02KS">
						$90
					</a>
				</h3>
				free shipping<br>
				100 lb drum
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/ransom-and-randolph-ultra-vest-investment-50-lbs/702314">
						$42.65
					</a>
				</h3>
				+$13 shipping
				50 lb box
			</td>
		</tr>
		<tr>
			<td>Aluminum (356 alloy)</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/ALUMINUM-INGOTS-43-lbs-26-to-30-ingots-Casting-alloy/182166261652">
						$125
					</a>
				</h3>
				free shipping<br>
				43 lbs.
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/ALUMINUM-INGOTS-28-lbs-17-to-19-ingots-Casting-alloy/171236930125">
						$90
					</a>
				</h3>
				free shipping<br>
				28 lbs.
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.ebay.com/itm/ALUMINUM-INGOTS-14-lbs-8-to-10-ingots-made-from-casting-alloy/172236970449">
						$51
					</a>
				</h3>
				free shipping<br>
				14 lbs.
			</td>
		</tr>
		<tr>
			<td>Rubber (room temperature vulcanization)</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/liquafast-ice-rtv-silicone-molding-compound-4kg/701045">
						$210.85
					</a>
				</h3>
				+$16 shipping<br>
				fast-setting<br>
				8 lbs.
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://shop.smooth-on.com/dragon-skin-10-medium">
						$183.72
					</a>
				</h3>
				+$33.23 shipping<br>
				hi-temp 450 F<br>
				16 lbs.
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/ditto-clear-rtv-mold-rubber-kit-1-1-lb/701025">
						$48.50
					</a>
				</h3>
				+$8 shipping<br>
				generic 400 F<br>
				1.1 lbs.
			</td>
		</tr>
		<tr>
			<td>Wood for box molds</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Midwest-Products-Co-5326-Plywood/dp/B000MNKTU6">
						$17.58
					</a>
				</h3>
				free shipping<br>
				base<br>
				3/8”x12”x24”
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.lowes.com/pd/Common-1-in-x-4-in-x-8-ft-Actual-0-75-in-x-3-5-in-x-8-ft-Poplar-Board/1000074283">
						$16.24
					</a>
				</h3>
				store pickup<br>
				walls<br>
				3/4”x3.5”x8’
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Jili-Online-Pieces-Natural-Rectangle/dp/B06XW4W6YT">
						$14.94
					</a>
				</h3>
				free shipping<br>
				walls<br>
				1.5”x4”x1/4”
			</td>
		</tr>
		<tr>
			<td>Nails for box molds</td>
			<td colspan="3">
				<h3>
					<a target="__blank" href="https://www.amazon.com/ARROW-160457-1-Wire-Nails/dp/B00VEDF246">
						$2.29
					</a>
				</h3>
				free shipping<br>
				wire nails 1” x 100
			</td>
		</tr>
		<tr>
			<td>Vaseline for box molds (rubber release agent)</td>
			<td colspan="3">
				<h3>
					<a target="__blank" href="https://www.amazon.com/Vaseline-Percent-Pure-Petroleum-Jelly/dp/B01FAL44ZU">
						$8.17
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Sealant for box molds (seal cracks after building)</td>
			<td colspan="3">
				<h3>
					<a target="__blank" href="https://www.amazon.com/Sargent-Art-Plastilina-Modeling-5-Pound/dp/B00FR7TR1O">
						$13.91
					</a>
				</h3>
			</td>
		</tr>
		<tr>
			<td>Sticky Wax</td>
			<td>
				<h3>
					<a target="__blank" href="http://www.remet.com/range/specialty-wax/">
						$60
					</a>
				</h3>
				$25.65 shipping
				50 lbs.
			</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/modelers-sticky-wax-pellets/700160">
						$10.75
					</a>
					/ lb
				</h3>
				+$8-25 shipping
			</td>
		</tr>
		<tr>
			<td>Methyl Alcohol</td>
			<td colspan="3">
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/methyl-alcohol/700003gp">
						$11.95
					</a>
				</h3>
				+$7.99 shipping (hazardous materials)<br>
				1 quart
			</td>
		</tr>
		<tr>
			<td>VacuFilm</td>
			<td colspan="3">
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/Rio-Vacu-Film-Concentrate/7021521">
						$21.90
					</a>
				</h3>
				+$37.99 shipping (hazardous materials)<br>
				10.90 ounces
			</td>
		</tr>
		<tr>
			<td>Risers &amp; Filters</td>
			<td colspan="3">
				<h3>
					<a target="__blank" href="http://www.mgstevens.com/riser-sleeves.html">
						$177
					</a>
					x 50
				</h3>
				$100 shipping
			</td>
		</tr>
		<tr>
			<td>Flint Lighter</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/ALLY-Tools-Triple-Striker-Rotatable/dp/B016C9TWK6/">
						$15.47
					</a>
				</h3>
				free shipping<br>
				4 tip replacements included
			</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.amazon.com/US-Forge-Welding-Lighter-00506/dp/B000UVHGXS">
						$8.88
					</a>
				</h3>
				free shipping<br>
				extra small
			</td>
		</tr>
		<tr>
			<td>FlexShaft Fittings</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/flex-shaft-accessory-kit/338310">
						$36.50
					</a>
				</h3>
				free shipping<br>
				1/8” shank (Foredom)
			</td>
			<td colspan="2">
				<h3>
					<a target="__blank" href="https://www.amazon.com/gp/product/B01MQYLQVI">
						$18.97
					</a>
				</h3>
				free shipping<br>
				1/8” shank (EuroTool)
			</td>
		</tr>
		<tr>
			<td>Respirator</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/3M-6000-Series-Full-Face-Respirator/201652">
						$149
					</a>
				</h3>
				free shipping<br>
				full face
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/3m-7500-series-half-face-respirators/201669gp">
						$29.95
					</a>
				</h3>
				free shipping<br>
				half face
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.harborfreight.com/p95-maintenance-free-dual-cartridge-respirator-66554.html">
						$16.99
					</a>
				</h3>
				+$6.99 shipping<br>
				half face
			</td>
		</tr>
		<tr>
			<td>Casting gloves</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/casting-gloves/704104gp">
						$39.50
					</a>
				</h3>
				$8 shipping<br>
				800 F, 1000 F spike
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/ZaoProteks-ZP2102-Resistant-Temperature-Aluminized/dp/B01MT8GUN8">
						$38.60
					</a>
				</h3>
				free shipping<br>
				482 F, 1000 F spike
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Resistant-Melting-Furnace-Refining-Casting/dp/B07178ZQCB">
						$26.45
					</a>
				</h3>
				free shipping<br>
				400 F, 800 F spike
			</td>
		</tr>
		<tr>
			<td>Casting apron</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.riogrande.com/product/heat-resistant-safety-apron/750160">
						$165
					</a>
				</h3>
				$5 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Welding-Protective-Apparel-Cowhide-Leather/dp/B079CTJ9LJ">
						$60
					</a>
				</h3>
				+$3.45 shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Welding-Aluminized-Resistant-Apparel-Safety/dp/B018HVUJ40">
						$29.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Nitrile gloves (investment mixing)</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B074V3HQD7">
						$14.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/AMMEX-GPNB46100-BX-GlovePlus-Disposable-Industrial">
						$10.58
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/Pro-Purple-Nitrile-Gloves-Medium/dp/B01EZQTUNW/">
						$6.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Vinyl Gloves (silicone mixing)</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01AE5YE2K">
						$13
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B00CF492OE/">
						$7.57
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/West-Chester-2750-Industrial-Disposable/dp/B002ZPO4A0/">
						$3.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Jumpsuit</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B006OC0OZE">
						$49.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B074TPL3TT">
						$40
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B005HJ8PFQ">
						$34.99
					</a>
				</h3>
				free shipping
			</td>
		</tr>
		<tr>
			<td>Bucket (quenching, investment waste)</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B010G3M7ZG">
						$38.49
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B01N1WHEH4">
						$14.99
					</a>
				</h3>
				free shipping
			</td>
			<td>
				<h3>
					<a target="__blank" href="https://www.amazon.com/dp/B077BST14P/ref=sspa_dk_detail_5">
						$11.95
					</a>
				</h3>
				free shipping
			</td>
		</tr>
	</tbody>
</table>