# 2.0.14

## Minor Changes

* Add try-except to pickling pairwise plots now fails silently (on info-level)
* Add support for Constant hyperparameters
* Beautify code in visualizer-class

## Bug fixes

* Fix axis on pairwise mixed cat/non-cat plots
* Fix visualizer's `create_all_plots`

# 2.0.13

## Bug fixes

* Unassigned variable for marginal plot

# 2.0.12

## Major Changes

* Enforce log-scale in plots if specified in argument of plot-function
* Add option to plot incumbent(s) if it/they is/are passed

## Minor Changes

* Add legend to plots
* Add grid to plots

# 2.0.11

## Bug fixes

* Having a boolean in pairwise marginal plots does not lead to indice-crash anymore (#80)
