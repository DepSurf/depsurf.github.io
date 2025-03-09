# Function: <code>brcm_sata_phy_wr</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void brcm_sata_phy_wr(void * pcb_base, u32 bank, u32 ofs, u32 msk, u32 value)
```

```json
{
  "name": "brcm_sata_phy_wr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496489272,
      "name": "brcm_sata_phy_wr",
      "external": false,
      "loc": "drivers/phy/broadcom/phy-brcm-sata.c:202",
      "file": "drivers/phy/broadcom/phy-brcm-sata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_calibrate",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init",
        "drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496489272,
      "name": "brcm_sata_phy_wr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
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
void brcm_sata_phy_wr(void * pcb_base, u32 bank, u32 ofs, u32 msk, u32 value)
```
</details>
</li>
</ul>
