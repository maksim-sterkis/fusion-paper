# Fusion: Science, Energy, Industry, Spaceflight, and Civilization-Scale Futures

## A technical research report

**Prepared:** 26 August 2026  
**Audience:** technically literate public, engineers, and policy readers  
**Scope:** controlled fusion for energy and related applications; not weapons design.

### Abstract

Fusion is a family of technologies, not a single impending product. It can be demonstrated in a laboratory whenever light nuclei are brought close enough to react; a practical power system must also create, confine, heat, exhaust, breed fuel for, protect, repair, finance, regulate, and operate that reaction at high availability. The governing result of this report is consequently conditional: deuterium–tritium (D–T) fusion is the credible first fuel cycle for terrestrial power, and magnetic-confinement tokamaks and stellarators are the most developed routes; neither has yet demonstrated a power-plant-relevant, self-sufficient, maintainable electricity system. Inertial fusion has demonstrated target-level ignition, an important scientific milestone, but not an efficient or repetitive power cycle. The near-term social value of fusion may therefore arrive first through research infrastructure and specialized neutron applications rather than bulk grid electricity. Space propulsion is physically interesting but is even further from application because reactor mass, shielding, radiators, and power handling dominate a spacecraft mission.

This paper uses four evidence tiers throughout.

| Tier | Meaning | Appropriate inference |
|---|---|---|
| **Demonstrated** | Independently measured experimental result | It happened under the stated experimental conditions. |
| **Engineered** | Integrated prototype shown under relevant conditions | A subsystem or system can work in its intended operating regime. |
| **Projected** | Modelled result with transparent assumptions | It could work if assumptions, scaling, and integration hold. |
| **Speculative** | Physically plausible but unproven concept | It is a research proposition, not a capability. |

### Executive summary

Fusion releases nuclear binding energy when light nuclei combine into a more tightly bound product. The attractive arithmetic is real: D–T reactions release 17.6 MeV per fusion event, millions of times more energy per unit mass of reactants than chemical combustion. The difficult part is the Coulomb barrier: positively charged nuclei repel one another, so useful reaction rates require exceptionally hot, dense, and well-confined plasma, or an alternative compression scheme. **[Demonstrated]**

The headline word *net energy* is dangerously incomplete. At the National Ignition Facility (NIF), experiments have produced fusion yield exceeding laser energy delivered to the target, a target-level gain and an ignition-related scientific achievement. It does **not** mean a facility exported net electricity, because the laser system consumes far more wall-plug energy than reaches the capsule and no power-conversion plant was operated. **[Demonstrated for target gain; not demonstrated for plant gain]** [1, 2]

ITER is designed to test burning-plasma physics at an approximately Q=10 fusion-power-gain target, while major national DEMO programs study later electricity-producing prototypes. ITER is not designed to supply commercial electricity. Its importance is that a D–T burning plasma at reactor scale is an engineering and scientific prerequisite, not that it settles blanket breeding, availability, maintenance, licensing, or cost. **[Projected design objective]** [3, 4]

The most consequential constraints are not simply achieving fusion reactions. A viable D–T plant requires a tritium breeding ratio with operating margin, robust first-wall and divertor materials under intense 14 MeV neutron exposure, remote replacement of irradiated internal components, high heat-to-electricity conversion efficiency, low recirculating power, and enough availability to service debt. Those requirements interact: a hotter or more compact machine can improve core performance while worsening exhaust and material loads. **[Engineered pieces; whole-plant integration unproven]** [4–7]

Commercial dates announced by companies or governments are milestones, not evidence. The appropriate test is a dated scorecard: report independently verified plasma performance, energy accounting boundary, duty cycle, radiation environment, and demonstrated subsystem lifetime; label everything else as projected. On that test, no fusion enterprise has yet delivered net electricity to a grid or shown a tritium-self-sufficient D–T power-plant cycle. **[Demonstrated absence as of this report date]** [1, 3, 8]

Fusion would complement rather than automatically displace renewables, storage, transmission, efficiency, geothermal energy, and fission. Its possible economic niche is firm low-carbon energy and perhaps high-temperature heat where it can achieve reliable availability and cost. Cheap fuel alone does not make cheap electricity: capital, replacement parts, remote maintenance, financing, and outages dominate the unknowns. **[Projected economic conclusion]**

For spaceflight, a terrestrial fusion power plant is not an engine. A spacecraft needs thrust, specific impulse, reactor and radiator mass, heat rejection, shielding, and reliable startup. Fusion may someday enable high-power electric propulsion or specialized deep-space missions, but it is not a plausible replacement for chemical launch from Earth in the foreseeable future. **[Projected to speculative, depending on concept]**

## 1. Fusion fundamentals

### 1.1 Binding energy and reaction energy

Nuclei are bound by the strong nuclear force. Binding energy per nucleon rises steeply from hydrogen toward iron, so fusing light nuclei can lower the total rest mass. The mass difference appears as kinetic energy and radiation, according to \(E=mc^2\). D–T fusion is

\[
{}^2\mathrm{H}+{}^3\mathrm{H}\rightarrow{}^4\mathrm{He}\,(3.5\ \mathrm{MeV})+n\,(14.1\ \mathrm{MeV}),
\]

for a total of 17.6 MeV. The charged alpha particle can heat a magnetically confined plasma; the neutron has no magnetic charge and deposits most of its energy in surrounding material. **[Demonstrated nuclear physics]** [9, 10]

Fusion and fission are both nuclear-energy technologies, but their control problems differ. Fission reactors sustain neutron-driven chain reactions in solid fuel; fusion requires external conditions—hot fuel, confinement, and sufficient density—to persist. If a magnetic plasma loses confinement or an inertial capsule misses compression, the reaction rate falls rapidly. That eliminates the conventional criticality/runaway mechanism of fission, but it does not eliminate hazards from tritium, activated components, cryogens, magnets, stored energy, or radioactive waste. **[Demonstrated physics; engineered safety implication]**

### 1.2 Coulomb barrier, tunnelling, and reaction rate

Two bare nuclei with charges \(Z_1e\) and \(Z_2e\) repel through the Coulomb potential. Thermal particles need not classically surmount the barrier; quantum tunnelling allows a small fraction of collisions to react. The cross-section is strongly energy-dependent and is conventionally written through an astrophysical S-factor and a Gamow factor. For Maxwellian fuel distributions, the volumetric fusion power scales roughly as

\[
P_f= n_D n_T\langle\sigma v\rangle E_f,
\]

where \(\langle\sigma v\rangle\) is the temperature-dependent reactivity. This exponential sensitivity is why D–T is attractive: its reactivity peaks at much lower temperature than D–\(^3\)He or proton–boron-11 (p–B11). **[Demonstrated theory and data]** [10, 11]

The phrase “fusion temperature” is shorthand, not a switch. A plasma at tens of keV contains a distribution of particle energies, and meaningful output depends on density, temperature, composition, impurities, and confinement. Higher temperature can raise reactivity, but it can also increase losses, reduce stability margin, and intensify material heat flux. **[Demonstrated plasma physics]**

### 1.3 Plasma basics and confinement

A plasma is a quasi-neutral ionized gas whose charged particles collectively respond to electric and magnetic fields. In a magnetic field, particles gyrate around field lines; carefully shaped fields reduce transport across those lines. Important quantities include particle density \(n\), temperature \(T\), energy-confinement time \(\tau_E\), plasma pressure \(p\), and beta \(\beta=p/(B^2/2\mu_0)\), the ratio of plasma pressure to magnetic pressure. A useful reactor must balance pressure high enough for reactions against stability and magnet limits. **[Demonstrated]** [12]

