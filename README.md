# Driving Scenario Input Output Dataset

This dataset contains data which enables the evaluation of metamodels and approches for targeted test case selection without setting up test environments or performing test runs. The dataset is split into different scenarios: Each scenario comes with one or more tabular datasets containing the inputs and outputs of different test cases (concrete scenarios). A configuration file describes which of the columns are inputs and outputs and explains the different parameters. The config also contains verbal descriptions of the scenarios. Additionally, animations of the scenarios are available.

Please check the respective folders to get more information on the scenarios. You can find an overview of the scenario's properties here:
|Title|Number of Inputs|Functional Description|
|-|-|-|
|[Cut-In](data/202109_Cut-In/)|2|An automated vehicle (ego) is driving in the middle lane of a straight road with three lanes. Another vehicle drives ahead in the right lane and immidiately cuts into the ego's lane.|
|[Emergency Braking](data/202109_Emergency_Braking/)|5|An automated vehicle follows another vehicle (co) on a straight road. Suddenly, the co carries out an emergency braking maneuver.|
|[Following](data/202109_Following/)|13|An automated vehicle follows another vehicle, which initially accelerates, holds its velocity and then brakes.|
|[Lane-Keeping](data/202109_Lane-Keeping/)|15|An automated vehicle has to follow a curved road, where different obstacles can hide the lane markings.|
|[Parking](data/202109_Parking/)|20|An automated vehicle drives across a parking lot. Two other vehicles occlude a third vehicle that suddenly leaves its parking lot.|
|[Jaywalking](data/202202_Jaywalking/)|7|An automated vehicle (AV) drives in a suburban area. Suddenly, an initially occluded child crosses the road in front of the AV.|

## Citation
For more information, please look at our publication:
```
@article{winkelmann_probabilistic_2021,
	title = {Probabilistic {Metamodels} for an {Efficient} {Characterization} of {Complex} {Driving} {Scenarios}},
	url = {http://arxiv.org/abs/2110.02892},
	journal = {arXiv:2110.02892 [cs, eess]},
	author = {Winkelmann, Max and Kohlhoff, Mike and Tadjine, Hadj Hamma and Müller, Steffen},
	month = oct,
	year = {2021},
}
```

## Extension of the Dataset
We invite other researchers to add similar datasets to this repository. Please feel free to open pull requests.