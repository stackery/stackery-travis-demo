# Stackery + Travis Demo

This repository stored the source code required to follow along with the <a href="https://docs.stackery.io/docs/using-stackery/cicd-and-stackery/" target="_blank" alt="stackery-travis-tutorial">CI/CD with Stackery & Travis CI tutorial</a>.

## Key Files
* `src/.travis.yml`: Travis CI configuration YAML for deploying our custom Stackery deploy script
* `src/scripts/deploy.sh`: Custom Stackery deploy script that runs everytime changes are committed to this repository's `stg` or `master` branch

Additional documentation for the Travis CI related files described can be found at their <a href="https://docs.travis-ci.com/" target="_blank" alt="travis-ci-docs">documentation site</a>.
