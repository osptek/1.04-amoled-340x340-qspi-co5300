<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.04″ AMOLED 340×340 (CO5300 · QSPI)</h1>

<p align="center"><b>Round-ready AMOLED module · QSPI · CO5300</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English</p>

<p align="center">
  <img alt="Size: 1.04 inch" src="https://img.shields.io/badge/Size-1.04%22-3498DB?style=flat-square" />
  <img alt="Resolution: 340x340" src="https://img.shields.io/badge/Resolution-340%C3%97340-8E44AD?style=flat-square" />
  <img alt="Interface: QSPI" src="https://img.shields.io/badge/Interface-QSPI-27AE60?style=flat-square" />
  <img alt="Driver: CO5300" src="https://img.shields.io/badge/Driver-CO5300-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.04&quot; 340×340 AMOLED QSPI module (CO5300) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **1.04″ 340×340 AMOLED** is a **QSPI** color display module driven by **CO5300**, with touch controller **CST820**. The square resolution suits wearables and compact HMI panels.

Spec ID (repository name): `1.04-amoled-340x340-qspi-co5300`

Current module version: **AM104Q340340LK**. Electrical and mechanical details follow [`docs/AM_104_Q340340_LK_2_23736c9875.pdf`](./docs/AM_104_Q340340_LK_2_23736c9875.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 1.04 inch |
| Type | AMOLED (color) |
| Resolution | 340×340 |
| Interface | QSPI |
| Driver IC | CO5300 |
| Touch IC | CST820 |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-S3 · CO5300 QSPI + esp-lvgl-adapter / LVGL8 | [`examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/`](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/) |
| ESP32-S3 · CO5300 QSPI + esp-lvgl-adapter / LVGL9 | [`examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/`](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/) |
| ESP32-S3 · LVGL8 + TE | [`examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/`](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/) |
| ESP32-S3 · LVGL9 + TE | [`examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/`](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/) |

## Repository layout

```text
1.04-amoled-340x340-qspi-co5300/
├── README.md
├── README_EN.md
├── MODULE_VERSION.md
├── LICENSE
├── images/          # README assets
├── docs/            # datasheets, init files
└── examples/        # sample projects
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (AM104Q340340LK) | [`docs/AM_104_Q340340_LK_2_23736c9875.pdf`](./docs/AM_104_Q340340_LK_2_23736c9875.pdf) |
| Board-to-board connector datasheet (OK-23GF024-04) | [`docs/OK-23GF024-04.pdf`](./docs/OK-23GF024-04.pdf) |
| Driver IC datasheet (CO5300) | [`docs/CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf`](./docs/CO_5300_Datasheet_V0_00_20230328_07edb82936.pdf) |
| Touch IC datasheet (CST820) | [`docs/DS_CST_820_V1_2_e0543732ca.pdf`](./docs/DS_CST_820_V1_2_e0543732ca.pdf) |
| Init sequence (text) | [`docs/BOE1.04_340x340_CO5300_QSPI_简码_202401021.txt`](./docs/BOE1.04_340x340_CO5300_QSPI_%E7%AE%80%E7%A0%81_202401021.txt) |

### Samples

- [ESP32-S3 CO5300 QSPI + LVGL8](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/)
- [ESP32-S3 CO5300 QSPI + LVGL9](./examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/)
- [ESP32-S3 LVGL8 + TE](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/)
- [ESP32-S3 LVGL9 + TE](./examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group (China): **985881096**
- Website: <https://osptek.com/>

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
