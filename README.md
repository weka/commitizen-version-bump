# commitizen-version-bump

Commitizen customized for Weka projects (https://commitizen-tools.github.io/commitizen/customization)


## Usage:

Install this Python package, and set the Commitizen config option `name` to `cz_version_bump`.

If using [`commitizen-action`](https://github.com/commitizen-tools/commitizen-action), this package can be installed using the `extra_requirements` option:


```yml
- name: Version bump
  uses: commitizen-tools/commitizen-action@master
  with:
    github_token: "${{ secrets.GITHUB_TOKEN }}"
    extra_requirements: 'git+https://github.com/weka/commitizen-version-bump@master'
```
