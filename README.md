# eslint-config-duo

> ESLint configuration for the projects in the duojs organization.

## Usage

ESLint allows sharing config via the `extends` property in the `.eslintrc`.
There should be 2 config files for each project:

### .eslintrc

```json
{
  "extends": "duo"
}
```

### test/.eslintrc

```json
{
  "extends": "duo/test"
}
```

Each project is allowed to have more config than this in case something is
genuinely unique to that project, but that should be kept to a minimum.


## Proposing Changes

Any proposals for changes to the ESLint config should be run through a PR
on this repo. That gives all the @duojs/owners the ability to review the
proposal and vote on it.