Plasma confinement is not a sealed bottle. Microscopic turbulence, collisions, energetic particles, radiation, and edge losses carry heat and particles outward. Large-scale instabilities can redistribute plasma current or energy abruptly. Magnetic fusion performance is therefore a systems property: geometry, profiles, heating, fueling, feedback control, exhaust, and wall condition all matter. **[Demonstrated]**

### 1.4 Lawson criterion and gain boundaries

The Lawson criterion states that fusion self-heating becomes possible when density, temperature, and confinement meet a fuel-specific condition. A common shorthand is the triple product \(nT\tau_E\). It is a necessary performance measure, not a complete reactor criterion: it does not by itself specify plant efficiency, tritium breeding, availability, or cost. **[Demonstrated theoretical framework]** [13]

Different gains must never be conflated:

| Measure | Numerator / denominator | What it establishes |
|---|---|---|
| \(Q_{plasma}\) | fusion power / external power coupled to plasma | Core plasma performance. |
| Target gain | fusion yield / energy delivered to an ICF target | Capsule-scale performance. |
| Engineering gain | useful fusion thermal energy / facility input energy | System energy balance. |
| Grid gain | exported electrical energy / total purchased electrical energy | Electricity-plant outcome. |
| Economic viability | revenues and system value / all lifecycle costs and risks | A finance and operations outcome. |

An experiment can have high target gain and still have poor wall-plug efficiency; a reactor can have positive thermal engineering gain and still fail economically. **[Definitions; demonstrated accounting distinction]**

### 1.5 Comparison with other energy routes

Chemical combustion is mature, controllable, and energy-dense enough for transport, but emits carbon dioxide when fossil carbon is burned. Fission already produces firm low-carbon electricity at scale but requires a different fuel cycle, safety case, and waste-management regime. Solar and wind convert abundant external energy without reactor fuel, but their output varies with weather and daylight and is integrated through transmission, storage, flexible demand, and firm supply. Antimatter has unmatched mass-energy conversion in principle but is vastly harder to produce and store; it is not an energy source in the terrestrial sense because production consumes far more energy than it returns. **[Demonstrated technologies; comparative system conclusion]**

## 2. Fusion fuel cycles

### 2.1 Deuterium–tritium: the near-term baseline

D–T has the largest useful reactivity at the lowest attainable plasma temperature among practical fusion candidates. Deuterium is available in natural water. Tritium is radioactive (half-life about 12.3 years), scarce in nature, and must be produced, recovered, and carefully contained. A D–T plant is thus not fueled simply by seawater; it is a tritium-management facility coupled to a fusion reactor. **[Demonstrated nuclear data; engineered fuel-cycle challenge]** [9, 14]

Most D–T energy is carried by 14.1 MeV neutrons. A lithium-containing blanket surrounding the vacuum vessel is expected to slow those neutrons, convert their energy to heat, shield magnets and structures, and breed tritium through neutron–lithium reactions. To support a fleet, the plant must achieve tritium breeding ratio (TBR) greater than one after accounting for decay, processing inventories, losses, reserve needs, and measurement uncertainty. A calculated TBR above unity is not evidence of fleet self-sufficiency; it is a design result that needs integrated validation. **[Projected for power plants]** [5, 6]

### 2.2 D–D and D–helium-3

D–D fusion avoids initial tritium input but has lower reactivity and produces a mixture of charged particles, neutrons, tritium, and helium-3. The tritium branch ultimately returns the system to a D–T-like neutron problem. D–\(^3\)He produces a charged proton and alpha particle in its principal branch and has an attractive direct-energy-conversion story, but it requires much hotter plasma and still has side reactions that make neutrons. It also needs large quantities of helium-3, which are not available from an established terrestrial energy supply. **[Demonstrated reaction physics; projected reactor relevance]** [10, 11]

Helium-3 mining on the Moon is frequently presented as a solution to terrestrial energy scarcity. It is not a current energy plan: concentrations, extraction energy, lunar industrial infrastructure, transport, and the harder D–\(^3\)He reactor all remain unresolved. Lunar helium-3 is a resource hypothesis, not a demonstrated fuel supply. **[Speculative economic proposition]**

### 2.3 p–B11 and “aneutronic” claims

The p–B11 reaction produces three alpha particles and is often called aneutronic. Its main attractions are reduced primary neutron production and potentially direct conversion of charged-particle energy. Its liabilities are severe: much lower reactivity at accessible temperatures, required ion energies of order hundreds of keV, bremsstrahlung radiation losses, and unavoidable secondary neutron channels in realistic plasmas. “Aneutronic” should mean neutron-reduced relative to D–T, not radiation-free or easy. **[Demonstrated nuclear physics; projected reactor feasibility]** [10, 11]

### 2.4 Fuel-cycle comparison

| Cycle | Main products | Principal advantage | Principal reactor obstacle | Evidence status |
|---|---|---|---|---|
| D–T | alpha + 14.1 MeV neutron | Highest low-temperature reactivity | Tritium breeding; neutron damage | Best-developed path; no closed plant cycle |
| D–D | mixed n, p, T, \(^3\)He | Deuterium-only input | Low reactivity; neutron and tritium branches | Physics established |
| D–\(^3\)He | alpha + proton | Lower primary neutron fraction | Hotter plasma; helium-3 supply | Physics established; reactor projected |
| p–B11 | three alphas | Neutron-reduced primary reaction | Very difficult reactivity/radiation balance | Physics established; reactor speculative |

## 3. How a fusion power plant would work

A reference magnetic D–T plant has: (1) a fuel and isotope-separation system; (2) a vacuum vessel and plasma-facing first wall; (3) magnets, power supplies, heating and current-drive systems; (4) breeding blankets and shielding; (5) a primary coolant; (6) heat exchangers and a turbine-generator or other conversion system; (7) tritium extraction, detritiation, accounting, and storage; (8) hot cells, cranes, robots, and remote-handling tooling; and (9) conventional electrical and cooling infrastructure. The fusion core is only one subsystem. **[Projected whole-plant architecture; components engineered to varying degrees]** [4–7]

Energy flow is conceptually simple: fusion products heat blanket/coolant material; the coolant transfers heat to a power cycle; a turbine-generator exports electricity. The practical losses are numerous: heating and current drive, cryogenic loads for superconducting magnets, pumps, tritium systems, vacuum, diagnostics, controls, cooling, and outage periods all consume value. A thermal plant with 40% conversion efficiency needs roughly 2.5 units of thermal fusion heat for one unit of gross electricity; net output is lower after internal loads. **[Engineered thermodynamics; projected plant accounting]**

Maintenance separates an experiment from a product. Neutrons displace atoms, create helium and hydrogen in materials, and activate structures. Internal components may require periodic replacement in a radiation field that precludes hands-on work. A competitive plant needs modularity, tolerances, remote tooling, spare parts, a practical outage duration, and demonstrated cumulative lifetime. Availability is not an optional commercial detail: a high capital-cost asset that is offline frequently has expensive electricity even if fuel is cheap. **[Engineered remote handling in nuclear settings; fusion plant availability projected]**

## 4. Magnetic-confinement fusion

### 4.1 Tokamaks

A tokamak uses a strong toroidal magnetic field and a plasma current to create helical field lines that confine a toroidal plasma. It is the most mature high-performance magnetic configuration, with decades of experiments establishing high temperature, significant fusion power, and control methods. Its central weakness is that conventional current drive naturally produces pulsed operation and can produce disruptions—rapid loss or redistribution of current and plasma energy. Non-inductive current drive and bootstrap current can support steady-state operation in principle, but cost, efficiency, and stability remain central issues. **[Demonstrated configuration; steady-state commercial operation projected]** [3, 12]

