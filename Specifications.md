# Tiansuan Satellite Specifications 

## BUPT-1 

BUPT-1 is the first flagship satellite of the Tiansuan Constellation. For more information, visit [Tiansuan Official Website about BUPT-1](http://www.tiansuan.org.cn/sate-b1.html).

### Key Parameters

| Parameter              | Value                                   |
|------------------------|-----------------------------------------|
| ORCID                  | 55261                                   |
| Orbit                  | Sun-synchronous Orbit                   |
| Orbital Altitude       | 487.607 km to 494.651 km                |
| Orbital Inclination    | 97.3710°                                |
| Mass                   | 17.44 kg                                |
| Volume                 | 434.5 mm x 346.6 mm x 340.8 mm          |
| Internal Thermal Range | -10℃ to 30℃                             |
| Solar Panel Size       | 1199.3 mm x 868.4 mm x 423.4 mm         |
| Battery Capacity       | 115 Wh x 2                              |
| TT&C                   | 4.8 kbps uplink, 9.6 kbps downlink      |
| Data Transmission      | 1 Mbps uplink, 100 Mbps downlink        |

### Hardware & OS

On BUPT-1, we have 2x Raspberry Pi 4B (8GB version) and 2x Atlas 200 DK as the computing payload (More details on [Raspberry Pi 4B](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/specifications/) and [Atlas 200 DK](https://e.huawei.com/en/products/computing/ascend/atlas-200) Specifications) with docker installed. The OS used is Ubuntu Server 20.04 for Pi (which can be found at [old ubuntu releases](https://cdimage.ubuntu.com/releases/20.04/release/)) and Ubuntu 18.04 for Atlas 200 DK.
 
 
## BUPT-2/3
BUPT-2/3 plan to be launch at the end of 2024. On BUPT-2/3, Besides Raspberry Pi 4B, we have customized a SoC for improved computing/IO capability. The core parameters are:
- Board CPU: Feiteng D2000
- Memory: 32GB
- Storage: 512GB
- Computing Accelerator: 22TFLOPS

We plan to use Ubuntu Server 22.04 for now which might be changed if there are some untackleable issues. In addition, BUPT-2/3 also have improved the uplink capability to about 5mbps and better transmission layer protocol support.
