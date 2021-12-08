# Changelog

## [0.2.0](https://www.github.com/googleapis/python-spanner-sqlalchemy/compare/v0.1.0...v0.2.0) (2021-12-08)


### Features

* add code samples ([#55](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/55)) ([406c34b](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/406c34bdb21e01a1317c074fab34d87bb3d61020))
* set user-agent string to distinguish SQLAlchemy requests ([#116](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/116)) ([b5e1a21](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/b5e1a211a0475690feed36fd222a41c216d8fb82))
* support computed columns ([#139](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/139)) ([046ca97](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/046ca975778f4793e2c37d70d2a602546f9d4699)), closes [#137](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/137)
* support JSON data type ([#135](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/135)) ([184a7d5](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/184a7d576a790bbbd049fe80d589af78831379b4))
* support read_only connections ([#125](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/125)) ([352c47d](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/352c47de7bb4ea1c30b50a7fe5aee0c4d102e80e))
* support stale reads ([#146](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/146)) ([d80cb27](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/d80cb2792437731c24905c7a6919468c37779c67))


### Bug Fixes

* ALTER COLUMN NOT NULL directive fails because of inappropriate syntax ([#124](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/124)) ([c433cda](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/c433cda99fd8544810c878328a272a3a9430630f))
* array columns reflection ([#119](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/119)) ([af3b97b](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/af3b97bfa4b3ed4b223384c9ed3fa0643204d8c9)), closes [#118](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/118)
* calculate limit value correctly for offset only queries ([#160](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/160)) ([6844336](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/684433682ed29d9cde8c9898796024cefeb38493))
* correct typo in spanner_interleave_on_delete_cascade keyword ([#99](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/99)) ([a0ebf75](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/a0ebf758eda351c0a20103f9e8c2243f002b2e6e))
* raise Unimplemented error when creating temporary tables ([#159](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/159)) ([646d6ac](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/646d6ac24ccd0643b67abff9da28118e0a6f6e55))
* rollback failed exception log ([#106](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/106)) ([809e6ab](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/809e6abb29f82a7fbe6587d606e8d75283f2a2fe))


### Documentation

* add query hints example ([#153](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/153)) ([9c23804](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/9c23804746bc8c638b6c22f2cb6ea57778f7fd19))
* reformatted README titles ([#141](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/141)) ([a3ccbac](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/a3ccbac476679fe8048ed2109e5489b873278c9c))
* update benchmarks ([#155](https://www.github.com/googleapis/python-spanner-sqlalchemy/issues/155)) ([3500653](https://www.github.com/googleapis/python-spanner-sqlalchemy/commit/35006536e4de31dbcba022b73f0aadf39bc89e39))