### 4.2 Stellarators and spherical tokamaks

Stellarators use externally shaped three-dimensional coils to generate rotational transform without relying on a large plasma current. Their appeal is steady-state operation and reduced disruption exposure; their difficulty is exceptionally complex magnet geometry and historically poorer confinement. Modern optimized stellarators, notably Wendelstein 7-X, have substantially advanced confinement and long-pulse operation, but have not demonstrated a power-plant fuel cycle or economics. **[Demonstrated experimental progress; reactor projection]** [15]

Spherical tokamaks use a compact, low-aspect-ratio geometry that can provide high beta and potentially smaller machines. They also impose tight engineering space for center columns, shielding, maintenance, and high-field magnets. Compactness should not be equated with lower plant cost without a full replacement and availability model. **[Demonstrated experiments; cost claim projected]**

### 4.3 Other magnetic configurations

Mirrors, reversed-field pinches, field-reversed configurations (FRCs), compact toroids, and magneto-inertial variants explore different balances of size, pulsing, plasma pressure, and engineering complexity. They are legitimate research areas. The evidence standard should scale with the promise: a short high-temperature pulse or a neutron measurement demonstrates a plasma result, not a net-power system, and a simulation is a projection unless the boundary conditions and validation are clear. **[Demonstrated research platforms; reactor claims vary from projected to speculative]**

### 4.4 Heating, turbulence, and exhaust

Ohmic heating becomes less effective as plasma temperature rises, so reactors use neutral-beam injection, ion/electron cyclotron radiofrequency systems, and electron-cyclotron heating. These systems must be efficient, maintainable, and compatible with high radiation. The edge and divertor must remove helium ash and exhaust heat without contaminating or damaging the core. This is one of fusion’s hardest scaling problems: core energy is intentionally trapped, while exhaust energy must be deliberately concentrated on engineered surfaces. **[Engineered subsystems; reactor heat-flux solution unproven]**

High-temperature superconductors can create stronger fields than conventional low-temperature-superconducting magnet systems at certain operating conditions. Higher field can reduce plasma volume for a given performance target, but it does not remove neutron shielding, joints, quench protection, mechanical stresses, manufacturing capacity, or maintenance constraints. High field changes the trade space; it is not a universal fusion shortcut. **[Engineered material technology; power-plant benefit projected]**

## 5. Inertial-confinement fusion

In inertial confinement fusion (ICF), a tiny fuel capsule is compressed and heated so rapidly that its own inertia confines it briefly. In indirect drive, lasers heat a hohlraum whose x-rays implode the capsule; in direct drive, lasers illuminate the capsule more directly. Compression must be remarkably symmetric. Small asymmetries, hydrodynamic instabilities, mix of shell material into hot fuel, or laser–plasma interactions can lower yield sharply. **[Demonstrated physics and experiments]** [1, 2]

NIF ignition experiments are scientifically important because they have entered a regime in which fusion alpha particles significantly heat the fuel, and shots have exceeded the laser energy delivered to the target. This validates aspects of high-energy-density physics and capsule design. It does not demonstrate a commercial laser-fusion plant: today’s system was built for stockpile-stewardship research, not high wall-plug efficiency, high repetition rate, cheap targets, or rapid chamber turnaround. **[Demonstrated target-level result; power-plant inference not supported]** [1, 2]

A laser-fusion power plant would require driver efficiency, perhaps several shots each second or more depending on plant scale, automated injection and tracking of extremely consistent targets, a chamber that survives repeated neutron and debris pulses, tritium handling, blanket systems, and turbine-grade heat recovery. Heavy-ion drivers and pulsed-power concepts aim at different parts of this trade space, but no integrated repetitive power-plant cycle has been demonstrated. **[Projected]**

## 6. Alternative and emerging approaches

Magnetized target fusion compresses magnetized fuel to relax some requirements of purely magnetic and purely inertial approaches. Z-pinches use current-generated magnetic fields; sheared-flow systems seek stabilization. Dense plasma focus devices and inertial electrostatic confinement systems can generate fusion neutrons and are useful research or source technologies, but their demonstrated energy gains are far from a power plant. **[Demonstrated devices; electricity claims unproven]**

Muon-catalyzed fusion proves that a heavy charged lepton can bring nuclei close enough to fuse at low temperature. It is not an energy source with present technology because making muons costs much more energy than the fusion events release, and muons decay or stick to fusion products. **[Demonstrated physics; nonviable energy system]**

Claims of lattice-confined fusion, low-energy nuclear reactions, or similar extraordinary energy effects require calorimetry with rigorous controls, independent replication, isotopic/nuclear-product diagnostics, and energy accounting. Anomalous heat without decisive nuclear signatures is not evidence of a usable fusion process. The correct classification remains speculative until reproducible independently measured results meet that bar. **[Evidence-standard conclusion]**

## 7. The hardest engineering problems

### 7.1 First wall, divertor, and materials

The first wall faces neutron irradiation, particle bombardment, thermal cycling, and potential off-normal events. The divertor faces exceptionally concentrated heat and particle flux. Tungsten is favored in many concepts because of its high melting point and low sputtering, but it is brittle under some conditions and can contaminate plasma if eroded. Reduced-activation ferritic/martensitic steels, silicon-carbide composites, liquid lithium or lead-lithium concepts, and advanced copper alloys each trade strength, activation, thermal performance, chemical compatibility, and fabrication complexity. **[Engineered materials research; lifetime under full reactor spectrum unproven]** [6, 7]

The D–T neutron spectrum is a particularly hard qualification problem. Neutrons displace atoms, produce helium bubbles and swelling, alter thermal conductivity, and activate structures. Fission-reactor experience is informative but not a full substitute because spectra, temperatures, fluxes, and transmutation products differ. Dedicated materials irradiation sources and representative component tests are therefore strategically important. **[Demonstrated damage mechanisms; fusion-lifetime data gap]**

### 7.2 Tritium and remote maintenance

Tritium permeates and can be retained in materials; it must be measured across fuel, blanket, processing, waste, and environmental pathways. A self-sufficient fuel cycle must have minimal losses and low in-process inventory without sacrificing safety. Any plant claiming a D–T commercial schedule should state its assumed TBR, fractional tritium losses, startup inventory, processing time, reserve policy, and measurement uncertainty. **[Projected requirements]**

Remote maintenance has been developed for hazardous and radioactive environments, and fusion experiments have remote-handling programs. The power-plant question is more stringent: can frequent replacements be completed reliably and quickly enough, with components designed for manipulators rather than human access? This is a manufacturability and operations problem as much as a robotics problem. **[Engineered precedents; fusion-commercial availability projected]**

## 8. Safety, waste, and environmental impact

Fusion cannot sustain a conventional fission-style chain reaction. Loss of suitable plasma conditions sharply reduces fusion power. This is a genuine safety advantage, but it should not be marketed as “no radioactive materials” or “no waste.” D–T facilities manage radioactive tritium and neutron-activated equipment; activated materials need characterization, storage, recycling pathways where feasible, and disposal routes. **[Demonstrated physics; waste classifications jurisdiction-dependent]** [16]

Relevant accident scenarios include tritium releases, coolant or chemical fires, cryogenic hazards, magnet quench events, vacuum failures, stored electrical/magnetic energy, and handling accidents involving activated components. Consequence analysis must be facility-specific. Fusion’s source term and decay profile may be more manageable than long-lived spent fission fuel in some designs, but that conclusion depends on materials choices, contamination, and regulation—not on the word fusion alone. **[Projected comparative safety assessment]**

