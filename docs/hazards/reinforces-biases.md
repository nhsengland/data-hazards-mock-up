# Hazard: Reinforces Existing Biases

<img src="/images/reinforce-bias.png" alt="A red diamond shaped outline (like a warning sign) with a dark head and shoulders, who has a white triangle in their mind. They are looking out at a black circle, a black square and a larger white triangle just ahead of them. This indicates that the largest shape is the one that they think of." width="250"/>

## Description

Reinforces unfair treatment of individuals and groups. This may be due to for example input data, algorithm or software design choices, or society at large.

__Note:__ this is a Hazard in it's own right, even if it isn't then used to harm people directly, due to e.g. reinforcing stereotypes.

### Does the input data contain intrinsic bias?

#### Is the bias acceptable? (i.e. if it only contains data about a certain group because this is the scope of the project)

#### If not, are there more representative alternatives? Or can we make the dataset more representative?

### Have you thought about which performance metrics are most applicable here to ensure you're not missing bias?

### Does the architecture of the technology particularly susceptible to bias?

## More information

More information about this hazard is available via the [Data Hazards Project website][1].

## Safety Precautions

- Test the effect of the algorithm for different marginalised groups, considering different definitions of bias and fairness.
- Think about the bias of the algorithm, what intrinsic bias it contains, and how this can be reduced. See Hooker (2021)[^1].
- Do not deploy tools that are know to reinforce biases against particular groups (for instance, systemic racism).

[1]: https://datahazards.com/hazards/reinforces-biases.html
[^1]: [Moving beyond “algorithmic bias is a data problem”](https://doi.org/10.1016/j.patter.2021.100241), Patterns 2(4)
