---
title: |
  Climate-Triggered Global Cascades:\
  Pathways to a Billion-Death Year: Modeling Climate-Triggered Global Cascades
author: PIATRA . INSTITUTE
date: August 2026
---

## Abstract

No existing model supports a defensible probability that anthropogenic climate change will cause 1 billion excess deaths within a rolling year, because no model class links forcing to unique deaths across coupled human systems. We specify 1177-G, a stochastic hybrid causal model of climate-triggered failure across crop, food, trade, energy, water, finance, governance, conflict, health, and displacement networks. The outcome is the maximum 365-day sum of excess mortality, with each death assigned once through competing hazards; summing sectoral estimates would double-count. Buffer depletion, recovery time, behavioral response, and state capacity determine whether shocks dissipate or compound. A state-dependent cascade matrix measures amplification between layer-region failures, and minimal cut sets identify the combinations capable of crossing the threshold, which corresponds to 12.2% of the 2024 world population, or about 3.34 excess deaths per 10,000 people per day sustained for a year. The design combines module-level calibration, validation against cases in which large shocks were absorbed, rare-event sampling, and paired factual and counterfactual climate ensembles. Existing crop, network, famine, and nuclear-winter studies constrain individual modules and cannot validate the global tail. A simulated billion-death year would be a conditional model result, and we state the tests under which such a result should be rejected as evidence about climate risk.

## Introduction

A death toll of 1 billion in 365 days can first be stated in demographic terms. The United Nations estimated a world population of 8.2 billion in 2024 [@undesa2024]. Against that reference population, the threshold is about 12.2%. It is close to the 10% mortality anchor used in one recent framework for global catastrophic risk [@arnscheidt2025]. Crossing it would require a disturbance operating across regions and causes of death at a scale outside the range of modern climate-impact observations.

No published climate model assigns a defensible probability to that event. @kemp2022 argue that catastrophic climate scenarios remain underexplored and call for research on mass mortality, systemic vulnerability, and social fragility. Their paper sets a research agenda and supplies no estimate. Sectoral studies quantify heat exposure, crop response, flooding, disease suitability, economic loss, or conflict-related risks under defined assumptions. Their outcomes have different baselines, horizons, and populations. Adding their upper bounds would double-count people and erase causal dependence.

The evidence does support a narrower premise. Climate risks can be compound, cascading, and transmitted through connected human systems. The IPCC assesses complex compound and cascading risks with high confidence and describes transmission through food, trade, finance, and ecosystems [@ipcc2022]. Simultaneous crop-loss risk rises with warming. A drought in several exporting regions can alter prices and reserves elsewhere; the response of importing states can then change the shock faced by their neighbors.

A billion-death year would almost certainly require this kind of amplification. Direct heat, flood, fire, and storm mortality would remain inside the causal chain, but the principal scientifically constructible route runs through failures of access and response in which crop losses interact with trade restrictions or financing constraints, energy and water interruptions impair health systems, conflict blocks relief, malnutrition changes susceptibility to infection, and displacement redistributes exposure while degrading records and care.

That the route can be constructed says nothing about its probability. It defines what a model must do: represent the systems that separate a physical hazard from death, and allow those systems to work. Grain stocks, substitution, imports, fiscal transfers, public health, migration, and international assistance prevent many shocks from becoming famines. A catastrophe model calibrated only on failure would confuse omission of resilience with evidence of collapse.

1177-G states these requirements in executable terms. The name refers to a historical systems-collapse analogy, and the suffix marks a global model. We specify the model without implementing it; a credible implementation would be a multi-institution program with restricted microdata, sectoral simulators, historical reconstruction, and repeated external review. We supply the causal specification, the validation sequence, and the conditions under which a claimed result should be rejected.

## Constraints from existing models

Agricultural studies provide forcing distributions; mortality functions lie downstream. @gaupp2020 estimate changing risks of simultaneous failure across major breadbaskets. @kornhuber2023 find that climate and crop-model ensembles can underestimate synchronized low yields associated with large-scale atmospheric circulation. A model that draws national yield shocks independently would therefore suppress an important tail mechanism.

@hultgren2025 estimate climate effects across 12,658 regions and six staple crops while accounting for observed adaptation, with an aggregate response corresponding to an annual loss of about $5.5\times10^{14}$ kilocalories for each degree of warming, which the authors express as around 120 kilocalories per person per day at the global scale. This production result cannot be converted directly into deaths because food reaches people through stocks, feed use, processing, prices, incomes, public distribution, and household allocation.