Lifecycle effects include mining and processing of steel, copper, superconductors, lithium, beryllium or other blanket materials, construction, cooling-water demand, and decommissioning. Like fission, fusion could be low operational-carbon electricity if built and operated successfully; unlike wind and solar it would not require weather-dependent output, but those technologies have their own mature deployment and cost trajectories. Direct comparison needs a consistent lifecycle boundary and current regional grid assumptions. **[Projected lifecycle conclusion]**

## 9. Economics and commercialization

Fusion economics are dominated by uncertainty, not a published levelized-cost number. Capital intensity, construction duration, cost of capital, maintenance intervals, replacement blankets/divertors, unplanned outages, tritium inventory, plant staffing, and decommissioning all matter. A small compact core may reduce some construction costs but can raise power density, material stress, and maintenance frequency; a large core can improve surface-to-volume ratios but increase absolute project risk. **[Projected]**

For grids, the relevant comparison is not fuel cost but the system value of dependable low-carbon power. Firm fusion electricity might complement variable renewables by providing capacity during low-wind/low-sun periods, process heat, hydrogen, or flexible load. It would compete with long-duration storage, transmission, demand flexibility, geothermal energy, biomass with carbon controls, and fission. The outcome will vary by region, finance, resource quality, and demand profile. **[Projected]**

Private-company milestones should be audited with five questions: What energy boundary was measured? Was the result independently reproduced or peer reviewed? What was the duty cycle and availability? What material, tritium, and exhaust problem was included? What must still be invented, scaled, or licensed? A press release announcing a future pilot plant belongs in the projected tier unless supported by a disclosed, independently assessed demonstration. **[Evidence-standard conclusion]**

### 9.1 Deployment scenarios

| Scenario | Description | Conditions that support it | Evidence tier |
|---|---|---|---|
| Constrained | No economic grid fusion by 2050; continued research and neutron uses | Materials, breeding, or availability remain limiting | Projected |
| Niche | First specialized plants or industrial demonstrators mid-century | One design proves maintainability and financeable uptime | Projected |
| Broad late-century | Grid deployment grows after several successful prototypes | Repeatable supply chains, regulation, cost and TBR close | Projected |
| Space-first | Fusion succeeds first for terrestrial neutron/heat niche, later propulsion | Very high specific-power systems demonstrated | Speculative |

## 10. Present fusion ecosystem

Public programs form the evidentiary backbone of fusion: ITER pursues burning-plasma physics and key technologies; JET established major D–T experimental results before ending operations; JT-60SA expands superconducting tokamak research; NIF advances high-energy-density ignition science; Wendelstein 7-X tests optimized stellarator operation; and national DEMO, STEP, CFETR, and related programs study subsequent prototypes. These facilities have different missions and must not be ranked by a single “net-energy” metric. **[Demonstrated facilities; future milestones projected]** [1, 3, 4, 15]

The private sector broadens design exploration and can accelerate manufacturing, software, magnets, and subsystem iteration. It also introduces an incentive to publicize preliminary milestones. Public and private work are complementary when results are made legible: independent diagnostics, clear accounting boundaries, peer review where possible, and disclosure of the engineering assumptions that turn a plasma result into a plant claim. **[Evidence-standard conclusion]**

International collaboration is inherent because fusion combines nuclear materials, advanced computing, superconductors, lasers, high-vacuum manufacturing, and sensitive tritium technologies. Collaboration can distribute cost and knowledge; export controls and intellectual property can slow supply chains or limit verification. Regulation must evolve without assuming that a non-fission hazard profile implies no rigorous safety case. **[Demonstrated institutional fact; policy implications projected]** [4, 16]

## 11. Fusion for electricity generation

### 11.1 What a grid-facing fusion plant must do

Electricity systems do not purchase *fusion reactions*; they purchase power and capacity at defined locations and times. A grid-facing plant must synchronize through conventional power electronics or a turbine-generator, meet fault and frequency requirements, ramp within its design envelope, survive external grid disturbances, and provide credible availability information to system planners. A heat-producing fusion core would ordinarily be coupled to a thermal power cycle, which may be capable of some load-following but has thermal-inertia and component-fatigue limits. **[Engineered requirements; fusion-specific response unproven]**

The traditional label “baseload” is not a physical property. Nuclear and thermal plants can often vary output, but economic optimum and materials life may favor relatively steady operation. In a deeply renewable grid, firm clean capacity is most valuable during extended weather-driven shortfalls, while in an industrial region a plant might maximize value through heat, hydrogen, desalination, or district-heating coproduction. The optimum use case depends on local demand and competing flexibility resources. **[Projected system analysis]**

### 11.2 Cogeneration and regional fit

A power plant rejects substantial low-grade heat even with an efficient steam or supercritical-CO2 cycle. In the right geography, that heat could support district heating, desalination, or industrial processes. Higher-temperature coolants could potentially provide more valuable process heat, but increase material, chemistry, safety, and licensing demands. A plant placed far from heat customers cannot claim those benefits. **[Engineered cogeneration principle; fusion application projected]**

Fusion’s plausible early market is thus not automatically “every grid.” Regions with limited land or renewable resource, dense industrial demand, high firm-power costs, strong nuclear institutions, cooling access, and finance for large infrastructure could value it differently from regions with cheap renewables and transmission. This is a reason for regional scenario analysis rather than a globalized cost slogan. **[Projected]**

### 11.3 Climate relevance and deployment rate

Even a technically successful first plant has modest climate effect until it can be replicated. Climate relevance is the product of emissions avoided per plant, construction and commissioning time, supply-chain throughput, financing, siting, skilled workforce, and retirement or displacement of emitting assets. Fusion’s long development time makes near-term emissions reductions dependent on already-deployable technologies; its potential contribution is principally a later-century option if it reaches repeatable construction and high availability. **[Projected]**

## 12. Fusion for industry

High-temperature heat, electricity, and neutrons are distinct products. Steel, cement, chemicals, refining, ammonia, hydrogen, synthetic fuels, and desalination each need different temperatures, process integration, capital structure, and demand profiles. A fusion plant that makes electricity can support electrification; a higher-temperature reactor could in principle provide heat directly, but direct coupling ties industrial outages and plant outages together and raises interface complexity. **[Projected]**

### 12.1 Hydrogen, fuels, and chemicals

Low-carbon hydrogen can be produced by electrolysis using electricity, or by thermal/electrochemical pathways if suitable high-temperature heat is available. For synthetic fuels and ammonia, the cost of electricity or heat, electrolyzer utilization, carbon or nitrogen feedstock, and downstream plant utilization typically dominate the simple question of fuel source. Fusion would have to beat or complement renewables, storage-backed electrolysis, fission, geothermal heat, and grid power on delivered energy and uptime. **[Projected]**

### 12.2 Materials processing and desalination

Electric arc furnaces, resistance heating, induction, plasma torches, and heat pumps already provide electrification routes for many processes. Fusion may be valuable if it delivers dependable electricity or heat at a site where other clean supplies are constrained; it is not intrinsically required for industrial decarbonization. Desalination is especially location-sensitive: a coastal fusion plant could supply electricity and reject heat useful to thermal desalination, but water intake, brine discharge, cooling, and local water policy control viability. **[Projected]**

### 12.3 Direct neutron uses

