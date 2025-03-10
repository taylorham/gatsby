# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [4.1.1](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@4.1.0...gatsby-transformer-react-docgen@4.1.1) (2019-07-11)

**Note:** Version bump only for package gatsby-transformer-react-docgen

# [4.1.0](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@4.0.4...gatsby-transformer-react-docgen@4.1.0) (2019-06-20)

**Note:** Version bump only for package gatsby-transformer-react-docgen

## [4.0.4](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@4.0.2...gatsby-transformer-react-docgen@4.0.4) (2019-06-19)

### Bug Fixes

- **gatsby-transformer-react-docgen:** always create description nodes ([#14876](https://github.com/gatsbyjs/gatsby/issues/14876)) ([48a9e10](https://github.com/gatsbyjs/gatsby/commit/48a9e10))

## [4.0.3](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@4.0.2...gatsby-transformer-react-docgen@4.0.3) (2019-06-19)

### Bug Fixes

- **gatsby-transformer-react-docgen:** always create description nodes ([#14876](https://github.com/gatsbyjs/gatsby/issues/14876)) ([48a9e10](https://github.com/gatsbyjs/gatsby/commit/48a9e10))

## [4.0.2](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@4.0.1...gatsby-transformer-react-docgen@4.0.2) (2019-05-30)

**Note:** Version bump only for package gatsby-transformer-react-docgen

## [4.0.1](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@4.0.0...gatsby-transformer-react-docgen@4.0.1) (2019-04-08)

**Note:** Version bump only for package gatsby-transformer-react-docgen

# [4.0.0](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.7...gatsby-transformer-react-docgen@4.0.0) (2019-04-02)

### Features

- **gatsby-transformer-react-docgen:** use local babel config for react-docgen ([#12001](https://github.com/gatsbyjs/gatsby/issues/12001)) ([4a2680b](https://github.com/gatsbyjs/gatsby/commit/4a2680b))

### BREAKING CHANGES

- **gatsby-transformer-react-docgen:** now uses the local babel config with a fallback

- Update README.md

## [3.0.7](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.6...gatsby-transformer-react-docgen@3.0.7) (2019-03-15)

**Note:** Version bump only for package gatsby-transformer-react-docgen

## [3.0.6](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.5...gatsby-transformer-react-docgen@3.0.6) (2019-03-11)

**Note:** Version bump only for package gatsby-transformer-react-docgen

## [3.0.5](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.4...gatsby-transformer-react-docgen@3.0.5) (2019-02-06)

**Note:** Version bump only for package gatsby-transformer-react-docgen

## [3.0.4](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.3...gatsby-transformer-react-docgen@3.0.4) (2019-02-01)

**Note:** Version bump only for package gatsby-transformer-react-docgen

## [3.0.3](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.2...gatsby-transformer-react-docgen@3.0.3) (2019-01-29)

### Features

- **gatsby-transformer-react-docgen:** allow parsing TypeScript files ([#11265](https://github.com/gatsbyjs/gatsby/issues/11265)) ([c9a8991](https://github.com/gatsbyjs/gatsby/commit/c9a8991))

## [3.0.2](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.1...gatsby-transformer-react-docgen@3.0.2) (2019-01-25)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="3.0.1"></a>

## [3.0.1](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@3.0.0...gatsby-transformer-react-docgen@3.0.1) (2019-01-23)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="3.0.0"></a>

# [3.0.0](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.3...gatsby-transformer-react-docgen@3.0.0) (2018-12-31)

### Features

- **gatsby-transformer-react-docgen:** support multiple doclets of same tag ([#10342](https://github.com/gatsbyjs/gatsby/issues/10342)) ([c5c84a0](https://github.com/gatsbyjs/gatsby/commit/c5c84a0))

### BREAKING CHANGES

- **gatsby-transformer-react-docgen:** Shape of `doclet` field is changed. It's no longer object but array of objects with `tag` and `value` fields:

gatsby-transformer-react-docgen@^2.0.0:

```json
{
  "doclets": {
    "type": "{Foo}",
    "property": "{string} property1"
  }
}
```

gatsby-transformer-react-docgen@^3.0.0:

```json
{
  "doclets": [
    { "tag": "type", "value": "{Foo}" },
    { "tag": "property", "value": "{string} property1" },
    { "tag": "property", "value": "{number} property2" }
  ]
}
```

<a name="2.1.3"></a>

## [2.1.3](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.2...gatsby-transformer-react-docgen@2.1.3) (2018-11-29)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.2"></a>

## [2.1.2](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1...gatsby-transformer-react-docgen@2.1.2) (2018-10-29)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1"></a>

## [2.1.1](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-rc.5...gatsby-transformer-react-docgen@2.1.1) (2018-09-17)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-rc.5"></a>

## [2.1.1-rc.5](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-rc.4...gatsby-transformer-react-docgen@2.1.1-rc.5) (2018-09-11)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-rc.4"></a>

## [2.1.1-rc.4](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-rc.3...gatsby-transformer-react-docgen@2.1.1-rc.4) (2018-09-11)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-rc.3"></a>

## [2.1.1-rc.3](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-rc.2...gatsby-transformer-react-docgen@2.1.1-rc.3) (2018-09-11)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-rc.2"></a>

## [2.1.1-rc.2](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-rc.1...gatsby-transformer-react-docgen@2.1.1-rc.2) (2018-09-11)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-rc.1"></a>

## [2.1.1-rc.1](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-rc.0...gatsby-transformer-react-docgen@2.1.1-rc.1) (2018-08-29)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-rc.0"></a>

## [2.1.1-rc.0](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-beta.5...gatsby-transformer-react-docgen@2.1.1-rc.0) (2018-08-21)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-beta.5"></a>

## [2.1.1-beta.5](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-beta.4...gatsby-transformer-react-docgen@2.1.1-beta.5) (2018-08-08)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-beta.4"></a>

## [2.1.1-beta.4](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-beta.3...gatsby-transformer-react-docgen@2.1.1-beta.4) (2018-07-21)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-beta.3"></a>

## [2.1.1-beta.3](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-beta.2...gatsby-transformer-react-docgen@2.1.1-beta.3) (2018-06-23)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-beta.2"></a>

## [2.1.1-beta.2](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-beta.1...gatsby-transformer-react-docgen@2.1.1-beta.2) (2018-06-20)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-beta.1"></a>

## [2.1.1-beta.1](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@2.1.1-beta.0...gatsby-transformer-react-docgen@2.1.1-beta.1) (2018-06-17)

**Note:** Version bump only for package gatsby-transformer-react-docgen

<a name="2.1.1-beta.0"></a>

## [2.1.1-beta.0](https://github.com/gatsbyjs/gatsby/compare/gatsby-transformer-react-docgen@1.0.17...gatsby-transformer-react-docgen@2.1.1-beta.0) (2018-06-17)

**Note:** Version bump only for package gatsby-transformer-react-docgen
