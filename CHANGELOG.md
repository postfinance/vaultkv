## 0.0.5 (2023-01-05)



## 0.0.4 (2022-02-28)



## 0.0.3 (2021-05-28)



## 0.0.2 (2021-05-27)


### Bug Fixes

* **common**: version detection fixed when engine gets converted ([558cf0da](https://github.com/postfinance/vaultkv/commit/558cf0da))
  > Version detection failed, when the generic backend was created before [0.8.3](https://github.com/hashicorp/vault/blob/master/CHANGELOG.md#083-september-19th-2017)
  > and converted to v2 later.