D–T neutron sources can support materials testing, neutron imaging, isotope production, and certain semiconductor or advanced-material processes. These uses require much less energy multiplication and plant availability than grid electricity. They may therefore be earlier commercial niches for compact fusion-neutron devices if irradiation quality, reliability, cost, shielding, and regulation are demonstrated. This does not prove a power plant; it can nevertheless produce societal value and close data gaps for materials. **[Engineered to projected, application dependent]**

## 13. Fusion as a neutron source, safeguards, and hybrids

The 14 MeV neutron from D–T fusion can create damage conditions relevant to fusion materials and can induce nuclear reactions for scientific and industrial purposes. Neutron radiography can inspect dense objects; specialized sources can contribute to isotope production; irradiation can test steels, ceramics, and blanket candidates. Each application requires a target-specific safety case, dosimetry, product purity, radiochemical separation, and business model. **[Demonstrated neutron-science principle; project implementation varies]**

Fusion–fission hybrid concepts use fusion neutrons to drive a subcritical fission blanket, breed fissile material, transmute some isotopes, or produce energy. They may reduce the plasma-performance threshold relative to a pure fusion electricity plant, but introduce fission fuel, waste, safeguards, reprocessing, and criticality-related governance issues. A hybrid is not a simple bridge to “clean fusion”; it is a distinct nuclear system requiring its own full evaluation. **[Physics demonstrated; power-system concept projected]**

Safeguards attention is warranted where tritium, high-flux neutrons, lithium processing, or hybrid blankets can support sensitive nuclear activities. The proper policy response is proportionate transparency, material accounting, export controls where justified, and international verification—not assuming either that all fusion is proliferation-neutral or that civilian fusion work is equivalent to weapons activity. **[Policy conclusion]**

## 14. Fusion propulsion: physical foundations

### 14.1 Rocket equation and the power problem

The ideal rocket equation is

\[
\Delta v = v_e\ln\!\left(\frac{m_0}{m_f}\right)=g_0 I_{sp}\ln\!\left(\frac{m_0}{m_f}\right),
\]

where \(v_e\) is exhaust velocity, \(I_{sp}\) specific impulse, and \(m_0/m_f\) mass ratio. High exhaust velocity reduces propellant required for a given delta-v. It does not alone make a useful mission: thrust depends on exhaust mass flow and power. For an ideal kinetic exhaust, \(P\approx\tfrac12\dot m v_e^2\) and \(F=\dot m v_e\), so \(F\approx2P/v_e\). At fixed power, raising exhaust velocity lowers thrust. **[Demonstrated mechanics]**

This tradeoff explains why high-specific-impulse electric propulsion is excellent for low-thrust cargo and deep-space missions but cannot replace high-thrust launch vehicles. It also explains why a fusion spacecraft needs an extraordinary specific power: reactor mass, conversion equipment, propellant, shielding, structures, and radiators must be low enough that the engine’s delta-v advantage is not consumed by its own mass. **[Demonstrated mechanics; fusion-system implication projected]**

### 14.2 Heat rejection and radiation

In space, waste heat cannot be dumped into air or water. It must be radiated, with radiator area governed by temperature and emissivity. High-power systems therefore face a radiator-mass problem as well as a reactor-mass problem. D–T neutrons also complicate crew shielding, electronics, structural lifetime, and activation. A terrestrial D–T blanket can use mass and coolant volume that a spacecraft cannot afford. **[Demonstrated thermal physics; spacecraft integration projected]**

### 14.3 Why fusion is not launch propulsion

Earth launch rewards high thrust, reliability, low dry mass, simple operations, and abort options. Chemical rockets already provide these at high thrust, while fusion concepts require heavy, complex, radiation-producing hardware that has not operated in space. Fusion is therefore not a foreseeable replacement for chemical ascent or for near-term cislunar logistics. It could be relevant only after orbit, where long operating time and low propellant mass become more valuable. **[Projected judgment]**

## 15. Fusion propulsion concepts

### 15.1 Fusion thermal and fusion-electric propulsion

A fusion thermal rocket would use fusion energy to heat a propellant, commonly hydrogen, and expand it through a nozzle. It could offer specific impulse higher than chemical propulsion if a compact, controllable, lightweight reactor and heat exchanger existed. The reactor/heat-exchanger materials would face extreme temperatures and radiation, and no such flight engine has been demonstrated. **[Speculative system]**

Fusion-electric propulsion would convert fusion heat or charged-particle energy to electricity and run electric thrusters. It offers a more modular connection to mature electric-propulsion physics, but inherits conversion, radiator, and mass penalties. Its likely role, if achieved, would be high-energy cargo or robotic missions rather than impulsive crew maneuvers. **[Speculative system; electric-propulsion component physics demonstrated]**

### 15.2 Direct and pulsed concepts

Direct fusion drives seek to expel charged fusion products or heated plasma through a magnetic nozzle, reducing thermal conversion losses. Pulsed concepts seek a sequence of micro-explosions or magneto-inertial events coupled to a reaction chamber or pusher. In principle these can trade pulse energy, frequency, and exhaust velocity. In practice, they require unprecedented repetitive reaction control, coil/structure survival, pulsed-power mass, propellant coupling, and radiation management. **[Speculative]**

Antimatter-assisted fusion and fusion–fission propulsion are even more conditional. Antimatter can act as an ignition trigger in models, but production and storage are nowhere near mission-scale requirements. A fission hybrid can relax some fusion requirements but carries fission-specific mass, waste, safety, and policy burdens. **[Speculative]**

### 15.3 Propulsion comparison

| Propulsion family | Typical strength | Principal limit | Maturity for mission use |
|---|---|---|---|
| Chemical | High thrust, launch and landing | Low Isp, propellant mass | Operational |
| Nuclear thermal | Higher Isp, high thrust potential | Reactor qualification and politics | Engine tests historically; modern missions in development |
| Solar electric | Efficient, mature long-duration thrust | Solar-distance and low-thrust limits | Operational |
| Nuclear electric | High power independent of sunlight | Reactor/radiator mass | Projected for large missions |
| Fusion electric/thermal | Potentially very high power/Isp | No compact demonstrated fusion reactor | Speculative |
| Direct/pulsed fusion | Potentially favorable exhaust trade space | Repetitive reactor and mass problem | Speculative |
| Antimatter | Exceptional energy density | Production/storage infeasibility | Speculative |

## 16. Space mission analysis

Mission claims should begin with payload mass, delta-v, acceleration, power, mission duration, radiation environment, redundancy, and abort mode—not a desired trip time. A “rapid Mars” claim without these numbers is usually a propulsion aspiration, not an engineering design. A crew mission also needs life support, artificial- or microgravity countermeasures, radiation protection, communications, landing/ascent systems, and rescue strategy. **[Evidence-standard conclusion]**

| Mission class | Near-term credible choices | What fusion would need to add | Fusion evidence tier |
|---|---|---|---|
| Earth-to-orbit | Chemical launch | Nothing competitive on thrust/mass | Not credible near term |
| Cislunar cargo | Chemical, solar electric, potentially nuclear | Lower logistics mass at robust reliability | Speculative |
| Mars cargo | Solar electric, nuclear electric concepts | High specific power and long life | Speculative |
| Mars crew | Chemical/nuclear-thermal concepts under study | High thrust plus high Isp, shielding, abort | Speculative |
| Outer-planet cargo | Solar electric near Sun, RTG/nuclear concepts | Long-lived high-power propulsion | Speculative |
| Interstellar precursor | Solar sail, nuclear electric concepts | Orders-of-magnitude specific-power breakthrough | Speculative |

