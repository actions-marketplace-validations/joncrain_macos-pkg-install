# macos-pkg-install

* _Note: Must be run on a `macos` runner._

## Inputs

|      Input       |        type         |                                            Example/Default                                            |                             Description                             |
| :--------------: | :-----------------: | :---------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------: |
| pkg_url | `string` (required) | None | Location of pkg to install. This will be downloaded by the action. |


## Usage

```yaml
...
    steps:
      - uses: actions/checkout@v3
      - name: macOS pkg install
        id: install-pkg
        uses: joncrain/macos-pkg-install@v1.0
```

* Free software: [MIT license](LICENSE)
