# Package index

## Basic usage

- [`mantis_report()`](https://docs.ropensci.org/mantis/reference/mantis_report.md)
  : Create an interactive time series report from a data frame
- [`inputspec()`](https://docs.ropensci.org/mantis/reference/inputspec.md)
  : Specify relevant columns in the source data frame
- [`example_prescription_numbers`](https://docs.ropensci.org/mantis/reference/example_prescription_numbers.md)
  : Example data frame containing numbers of antibiotic prescriptions in
  long format

## Specifying the output format

- [`outputspec_interactive()`](https://docs.ropensci.org/mantis/reference/outputspec_interactive.md)
  : Specify output options for an interactive report
- [`outputspec_static_heatmap()`](https://docs.ropensci.org/mantis/reference/outputspec_static_heatmap.md)
  : Specify output options for a static report containing heatmaps
- [`outputspec_static_multipanel()`](https://docs.ropensci.org/mantis/reference/outputspec_static_multipanel.md)
  : Specify output options for a static report containing a panel of
  plots.

## Specifying alerting rules

- [`alertspec()`](https://docs.ropensci.org/mantis/reference/alertspec.md)
  : Specify alerting rules to be run on the data and displayed in the
  report
- [`alert_rules()`](https://docs.ropensci.org/mantis/reference/alert_rules.md)
  : Create set of alert rules
- [`alert_missing()`](https://docs.ropensci.org/mantis/reference/alert_rule_types.md)
  [`alert_equals()`](https://docs.ropensci.org/mantis/reference/alert_rule_types.md)
  [`alert_above()`](https://docs.ropensci.org/mantis/reference/alert_rule_types.md)
  [`alert_below()`](https://docs.ropensci.org/mantis/reference/alert_rule_types.md)
  [`alert_difference_above_perc()`](https://docs.ropensci.org/mantis/reference/alert_rule_types.md)
  [`alert_difference_below_perc()`](https://docs.ropensci.org/mantis/reference/alert_rule_types.md)
  [`alert_custom()`](https://docs.ropensci.org/mantis/reference/alert_rule_types.md)
  : Built-in alert rules
- [`mantis_alerts()`](https://docs.ropensci.org/mantis/reference/mantis_alerts.md)
  : Generate a data frame containing alert results

## Creating a bespoke report

- [`bespoke_rmd_initialise_widgets()`](https://docs.ropensci.org/mantis/reference/bespoke_rmd_initialise_widgets.md)
  : Initialise HTML widgets
- [`bespoke_rmd_output()`](https://docs.ropensci.org/mantis/reference/bespoke_rmd_output.md)
  : Dynamically generate mantis output for an rmd chunk
- [`bespoke_rmd_alert_results()`](https://docs.ropensci.org/mantis/reference/bespoke_rmd_alert_results.md)
  : Dynamically generate a table containing alert results for an rmd
  chunk