The outer solar system is where a hypothetical compact fusion plant could be most valuable because sunlight weakens and mission durations stretch. But the same low solar flux is not evidence that fusion becomes easy: reliability and repairability become harsher, radiators work against a cold background but still require area, and communication delays preclude routine intervention. **[Projected]**

## 17. Fusion beyond propulsion

Fusion might eventually provide compact space-based power for habitats, scientific stations, or resource-processing sites. In the nearer term, solar power, batteries, fuel cells, radioisotope systems, and fission concepts have far stronger evidence bases. Moon or asteroid resource use does not change this hierarchy until there is an economically operating extraterrestrial industrial base. **[Projected]**

Helium-3 extraction narratives are a particularly useful reality check. Even if a lunar process could recover helium-3, it would need energy, machines, labor or autonomy, transport, and a reactor that benefits from the fuel. The demand side is not established because D–\(^3\)He reactors are not established. Resource claims should therefore be evaluated as coupled infrastructure scenarios rather than a concentration estimate multiplied by lunar area. **[Speculative economic system]**

Science fiction often uses fusion as a compact, silent, unlimited engine. Physics permits impressive energy density, but engineering demands a credible power density, heat sink, radiator, neutron shielding, fuel cycle, maintenance plan, and failure mode. A story can choose a breakthrough; an analysis must name it. **[Methodological conclusion]**

## 18. Geopolitics, ethics, and societal consequences

If fusion becomes deployable, it could expand the portfolio of firm low-carbon energy and reduce exposure to fossil-fuel price shocks. It would not make energy free: capital, labor, materials, land, cooling, regulation, grids, and institutions remain scarce. A technology that is expensive and technically complex may initially concentrate in states and firms with advanced manufacturing and financing, creating a distributional question alongside any abundance benefit. **[Projected]**

Supply chains deserve early scrutiny. High-grade copper, specialty steels, superconducting tape, lithium-bearing materials, beryllium or alternative blanket materials, high-power semiconductors, lasers, precision vacuum systems, and nuclear-qualified fabrication can all concentrate power. Responsible deployment would include worker protections, environmental oversight for mining and processing, open safety evidence, workforce development, and consultation with host communities. **[Projected governance priorities]**

Military implications are real but should be stated precisely. Fusion research includes high-energy-density science, tritium handling, neutron sources, pulsed power, and advanced materials with possible dual-use aspects. Civilian benefits and international cooperation are valuable; they do not remove the need for safeguards, export-control discipline, and institutions that distinguish peaceful research from sensitive applications. **[Policy conclusion]**

## 19. Future scenarios and decision signals

The decisive decade is less about whether another plasma record is set than whether integrated constraints close together. Evidence that would materially strengthen the case for commercial D–T fusion includes: long-duration burning-plasma control; validated divertor and first-wall performance in relevant neutron/heat environments; credible blanket tests with measured tritium recovery; maintainable component architecture; high-efficiency heating/magnet systems; and independently auditable availability and cost data. **[Projected decision framework]**

Conversely, repeated inability to protect materials, achieve tritium margin, control disruptions/exhaust, or complete maintenance quickly would not mean fusion reactions are impossible; it would mean electricity economics are unlikely on the proposed pathway. A field that responds to such results by moving dates without updating assumptions is not doing useful forecasting. **[Evidence-standard conclusion]**

The no-commercial-fusion scenario remains possible and should remain in planning cases. It does not invalidate plasma science, neutron applications, or the value of research. The niche-fusion scenario is arguably the most defensible medium-term planning case: specialized facilities may create value before bulk power. Broad late-century deployment requires a sequence of successful prototypes, factories, regulatory precedents, and customers—not one successful scientific experiment. **[Projected]**

## 20. Conclusion

The strongest case for fusion is that the underlying physics is real, fuel energy density is extraordinary, D–T reactions are relatively accessible by fusion standards, and the world may value another form of dependable low-carbon energy. The strongest skeptical case is equally concrete: useful plasma performance has not yet been integrated with tritium self-sufficiency, neutron-tolerant materials, high heat-flux exhaust, maintainability, availability, and financeable construction.

The balanced judgment is neither “fusion is solved” nor “fusion is forever impossible.” Fusion is a portfolio of demanding technologies whose prospects vary by application. D–T magnetic fusion is the leading prospective route for terrestrial power; inertial ignition is a major scientific accomplishment with a large engineering gap; alternative concepts should be judged by clear, independently verifiable energy and lifetime evidence; and fusion spacecraft remain mainly research concepts. This is reason to sustain rigorous research, publish accounting boundaries, build materials and fuel-cycle test capability, and avoid using headline results as substitutes for systems engineering.

---

# Appendix A. Mathematical notes

## A.1 From reaction rate to fusion power density

For two distinct Maxwellian species, reaction rate per volume is

\[
R = n_1n_2\langle\sigma v\rangle.
\]

For an equimolar D–T plasma of electron density approximately equal to ion density \(n\), \(n_D\approx n_T\approx n/2\), so \(P_f\approx n^2\langle\sigma v\rangle E_f/4\). The alpha-heating fraction is \(3.5/17.6\approx0.20\), before losses and escape. A reactor calculation must add radiation, transport, dilution, alpha confinement, profile effects, and engineering geometry; this simple expression is a scaling relation, not a plant model. **[Demonstrated derivation]**

## A.2 Lawson-style energy balance

In an idealized D–T thermal plasma, alpha heating must at least balance energy losses. With thermal energy density proportional to \(nT\) and loss power density approximately energy density divided by \(\tau_E\), the ignition condition takes the form

\[
n\tau_E \gtrsim \frac{\text{thermal energy per particle}}{\langle\sigma v\rangle E_{\alpha}}.
\]

Multiplying by temperature gives the triple product. The optimum temperature is not selected from this equation alone because confinement, radiation, beta, current drive, impurities, and material loads change with operating point. **[Demonstrated framework]**

## A.3 Rocket equation example

Suppose a mission needs \(\Delta v=10\,\mathrm{km/s}\). At \(I_{sp}=450\,\mathrm{s}\), ideal mass ratio is \(\exp(10000/(9.81\times450))\approx9.6\). At \(I_{sp}=3,000\,\mathrm{s}\), it is about 1.4. The latter looks transformative, but the high-Isp engine must still deliver mission-appropriate thrust and fit in the dry-mass budget. This is why specific power, rather than Isp alone, governs fusion-propulsion credibility. **[Demonstrated arithmetic]**

# Appendix B. Claim ledger (selected)

| Claim | Tier | Key assumptions / counterargument | Sources |
|---|---|---|---|
| D–T releases 17.6 MeV | Demonstrated | Nuclear data are well established | [9, 10] |
| NIF achieved target-level gain/ignition regime | Demonstrated | Does not include facility wall-plug electricity | [1, 2] |
| ITER Q=10 is a design goal | Projected | Schedule and integrated performance remain uncertain | [3, 4] |
| D–T plants need tritium breeding margin | Projected requirement | Exact required margin depends on inventory and losses | [5, 14] |
| W7-X advanced optimized stellarator operation | Demonstrated | Not a power-plant test | [15] |
| Grid fusion by mid-century | Projected | Depends on materials, TBR, maintenance, finance | [4–8] |
| Fusion propulsion enables rapid crewed Mars missions | Speculative | Requires unprecedented specific power and shielding | [17, 18] |

# Appendix C. Glossary

