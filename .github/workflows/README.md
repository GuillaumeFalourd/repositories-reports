# Workflows descriptions

The [Reports Generator workflow](https://github.com/GuillaumeFalourd/repositories-reports/actions/workflows/1-reports-generator.yml) generates once a week a report with insights from the Github user public and private repositories.

The [Alternative Reports Generator workflow](https://github.com/GuillaumeFalourd/repositories-reports/actions/workflows/2-alternative-reports-generator.yml) does the same thing that the 1st workflow, but without using the [Github Checkout Action](https://github.com/actions/checkout). This workflow jobs use instead a docker image, and clone the current repository to add the new report file on the specified directory.
