# Climate-Triggered Global Cascades

Pathways to a Billion-Death Year: Modeling Climate-Triggered Global Cascades.

No existing model supports a defensible probability that anthropogenic climate change will cause 1 billion excess deaths within a rolling year, because no model class links forcing to unique deaths across coupled human systems. We specify 1177-G, a stochastic hybrid causal model of climate-triggered failure across crop, food, trade, energy, water, finance, governance, conflict, health, and displacement networks. The outcome is the maximum 365-day sum of excess mortality, with each death assigned once through competing hazards; summing sectoral estimates would double-count. Buffer depletion, recovery time, behavioral response, and state capacity determine whether shocks dissipate or compound. A state-dependent cascade matrix measures amplification between layer-region failures, and minimal cut sets identify the combinations capable of crossing the threshold, which corresponds to 12.2% of the 2024 world population, or about 3.34 excess deaths per 10,000 people per day sustained for a year. The design combines module-level calibration, validation against cases in which large shocks were absorbed, rare-event sampling, and paired factual and counterfactual climate ensembles. Existing crop, network, famine, and nuclear-winter studies constrain individual modules and cannot validate the global tail. A simulated billion-death year would be a conditional model result, and we state the tests under which such a result should be rejected as evidence about climate risk.

## Build

```bash
uv run build.py          # -> paper/PAPER.pdf  (vendored canonical recipe)
```

Requires `pandoc` and `xelatex` on PATH. From the workspace you can also run `papers build climate-triggered-global-cascades`.

Part of [piatra-papers](https://github.com/piatra-institute). See the workspace docs for the research and writing pipelines.
