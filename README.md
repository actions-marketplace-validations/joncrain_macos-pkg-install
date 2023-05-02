# macos-pkg-install

* _Note: Must be run on a `macos` runner._

## Inputs

|      Input       |        type         |                                            Example/Default                                            |                             Description                             |
| :--------------: | :-----------------: | :---------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------: |
| pkg_url | `string` (required) | None | Location of pkg to install. This will be downloaded and installed by the action. |


## Usage

```yaml
...
    steps:
      - name: macOS pkg install
        id: install-pkg
        uses: joncrain/macos-pkg-install@v1.0
        with:
          pkg_url: https://github.com/munki/munki/releases/download/v6.3.1/munkitools-6.3.1.4580.pkg
```

* Free software: [MIT license](LICENSE)
