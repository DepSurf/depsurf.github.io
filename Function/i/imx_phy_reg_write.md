# Function: <code>imx_phy_reg_write</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int imx_phy_reg_write(u16 val, void * mmio)
```

```json
{
  "name": "imx_phy_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499820136,
      "name": "imx_phy_reg_write",
      "external": false,
      "loc": "drivers/ata/ahci_imx.c:163",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:read_adc_sum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499820136,
      "name": "imx_phy_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int imx_phy_reg_write(u16 val, void * mmio)
```

```json
{
  "name": "imx_phy_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232275204,
      "name": "imx_phy_reg_write",
      "external": false,
      "loc": "drivers/ata/ahci_imx.c:163",
      "file": "drivers/ata/ahci_imx.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/ahci_imx.c:imx_sata_enable",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:sata_ahci_read_temperature",
        "drivers/ata/ahci_imx.c:read_adc_sum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232275204,
      "name": "imx_phy_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int imx_phy_reg_write(u16 val, void * mmio)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int imx_phy_reg_write(u16 val, void * mmio)
```
</details>
</li>
</ul>
