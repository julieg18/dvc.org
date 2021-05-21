# Visualize and Compare Experiments

You can visualize and compare experiments using a variety of tools.

## Generate metric plots

You can visualize certain metrics of machine learning experiments as plots.
Usual plot examples are AUC curves, loss functions, and confusion matrices,
among others. This type of metrics files are created by users, or generated by
user data processing code, and can be defined in dvc.yaml (plots field) for
tracking (optional). Refer to the
[DVC plots documentation](/doc/command-reference/plots) for details on how plots
are generated.

To generate metric plots, select one or more experiments (represented by the
commits), and click on the 'Show plots' button.

<img src="https://static.iterative.ai/img/studio/select_commits.png" alt="drawing" width="300"/>

The plots will appear below the tabular display. If you have selected more than
one experiment, you can use the plots to compare them.

<img src="https://static.iterative.ai/img/studio/plots.png" alt="drawing" width="300"/>

## Generate trend charts

Click on the Trends button to generate a plot of how the metrics changed over
the course of the different experiments. For each metric, the trend charts show
how the metric changed from one commit to another. You can include one or more
branches in the trend chart.

<img src="https://static.iterative.ai/img/studio/trends.png" alt="drawing" width="300"/>

## Compare experiments

To compare different experiments, select two experiments (represented by the
commits), and click on the `Compare` button. The metrics, parameters and files
in the selected experiments will be displayed side by side for easy comparison.

<img src="https://static.iterative.ai/img/studio/compare.png" alt="drawing" width="300"/>