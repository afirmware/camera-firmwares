# Camera Firmware Collection

此目录用于归档不同摄像头、行车记录仪及小型摄像头相关的固件镜像和资料。文件按原有设备分类目录保存。

> **注意：** 目录名和文件名是现有归档标签，不代表固件型号、硬件修订版或兼容性已经验证。刷写前请确认设备型号、主控和闪存容量，并先备份设备原始内容。错误镜像可能导致设备无法启动。

## 文件目录

| 子目录 | 文件 | 大小 | 备注 |
|---|---|---:|---|
| `car-recorder-8m` | `car-recorder-flash.bin` | 8 MiB | 行车记录仪相关镜像 |
| `lenovo-cam` | `ingenic-t21.bin` | 16 MiB | 文件名标注为 Ingenic T21 相关镜像 |
| `small-camera-no-battery` | `cam-withoutir-small-512k-spi-chip.bin` | 512 KiB | 文件名标注为无电池小摄像头 / 512 KiB SPI 芯片 |
| `small-camera-no-battery` | `cam-withoutir-small-512k-spi-chip2.bin` | 512 KiB | 同类镜像变体 2 |
| `small-camera-no-battery` | `cam-withoutir-small-512k-spi-chip3.bin` | 512 KiB | 同类镜像变体 3 |
| `small-camera-no-battery` | `cam-withoutir-small-512k-spi-chip4.bin` | 512 KiB | 同类镜像变体 4 |
| `small-camera-with-battery` | `cam-512k-spi-chip.bin` | 512 KiB | 文件名标注为带电池小摄像头 / 512 KiB SPI 芯片 |
| `wireless-video-camera` | `tuchuan-cam.bin` | 2 MiB | 无线视频摄像头相关镜像 |

## 使用建议

- 刷写前记录设备标签、主控型号、闪存芯片型号和原始固件版本。
- 将设备原始闪存完整备份，并保留备份文件，不要覆盖唯一副本。
- 对照镜像大小及硬件信息确认兼容性；不要仅依据目录名选择镜像。
- 完成镜像来源、版本和校验值整理后，可在此 README 中补充记录。

## 维护说明

当前清单按目录中的文件名和文件大小整理。固件版本、来源、校验和及对应设备硬件修订版尚未记录。
