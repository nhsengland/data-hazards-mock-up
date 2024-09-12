# Hazard: Difficult To Understand

<img src="/images/difficult-to-understand.png" alt="A red diamond shaped outline (like a warning sign) with an image of a closed box and a question mark next to it" width="250"/>

## Description

There is a danger that the technology is difficult to understand.

### Is the technology itself hard to interpret? (e.g. neural nets)?

#### Could this affect trouble-shooting?

#### Could this make it hard to spot incorrect results?

#### Could this impair users ability to understand results?

### Is the implementation difficult to understand? (i.e. missing documentation, code not available, training details not provided)

## More information

More information about this hazard is available via the [Data Hazards Project website][1].

## Safety Precautions

- Make code Open Source with an appropriate software license where possible.
- Adopt a standard of Reproducible Analytical Pipelines[2].
- Compare results to white box (explainable) methods such as [Random Forest](https://en.wikipedia.org/wiki/Random_forest) or [Regression](https://en.wikipedia.org/wiki/Regression_analysis), which may perform just as well.
- Ensure code is well documented with accompanying and/or inline documentation.

[1]: https://datahazards.com/hazards/difficult-to-understand.html
[2]: https://nhsdigital.github.io/rap-community-of-practice/