Model spread remains consequential even at moderate mean warming. @bevacqua2026 show that some modeled extreme outcomes at $2\,^{\circ}\mathrm{C}$ exceed multimodel-average outcomes at $4\,^{\circ}\mathrm{C}$ for selected metrics, including a breadbasket-drought measure. Their result calls for structural ensembles and plausibility checks, and gives no grounds for treating the most destructive model member as the representative future.

Trade models constrain another link. @puma2015 document evolving concentration and dependency in the international food-trade network. @kuhla2024 combine a wheat supply network with a market model to reconstruct the 2022 shock following Russia's invasion of Ukraine. Their counterfactuals show how production failures and escalating export restrictions can compound. They also show that favorable harvests and international cooperation reduced the realized price shock. Behavior is an amplifier in some draws and a buffer in others.

The most dramatic integrated food-shock model comes from a different hazard. @xia2022 couple nuclear-war soot scenarios to climate, crop, fishery, livestock, and national food-availability calculations. Under their specified scenarios and behavioral assumptions, estimated deaths exceed 2 billion for one regional-war case and 5 billion for a United States-Russia war. The study demonstrates that a globally coherent food shock can produce billion-scale modeled mortality. Greenhouse warming is slower, spatially different, and governed by different physics, so the mortality estimates do not transfer. The model architecture can still be examined for missing modules, allocation rules, adaptation assumptions, and uncertainty propagation.

Interdependent-network theory supplies a further component. @buldyrev2010 show that dependencies between networks can create recursive and abrupt failure absent from isolated-network analysis. @boccaletti2014 distinguish multiplex and interdependent structures and review their dynamics. These mathematical results establish possibilities under stylized rules. A percolation threshold derived for paired infrastructure networks is not an empirical collapse threshold for countries.

The literature thus constrains pieces of a global cascade. It does not close the chain from anthropogenic forcing to overlapping hazards, behavioral responses, institutional failure, and unique deaths within a rolling year.

## The Late Bronze Age analogy

The collapse of Late Bronze Age palace societies offers a vocabulary of interaction. @cline2021 describes drought, earthquake, conflict, migration, and the failure of interconnected political economies around the eastern Mediterranean. The historical record does not isolate a single sufficient cause. The episode is therefore a case of multicausal collapse.

@linkov2024 formalize parts of the case as interacting trade and sociopolitical networks. In their model, isolated disruption of a single node does not reproduce system collapse, while some paired disruptions generate cascades. The interaction result transfers to modern systems; the estimated parameters do not.

Modern systems differ in scale, speed, state capacity, technology, reserve depth, and destructive potential: container shipping and global finance can reroute supply across great distances while transmitting price shocks within days; vaccines, telecommunications, and international relief add resilience; and grid dependence, just-in-time logistics, cyber systems, and nuclear arsenals add failure modes without Bronze Age counterparts. A modern model must represent these mechanisms directly.

The analogy should therefore guide questions about timing and overlap. Did a second shock arrive before the system recovered from the first? Which dependencies turned a local loss into a regional one? Which buffers failed, and which institutions restored them? It supplies no coefficients. The name 1177-G refers to collapse as a sequence of coupled losses and implies no numerical similarity to the Bronze Age case.

## Model state and time steps

1177-G is a stochastic hybrid structural-causal model on a temporal multilayer network. Its main nodes are countries or operationally distinct subnational regions. Climate and crop forcing begin on a finer spatial grid and are aggregated through production areas, watersheds, grids, ports, and population exposure. The core transition step is monthly. Heat, epidemic, armed-conflict, grid, and transport modules can run at daily or weekly steps and pass aggregates to the monthly state.

For region $i$, define

$$
x_i(t)=\left(
Q_i,S_i,K_i,E_i,W_i,L_i,F_i,G_i,C_i,H_i,M_i,N_i
\right)_t.
$$

$Q$ is food production, $S$ stocks, and $K$ accessible dietary energy. $E$ and $W$ are usable energy and safe water. $L$ represents logistics. $F$ records fiscal and external-financing capacity. $G$ is effective government capacity, $C$ conflict intensity, $H$ health-system function, $M$ migration and displacement, and $N$ the population by age and vulnerability class. Each symbol is a vector in an implementation. Collapsing food or government into one scalar would hide essential substitutions.

