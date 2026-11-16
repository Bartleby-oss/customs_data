# customs_data

## 每月打包

Completed 2020 H2 export delivery packs:

| File | Bytes | SHA256 |
| --- | ---: | --- |
| `每月打包/customs_2020_07_export.zip` | 48892324 | `efb255fd05d605134c60d7a91068484f5cea4d93cbac84d8e1ace05a238fd225` |
| `每月打包/customs_2020_08_export.zip` | 49122619 | `8dad8003240e4bccd6f2c2369a3c6678ddfac601278fb00a643877ac01680003` |

Checksums are listed in `每月打包/SHA256SUMS_export.txt`.

Each zip keeps its original name. Inside, the original top folder is unchanged: `2020年7月全国出口/` and `2020年8月全国出口/`. Each of those folders has the national combined CSV at its root, plus `流程CSV/` and `检验文件/`. The packs stay zipped so the national CSVs are not stored as separate files.

September export is incomplete, and October–December export have not started, so those 2020 H2 export months are not in this repository. Import packs are not in this change.
