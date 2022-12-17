# DevOps-TrialProject

## Introduction
This trial project is adapted based off [this](https://www.youtube.com/watch?v=5sZAx2ylsOo&list=PLRrXdvWkq2vjT59ziM0BMi_BFoYBbH2Ru&index=3&t=247s&ab_channel=TusharRajpoot) tutorial.

Just learning the basics of DevOps, for possible implementation in projects in the future.

Will enhance along the way with new knowledge.

## Learning points:

### AWS and code integration:
1. To take note of the AWS resource regions - they have to be synchronised.
2. At `Build, push docker image` in `deploy.yml`, the workflow will timeout if there is no ECR to push to.
3. Port 22 is for SSH, 80 for HTTP

### Code/Syntax stuff
1.  Versioning of the `actions/checkout` seems to be unimportant in this case - as [this](https://github.com/actions/checkout/compare/v2.4.2...v3.0.2#diff-b335630551682c19a781afebcf4d07bf978fb1f8ac04c6bf87428ed5106870f5R17-R18) commit shows the version is updated when node runtime is updated. It may be important if we are looking for new commands/features though.