The global state evolves as

$$
x(t+\Delta t)=
\mathcal{F}\!\left[x(t),z(t),u(t);\theta\right]+\varepsilon(t),
$$

where $z(t)$ contains exogenous and climate-forced hazards, $u(t)$ contains policy and behavioral actions, $\theta$ contains estimated parameters, and $\varepsilon(t)$ contains process error. Some transitions are continuous, such as depletion of a reserve, and others are discrete, such as port closure, export prohibition, government loss of territorial access, or emergency foreign assistance, which is why the model is hybrid.

The layer set is

$$
\mathcal{L}=\{\text{climate, crops, food, energy, water, logistics,
finance, governance, conflict, health, population, response}\}.
$$

Links within and between layers change over time because a country may import grain from one partner, fertilizer from another, and fuel from a third while its port depends on a regional grid, and a displaced population changes the denominator and vulnerability distribution in both origin and destination regions. Static centrality cannot capture those changes.

The model should preserve causal ordering. Anthropogenic forcing changes distributions of physical hazards. Those hazards affect production, infrastructure, and exposure. Public and private actors respond on the information available to them. The responses alter later hazards and access. Mortality follows individual or cohort exposure histories. Feedback returns through labor loss, fiscal pressure, political legitimacy, and displacement.

## Buffers and recovery

Cascades occur when losses outrun replenishment across linked buffers. For buffer type $\ell$ in region $i$,

$$
B_{i\ell}(t+1)=B_{i\ell}(t)
+R_{i\ell}(t)-L_{i\ell}(t),
$$

where $R$ is replenishment or repair and $L$ is use, damage, diversion, or decay. The usable buffer may include a safety floor $b_{i\ell}^{\min}$. Service failure begins when $B_{i\ell}<b_{i\ell}^{\min}$, but the relationship need not be a step function. Hospitals can degrade as backup fuel is rationed before it is exhausted.

Recovery time is as important as shock magnitude. Let $\tau_{i\ell}^{R}$ be the stochastic time required to restore a buffer after disruption. A second loss at $t+s$ compounds with the first when $s<\tau_{i\ell}^{R}$ or when repair in one layer requires a service still unavailable in another. Drought can draw down hydropower and irrigation together. A fiscal shock can delay both imports and grid repair. A disease outbreak can reduce the labor available for harvest and transport.

This representation makes resilience observable. Regions with similar initial shocks can diverge because reserve release, credit, mutual aid, substitution, or repair rates differ. Parameters can be estimated from ordinary disruptions and severe crises. The model should also reproduce cases in which large shocks were absorbed. A parameter set that turns every overlap into collapse has failed before any tail simulation begins.

Buffers have ownership and access rules, so national grain stocks may exist while households cannot afford food, a private generator may serve a data center while the municipal water system remains dark, and foreign exchange may be sufficient in aggregate while unavailable to importers under sanctions or banking interruption. Physical availability and effective access must be separate states.

## Food, trade, and export restrictions

Crop production begins with gridded yield responses and harvested area. A regional reduced form is

$$
Q_{ic}(t)=A_{ic}(t)\,
Y_{ic}\!\left[T_i(t),P_i(t),Z_i(t),a_i(t);\theta_c\right],
$$

where $c$ indexes crops, $T$ and $P$ represent temperature and moisture conditions, $Z$ includes other agronomic shocks, and $a_i$ represents adaptation. The joint distribution must preserve teleconnections and common model error. @kornhuber2023 make independent national sampling indefensible for the tail.

Stocks then obey a material balance:

$$
S_{ic}(t+1)=S_{ic}(t)+Q_{ic}(t)+I_{ic}(t)
-X_{ic}(t)-D_{ic}(t)-\delta_c S_{ic}(t),
$$

with imports $I$, exports $X$, domestic use $D$, and loss rate $\delta_c$. Domestic use is divided among direct food, feed, seed, processing, waste, and emergency allocation. Substitution changes nutritional quality as well as calories.

Accessible dietary energy is distinct from supply:

$$
K_i(t)=\frac{\mathcal{C}_i(t)}{N_i(t)}
\,a_i^{p}(t)\,a_i^{d}(t)\,a_i^{h}(t),
$$

