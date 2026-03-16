# Mars-marketplace

Welcome to the official STZ Robotics Marketplace Registry for the MARS Framework. This repository acts as the global database for all verified MARS extensions.

## How to submit your Feature
Want to share your custom FRC library with the world? Follow these steps:

1. Create your Java library and host it on your own GitHub/Maven.
2. Ensure you have a valid `MarsFeature.json` in the root of your repository following the STZ standards.
3. Fork this repository.
4. Add your Raw GitHub URL to the `verifiedFeatures` array in `registry.json`.
5. Submit a Pull Request (PR) for our team to review.

## Allowed Categories
To maintain order in the MARS ecosystem, your `category` in the JSON must be EXACTLY one of the following:
* `Vision`
* `Odometry & Auto`
* `Hardware`
* `Control & Math`
* `Logging & Telemetry`
* `Utils`
* `Processor`
* 
*Developed with love by STZ Robotics.*
