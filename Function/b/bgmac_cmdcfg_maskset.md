# Function: <code>bgmac_cmdcfg_maskset</code>

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
void bgmac_cmdcfg_maskset(struct bgmac * bgmac, u32 mask, u32 set, bool force)
```

```json
{
  "name": "bgmac_cmdcfg_maskset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499994376,
      "name": "bgmac_cmdcfg_maskset",
      "external": false,
      "loc": "drivers/net/ethernet/broadcom/bgmac.c:749",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_mac_speed",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_rx_mode",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_rx_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499994376,
      "name": "bgmac_cmdcfg_maskset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void bgmac_cmdcfg_maskset(struct bgmac * bgmac, u32 mask, u32 set, bool force)
```
</details>
</li>
</ul>