where $\mathcal{C}_i$ is available food energy and the access terms represent purchasing power, physical distribution, and household allocation. Each term lies between zero and one. Cash transfers can raise purchasing access when food is present. They cannot create supply after markets have emptied. Rationing can improve distributional access even while average consumption falls.

Exports are endogenous. Let $r_i(t)$ denote reserve adequacy, $p(t)$ the world price, $g_i(t)$ domestic political stress, and $c_i(t)$ coordination commitments. The probability of a restriction can be modeled as

$$
\Pr(R_i^{X}=1)=
\sigma\left(\alpha_0-\alpha_r r_i+\alpha_p p+\alpha_g g_i-\alpha_c c_i\right).
$$

The form must be estimated from historical episodes and allowed to vary by regime and commodity, because a fixed assumption of open trade or universal export bans would miss the pattern documented by @{kuhla2024}: restrictions can protect domestic consumers in one region while transferring scarcity to import-dependent regions, and coordination can reverse that amplification.

Finance enters through import capacity, exchange rates, sovereign borrowing, household income, and payment infrastructure. A food deficit causes mortality only after these access channels and relief responses are represented. At this stage the biophysical crop model becomes a political-economy model.

## Government, conflict, and displacement

Governance should enter as a set of functions: revenue collection, information, territorial access, logistics, public-health delivery, and legitimate coordination. Conflict is also disaggregated by intensity, location, infrastructure targeting, and interference with relief. A single failed-state indicator would impose the outcome it is meant to explain.

Transitions can be represented as hazards that preserve differences among slow vulnerability, current stress, and the institutions capable of interrupting a deterioration. For a governance failure mode $j$,

$$
\lambda_{ij}^{G}(t)=
\lambda_{0j}\exp\left[
\beta_j^{\top}v_i(t)+\gamma_j^{\top}s_i(t)
\right],
$$

where $v_i$ contains slowly changing vulnerability and $s_i$ contains current stress, including price shocks, displacement, fiscal loss, and conflict. The equation is probabilistic because climate stress does not determine political breakdown, and institutions, external support, leadership, or chance can interrupt the path at several points.

Conflict feeds back through casualties, destroyed capital, blocked trade, and coerced movement. Displacement changes exposure. It can move people away from acute physical danger while increasing crowding, water insecurity, and loss of care. Population accounting must conserve people across origin, transit, and destination states, subject to recorded deaths and measurement error.

The IPCC's assessment of transmitted and cascading risks justifies inclusion of these pathways [@ipcc2022]. It does not supply universal coefficients. Those must come from domain-specific evidence, with sensitivity ranges wide enough to reflect contested causal estimates.

## Mortality accounting

The outcome is excess all-cause mortality. Let cohort $j$ in region $i$ face cause-specific hazards for direct climate exposure, trauma, infection, nutritional impairment, interrupted medical care, and other causes. The all-cause hazard is

$$
h_{ij}(t)=h_{ij}^{0}(t)+
h_{ij}^{\mathrm{heat}}(t)+h_{ij}^{\mathrm{trauma}}(t)
+h_{ij}^{\mathrm{infection}}(t)+h_{ij}^{\mathrm{care}}(t)
+h_{ij}^{\mathrm{int}}(t).
$$

$h^0$ is the counterfactual baseline, while the interaction term represents effects that cannot be allocated independently, such as nutritional impairment increasing the fatality risk from infection; the @who2024 identifies the heightened vulnerability of undernourished children to disease and death. Counting a malnutrition death and an infection death from separate models would assign the same person twice.

For a short interval $\Delta t$, expected deaths are

$$
d_{ij}(t)=N_{ij}(t)
\left[1-\exp\{-h_{ij}(t)\Delta t\}\right].
$$

Cause attribution can be assigned from competing hazards conditional on death. Excess deaths compare the factual trajectory with a baseline trajectory that shares demographic aging and non-climate secular trends. The baseline is uncertain and should be an ensemble.

The target statistic is

$$
D^*=\max_{\tau}
\sum_{t=\tau}^{\tau+364}
\sum_{i,j}d_{ij}^{\mathrm{excess}}(t).
$$

The simulation horizon must extend for years. A physical shock can precede peak mortality through stock depletion, conflict, or epidemic delay. A calendar-year total could split a single episode across December and January, so the rolling window is part of the estimand.

