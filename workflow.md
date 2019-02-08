# Workflow Checklist

- [ ] [Requirements complete]()
- [ ] Linting and testing passing locally
- [ ] [Develop deployment](https://eu-west-2.console.aws.amazon.com/codesuite/codepipeline/pipelines/df-ae-pipeline-system/view?region=eu-west-2) and successful [Sonar passing](https://sonarcloud.io/dashboard?id=defence-forecaster%3Adefence-forecaster)
- [ ] Documentation

## Kickoff meeting

- [ ] Include another developer and product owner in discussing requirements and approach.

## Quality Checks

- [ ] Check code for dupulication.
- [ ] Check code is self documenting: remove comments unless needed.
- [ ] Can any global variables be replaced?
- [ ] Can any of the code be replaced with library functions?
- [ ] Can any logging or debugging code be removed? Ctrl Shift F for console logs
- [ ] Does code follow defined architecture?
- [ ] Is any code invoking memory leaks?
- [ ] Check your variable names used for classes, enum, struct , methods, and variables?

## Error checks

- [ ] Are http/websocket/graphql connections handled in an error state?
- [ ] Check all error states are captured in every subscribe or http block.
- [ ] Check cases for mutated data.

## Best Practice

- [ ] Encapsulate methods to promote how they are used

## Pre pull request

- [ ] Refactor code.
- [ ] Sound out code with another developer.

## Dev Testing

- [ ] Check code coverage conforms to agreed acceptable level
- [ ] Test requirements in chrome
- [ ] Repeat in firefox and edge
- [ ] Repeat in iPad