**Activation:** creation of radioactive isotopes when materials absorb nuclear particles.  
**Alpha particle:** a helium-4 nucleus; the charged D–T fusion product.  
**Beta (\(\beta\)):** plasma pressure divided by magnetic pressure.  
**Blanket:** material surrounding a fusion chamber that absorbs neutrons, transfers heat, shields components, and may breed tritium.  
**Bremsstrahlung:** radiation emitted when charged particles are accelerated, especially in collisions.  
**Burning plasma:** a plasma in which fusion-produced alpha heating materially affects the energy balance.  
**Divertor:** a specially designed plasma-facing region that exhausts heat, particles, and impurities.  
**First wall:** the innermost structural surface facing the plasma.  
**Gain (Q):** a ratio whose meaning depends on its explicitly stated energy boundary.  
**ICF:** inertial-confinement fusion, using rapid compression and inertia for brief confinement.  
**Lawson criterion:** required combination of density, temperature, and confinement for useful fusion self-heating.  
**Plasma:** ionized matter with collective electromagnetic behavior.  
**TBR:** tritium breeding ratio, tritium produced divided by tritium consumed in a defined system boundary.  
**Tokamak:** toroidal magnetic-confinement device using a plasma current.  
**Triple product:** \(nT\tau_E\), a compact plasma-performance measure.  

# Appendix D. Myth versus fact

| Myth | Fact |
|---|---|
| “Fusion has already produced unlimited net energy.” | Some experiments have demonstrated target or plasma gain; no plant has demonstrated net grid electricity. |
| “Fusion has no radioactive waste.” | D–T fusion produces neutrons that activate materials and uses radioactive tritium. |
| “Seawater solves the fuel problem.” | Deuterium is abundant; tritium supply and breeding are central constraints. |
| “Higher magnetic field solves fusion.” | It can improve a design point while making stress, shielding, joints, and maintenance harder. |
| “A fusion reaction proves a fusion power plant.” | A power plant also requires fuel cycle, materials, conversion, maintenance, availability, licensing, and cost. |
| “Aneutronic means radiation-free.” | Advanced fuels reduce some primary neutron production but introduce demanding plasma and radiation problems. |
| “Fusion will replace rockets.” | High-Isp concepts still need high thrust, specific power, radiators, shielding, and flight-proven reactors. |

# Appendix E. Annotated bibliography and primary-source guide

1. **Lawrence Livermore National Laboratory / National Ignition Facility.** *Achieving fusion ignition* and related experimental reporting. Official account of target-level inertial-fusion results and their scientific boundary. https://lasers.llnl.gov/  
2. Zylstra, A. B., et al. “Burning plasma achieved in inertial fusion.” *Nature* 601 (2022): 542–548. Primary peer-reviewed evidence on alpha-heating/burning-plasma physics. https://doi.org/10.1038/s41586-021-04281-w  
3. **ITER Organization.** *ITER: the way to new energy* and project technical material. Design goals, machine architecture, and mission; not evidence of achieved gain. https://www.iter.org/  
4. **International Atomic Energy Agency.** *Fusion* topic portal and *World Fusion Outlook 2025*. Broad international program and regulatory context. https://www.iaea.org/topics/fusion  
5. Abdou, M. A., et al. “Blanket/tritium breeding requirements and the challenges.” *Fusion Engineering and Design* 54 (2001): 181–247. Foundational analysis of fuel-cycle constraints. https://doi.org/10.1016/S0920-3796(00)00354-8  
6. **EUROfusion.** *European Research Roadmap to the Realisation of Fusion Energy* (2018 update and successor material). System-level R&D gaps for DEMO. https://euro-fusion.org/  
7. **IAEA.** *Decommissioning and Waste Management Considerations for Fusion Facilities* (2026). Contemporary regulatory and waste framing. https://www.iaea.org/publications  
8. **U.S. Department of Energy.** *Fusion Energy Strategy* and Fusion Energy Sciences program materials. Public roadmap and funding context; schedule targets remain projections. https://www.energy.gov/science/fes/fusion-energy-sciences  
9. **IAEA Nuclear Data Services.** Evaluated nuclear-data resources for reaction energies and cross-sections. https://www-nds.iaea.org/  
10. Bosch, H.-S., and G. M. Hale. “Improved formulas for fusion cross-sections and thermal reactivities.” *Nuclear Fusion* 32 (1992): 611. Standard reactivity reference. https://doi.org/10.1088/0029-5515/32/4/I07  
11. Rider, T. H. “Fundamental limitations on plasma fusion systems not in thermodynamic equilibrium.” *Physics of Plasmas* 2 (1995): 1853. Important caution for advanced/aneutronic fuel claims. https://doi.org/10.1063/1.871273  
12. Wesson, J., and D. J. Campbell. *Tokamaks*, 4th ed. Oxford University Press, 2011. Comprehensive magnetic-fusion reference.  
13. Lawson, J. D. “Some criteria for a power producing thermonuclear reactor.” *Proceedings of the Physical Society B* 70 (1957): 6–10. Original confinement criterion. https://doi.org/10.1088/0370-1301/70/1/303  
14. **IAEA.** Tritium management and fusion safety publications. Primary institutional material on accounting and containment. https://www.iaea.org/  
15. **Max Planck Institute for Plasma Physics.** Wendelstein 7-X program and peer-reviewed publications. Evidence for optimized stellarator research, not commercial operation. https://www.ipp.mpg.de/w7x  
16. **IAEA.** *International Experience in the Regulation of Fusion Facilities* (2025). Current regulatory comparison. https://www.iaea.org/publications  
17. Frisbee, R. H. “Advanced space propulsion for the 21st century.” *Journal of Propulsion and Power* 19 (2003): 1129–1154. A technical survey of future propulsion concepts. https://doi.org/10.2514/2.6942  
18. **NASA.** Nuclear propulsion and space-technology program material. Useful for contrast with more mature nuclear-thermal and nuclear-electric concepts. https://www.nasa.gov/  

**Citation note.** Web sources were checked on 26 August 2026. Facility schedule, company milestones, and policy details change; readers should treat dated official reporting as a snapshot and distinguish it from independently reviewed experimental literature.

# Appendix F. Reactor and fuel-cycle comparison tables

## F.1 Confinement-family comparison

| Family | Confinement mechanism | Principal demonstrated strength | Critical unresolved plant issue | Appropriate claim boundary |
|---|---|---|---|---|
| Conventional tokamak | Toroidal field plus plasma current | Best-established high-performance D–T magnetic-fusion database | Disruptions, exhaust, steady state, maintenance | A strong experimental basis, not a commercial plant |
| Optimized stellarator | Externally shaped 3-D fields | Steady-state-oriented operation and improved confinement | Coil complexity, blanket integration, cost | Promising alternative magnetic pathway |
| Spherical tokamak | Low-aspect-ratio tokamak fields | High beta and compact plasma geometry | Center-stack shielding and component access | Compact-core hypothesis, not cost proof |
| ICF laser | Inertial confinement through rapid implosion | Ignition-related target physics | Driver efficiency, repetition, targets, chamber | Target gain is not facility gain |
| Magnetized target | Magnetic insulation plus compression | Potentially relaxed intermediate regime | Repetitive driver/chamber integration | Research architecture, not yet plant evidence |
| FRC/compact toroid | Self-organized compact plasma | High-beta, compact-plasma research | Lifetime, heating, particle losses, scale-up | Concept-dependent; examine disclosed diagnostics |
| Z-pinch | Self-magnetic compression by current | Very high-energy-density pulses | Stability and repetitive hardware | Pulsed neutron/physics evidence only unless more is shown |

## F.2 Fuel-cycle implications