Simple arithmetic gives the scale of the threshold. At a reference population of 8.2 billion, 1 billion deaths require an average excess rate of about 3.34 deaths per 10,000 people per day if the whole population is exposed for 365 days. If 4 billion people form the exposed population, the required average is about 6.85 per 10,000 per day. If 2 billion are exposed, half must die within the window.

The @ipc2021 uses a crude non-trauma death-rate threshold of at least 2 per 10,000 per day as one of several requirements for classifying an area in famine, alongside severe food-consumption and child-malnutrition conditions. Sustained for a year across 8.2 billion people, that rate corresponds arithmetically to about 599 million deaths before accounting for changing populations or competing risks. The comparison indicates scale only, since IPC classification is local, evidentiary, and multidimensional and does not define a global mortality function.

## Cascade diagnostics

A cascade is identified by propagation, and co-occurrence of failures is insufficient. Define a failure event $F_{i\ell}$ when a service in region $i$ and layer $\ell$ crosses a prespecified functional threshold for a minimum duration. Around state $x(t)$, perturb each event and estimate

$$
K_{ab}(t)=
\mathbb{E}\left[
\text{new failures of type }b
\mid \text{one additional failure of type }a,x(t)
\right].
$$

The spectral radius

$$
\mathcal{R}_C(t)=\rho\!\left(K(t)\right)
$$

is a local amplification diagnostic. Values above one indicate that a marginal failure generates more than one downstream failure under the current state and threshold definitions. $\mathcal{R}_C$ depends on the state of the system: $K$ changes with season, buffers, behavior, geography, and the size of the perturbation. Nonlinear cascades can occur below a local linear threshold after a large shock, while rapid repair can stop propagation above it.

Minimal cut sets provide a more direct tail diagnostic. A cut set is a smallest combination of exogenous shocks, buffer states, and responses whose joint occurrence drives $D^*$ above the threshold. Candidate sets might combine synchronized crop losses, depleted reserves, export restrictions, financing failure, and relief obstruction. The model should search for multiple qualitatively distinct sets. If every billion-death run depends on one poorly identified parameter at its maximum, the result is a sensitivity artifact.

Path decomposition should report how deaths accumulate. For each run, the model can assign shares to pathways such as climate-to-heat, climate-to-food-to-nutrition-infection, and climate-to-infrastructure-to-care interruption. Interaction shares remain explicit. A single global death number without path and state histories cannot be audited.

## Calibration and validation

Calibration proceeds by modules before integration. Climate hazards are checked against observations and physical-model ensembles. Crop responses are checked out of sample across regions and events. Trade, stock, price, and restriction modules are evaluated on the 2007-2008 and 2010-2011 food-price crises, the 2022 wheat shock, and commodity-specific disruptions. Energy, water, port, and health modules require their own event sets.

The integrated model then faces crises that crossed layers, including pandemic-era border controls, labor loss, fiscal support, school closure, and supply-chain disruption, which offer data on common shocks with heterogeneous institutional response. Conflict-associated food emergencies test access, displacement, and relief obstruction, while IPC classifications provide outcome definitions and evidence protocols that are themselves subject to measurement error.

Survival cases receive equal weight. Regions that maintained nutrition through drought, states that kept trade open during price spikes, grids restored before water systems failed, and epidemics contained amid displacement identify buffer and response parameters. Model selection should penalize false cascades. An implementation that reproduces famous failures and predicts collapse in resilient controls is invalid.

Temporal validation is essential. Parameters estimated through year $t$ should predict held-out episodes after $t$. Geographic transfer should be tested separately because the same observed indicator can encode different institutions. Latent states such as government capacity require measurement models with multiple indicators and uncertainty; scores assigned by hand after outcomes are known are inadmissible.

Structural uncertainty cannot be absorbed into wider random noise. Competing crop models, trade responses, conflict specifications, adaptation functions, and mortality models form a structured ensemble. Each member must satisfy module-level validation. Ensemble weights should be declared before the global tail is inspected.

No historical event validates a billion-death climate cascade end to end. Validation can establish that each link behaves credibly over observed ranges and that the integrated system reproduces smaller cross-layer episodes. Extrapolation to the far tail remains conditional. That limitation belongs in every reported probability.

## Rare-event sampling

