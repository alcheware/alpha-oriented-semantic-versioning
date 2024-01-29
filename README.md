# Alpha-oriented Semantic Versioning

AO-SemVer[^1] is an extension to [Semantic Versioning (v2.0.0)](https://semver.org/spec/v2.0.0.html) to suit better for active development phase prior to release.

[^1]: Alpha-oriented Semantic Versioning. Alpha here is used to mean [pre-alpha](https://en.wikipedia.org/wiki/Software_release_life_cycle#Pre-alpha) phase.

## Purpose of Its Existence

Plain SemVer did not meet our needs for pre-release development phase where constant changes were happening and features were developed in frequently made commits rather than having written all parts of the feature and commiting it at once.

We believe that logical grouping and frequent commits helps the flow of development to be understood more easily and clearly.

## Quick Start

==v0.28.5-f7.2.80== is a typical AO-SemVer in practice.

1. **v0.28.5** => Plain Old (but Gold) Semantic Versioning: MAJOR.MINOR.PATCH.
2. **-** => (hypen) Indicates the beginning of AO-SemVer.
3. **f7** => Indicates the feature worked on.
4. **2** => One of the main steps to achieve that feature.
5. **80** => Percentage of completation for the given feature + main step.