| Property | D–T | D–D | D–\(^3\)He | p–B11 |
|---|---|---|---|---|
| Reactivity at accessible fusion temperatures | Best | Lower | Lower and hotter | Much lower/hotter |
| Dominant useful product | Neutron energy + alpha heating | Mixed branches | Charged products | Charged products |
| Neutron/material burden | Severe | Significant | Reduced but not zero | Reduced primary, not zero in practice |
| Fuel-supply issue | Tritium breeding/startup inventory | Performance and tritium branch | Helium-3 availability | Boron supply not decisive; plasma physics is |
| Credible terrestrial first-power candidate | Yes, conditional | No | No | No |
| Evidence classification for reactor | Projected | Speculative | Speculative | Speculative |

## F.3 Thermal conversion and parasitic-load checklist

An honest plant energy balance should show, preferably as a Sankey diagram or numerical table, all of the following boundaries: fusion power; blanket heat recovered; gross turbine output; magnet cryogenic power; plasma heating and current drive; pumps and coolant systems; vacuum; tritium processing; control/diagnostics; site loads; availability loss; and annual exported electricity. Omitting an input is often more consequential than improving a headline \(Q\) value. **[Accounting rule]**

| Item often left implicit | Why it matters |
|---|---|
| Wall-plug-to-plasma heating efficiency | A high \(Q_{plasma}\) may still correspond to large facility power draw. |
| Cryogenic load and magnet protection | Superconducting magnets save resistive power but require refrigeration and reliability systems. |
| Current-drive power | Essential to many steady-state tokamak projections. |
| Blanket/primary-coolant temperature | Sets conversion efficiency and materials constraints. |
| Replacement outage duration | Directly determines annual energy sold. |
| Tritium inventory and processing delay | Determines whether a D–T plant can refuel itself. |

# Appendix G. Dated facility and milestone scorecard

This scorecard intentionally avoids giving a single “leaderboard” ranking. Facilities have different purposes; only evidence at the stated boundary is scored.

| Program/facility | Main role | What is independently established | What remains unestablished for a plant | Tier for commercial-power implication |
|---|---|---|---|---|
| JET (legacy) | D–T tokamak research | Important D–T operation and fusion-energy records | Breeding blanket, plant availability, electricity export | Demonstrated science; projected plant relevance |
| ITER | Burning-plasma experiment | Large international machine and technology program under construction | Its principal performance goals, routine D–T operation, power plant integration | Projected |
| JT-60SA | Superconducting tokamak research | Advanced operating platform | D–T power-plant fuel and material environment | Demonstrated facility; projected plant relevance |
| Wendelstein 7-X | Optimized stellarator research | Long-pulse and confinement advances | D–T reactor blanket, neutron environment, cost | Demonstrated research; projected reactor |
| NIF | High-energy-density/ICF research | Target-level ignition-related experiments | Efficient repetition, low-cost targets, electrical plant | Demonstrated target result; projected plant |
| DEMO/STEP/CFETR concepts | Prototype power-plant planning | Designs, programs, and R&D agendas | Construction, integrated performance, economics | Projected |
| Private pilot proposals | Diverse | Varies; assess each published result separately | Independent full-boundary net power and lifecycle evidence | Usually projected |

### G.1 Milestone language guide

*“First plasma”* establishes that a machine can form plasma, not that it can reach reactor temperature or useful gain. *“High temperature”* needs density and confinement context. *“Net energy”* requires a named boundary. *“Pilot plant”* may mean a planned demonstration rather than an operating power plant. *“Commercial by [year]”* is a forecast and must name its engineering dependencies. These distinctions are not rhetorical cautions: they are the minimum vocabulary for comparing results fairly.

# Appendix H. Private-company evaluation protocol

No private organization should be judged merely by whether it is public or private. The same protocol should apply to public programs, universities, and companies.

1. **State the physical claim.** Is the claim temperature, neutron production, confinement, a plasma triple product, target gain, thermal output, or exported electricity?
2. **State the meter boundary.** What inputs are included: stored electrical energy, wall-plug power, laser power, magnetic energy, cryogenics, facility loads, and target manufacture?
3. **Demand repeatability.** How many shots or discharges were measured, under what conditions, with what uncertainty and independent diagnostics?
4. **Separate core from plant.** Which claims address tritium, blanket, neutron lifetime, divertor/exhaust, magnets, remote maintenance, and availability?
5. **Interrogate the schedule.** Which remaining elements are extensions of demonstrated hardware, and which rely on a new material, manufacturing process, or physical regime?
6. **Examine financing assumptions.** What capacity factor, replacement interval, construction duration, and weighted cost of capital are necessary for the business case?

This protocol is demanding because the historical record includes genuine progress accompanied by overbroad framing. It rewards a company that says “we have demonstrated X; Y and Z remain engineering risk” more than one that uses a laboratory measurement as evidence that every downstream requirement is solved.

# Appendix I. Lifecycle and waste comparison framework

| Dimension | Fusion (prospective D–T) | Fission | Gas with carbon capture | Wind/solar | Geothermal |
|---|---|---|---|---|---|
| Operational carbon emissions | Potentially very low | Low | Lower than unabated gas but site-dependent | Very low | Low to very low, site-dependent |
| Primary waste issue | Activated components; tritium | Spent fuel and activated waste | CO2 capture/storage and upstream methane | Materials/recycling/end-of-life | Brines, drilling, site impacts |
| Fuel-cycle central risk | Tritium self-sufficiency | Fuel supply, waste, safeguards | Storage permanence and capture rate | Mineral supply and integration | Resource characterization |
| Dispatchability | Projected firm/thermal | Demonstrated firm | Demonstrated firm | Variable; needs integration | Demonstrated where resource exists |
| Technology maturity | Research/prototype | Commercial | Commercial/developing CCS | Commercial | Commercial in suitable regions |

This table is a comparison framework, not a lifecycle assessment. An actual comparison requires defined plant size, location, construction materials, capacity factor, cooling system, grid displacement, waste route, time horizon, and emissions-accounting method. It is misleading to compare a mature technology’s realized costs with a conceptual fusion plant’s idealized physics-only result.

# Appendix J. Research and policy agenda

## J.1 Highest-value technical evidence

The following work most directly reduces uncertainty across designs:

- Materials irradiation campaigns that approximate fusion-relevant spectra, temperatures, and fluence, followed by mechanical and thermal-property measurement.
- Blanket experiments that report tritium generation, extraction, inventory, losses, and measurement uncertainty at an integrated scale.
- Divertor and first-wall experiments that report cumulative damage and repairability, not only short peak-load records.
- Long-duration operation with quantified availability, component failure modes, and remote-maintenance time.
- End-to-end energy accounting for both magnetic and inertial pathways.
- Independent validation datasets for models that connect experimental plasma performance to plant-scale projections.

## J.2 Responsible public policy

Public support is defensible when it funds shared data, test facilities, workforce development, safety research, materials qualification, and transparent demonstrations that private incentives may underprovide. It should not require exaggerated deployment promises. Regulators should establish proportionate but rigorous frameworks for tritium, activated materials, radiation protection, quality assurance, emergency planning, and decommissioning. International cooperation should retain strong safeguards and appropriate controls on sensitive technology.

## J.3 Decision rule for public investment

The right question is not “Is fusion guaranteed?” Nearly all consequential R&D is uncertain. The useful question is whether the expected learning value and upside justify the research cost relative to alternatives, while near-term decarbonization relies on options ready to deploy. This supports a diversified strategy: fund fusion as a long-horizon option, but do not defer emissions reductions on the premise that fusion will arrive on a particular date. **[Policy judgment]**