If the true crossing probability is small, ordinary Monte Carlo is wasteful. A set of 1 million runs with no crossing does not prove impossibility; it supplies only a bound conditional on the sampling distribution and model. Direct sampling can also miss narrow combinations that dominate the tail.

Subset simulation replaces one rare event with a sequence of less rare conditional events [@au2001]. Define intermediate thresholds $0<d_1<\cdots<d_m=10^9$ for $D^*$, or use a composite stress score before mortality becomes informative. Then

$$
\Pr(D^*>10^9)=
\Pr(D^*>d_1)
\prod_{k=2}^{m}
\Pr(D^*>d_k\mid D^*>d_{k-1}).
$$

Markov-chain sampling within each subset concentrates computation near failure while preserving probability weights. Importance sampling and cross-entropy methods provide alternative checks. Agreement across samplers is evidence against an algorithmic artifact.

Rare-event algorithms have their own failure mode. If proposal distributions favor physically incoherent hazard combinations, they can populate the tail with impossible worlds. Every sampled driver must respect joint climate physics, demographic conservation, response constraints, and the calibrated dependence structure. Analysts should publish the dominant paths and importance weights alongside the final estimate.

The first scientific output may be a non-reachability result over validated parameter ranges. If no admissible combination crosses the threshold without leaving those ranges, that result is informative, and parameter ranges should not be widened to force a crossing.

## Attribution to anthropogenic forcing

A climate-triggered cascade is not automatically climate-attributable. Governance failures, war, financial crises, and policy choices may dominate a path. Attribution requires paired worlds.

For each set of non-climate initial conditions and random seeds, run a factual climate ensemble $F$ containing estimated anthropogenic forcing and a counterfactual ensemble $C$ without that forcing. The National Academies [-@nasem2016] describe this factual-counterfactual logic for extreme-event attribution. Extending it through an impact network is demanding because every downstream behavioral branch can diverge.

Two target quantities are

$$
\Delta P_{1B}=
\Pr(D^*>10^9\mid F)-
\Pr(D^*>10^9\mid C)
$$

and

$$
D_{\mathrm{attr}}=
\mathbb{E}[D^*\mid F]-
\mathbb{E}[D^*\mid C].
$$

The probability difference and attributable expectation answer different questions. A forcing can raise average mortality while leaving an extremely remote threshold almost unchanged. It can also change the threshold probability through synchronization even when the mean effect is modest.

Identical non-climate seeds improve pairing, but the counterfactual is not observed. Ocean states, adaptation histories, land use, and development may themselves reflect past climate. Several counterfactual constructions are needed. Attribution should be reported across them, with separate physical, impact-model, parameter, and sampling uncertainty.

Policy experiments belong inside both worlds. Coordinated stock release, open trade, cash support, emergency nutrition, grid islanding, water treatment, vaccination, protected relief corridors, and debt facilities change distinct edges. @kuhla2024 show that cooperation altered the realized wheat shock relative to modeled counterfactuals. A useful catastrophe model should identify interventions that break common cut sets and should expose interventions that protect one region by exporting risk.

## Interpreting results

Suppose a validated implementation produces a nonzero estimate for $\Pr(D^*>10^9\mid F)$. The estimate would be conditional on the model family, forcing ensemble, socioeconomic pathways, response rules, and observation window, and its credibility would depend on module validation, stability across structural ensembles, effective sample size in the tail, and whether dominant paths remain inside empirical or physically defended ranges. It would not be a forecast that 1 billion deaths will occur.

Suppose the estimate is zero in all sampled runs. That would not establish a mathematical impossibility. The report should give an upper confidence bound for the modeled distribution, list excluded mechanisms, and show how close admissible runs came to the threshold. A model without great-power war, novel pathogens, or unmodeled technology failures says nothing about cascades dominated by those exclusions.

The model should be refused as evidence if mortality is obtained by summing overlapping sectoral estimates, if export bans or state failures are imposed whenever needed to cross the threshold, if only collapse cases enter calibration, or if a single unvalidated module controls the tail. It should also be refused if the factual and counterfactual worlds change non-climate assumptions, since the difference could no longer be assigned to anthropogenic forcing.

Stated precisely, the question is whether calibrated climate hazards can push a buffered, adaptive, politically responsive world into a region of state space where cross-layer failures outrun repair and produce 1 billion unique excess deaths in some 365-day window. Current evidence does not answer it, and a model built to answer it must be able to return a negative result.

## References
