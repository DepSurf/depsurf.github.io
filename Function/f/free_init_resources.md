# Function: <code>free_init_resources</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void free_init_resources(struct fman * fman)
```

```json
{
  "name": "free_init_resources",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500045616,
      "name": "free_init_resources",
      "external": false,
      "loc": "drivers/net/ethernet/freescale/fman/fman.c:1215",
      "file": "drivers/net/ethernet/freescale/fman/fman.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe",
        "drivers/net/ethernet/freescale/fman/fman.c:fman_probe"
      ]
    },
    {
      "addr": 18446603336500069304,
      "name": "free_init_resources",
      "external": false,
      "loc": "drivers/net/ethernet/freescale/fman/fman_dtsec.c:832",
      "file": "drivers/net/ethernet/freescale/fman/fman_dtsec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_free",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init"
      ]
    },
    {
      "addr": 18446603336500078136,
      "name": "free_init_resources",
      "external": false,
      "loc": "drivers/net/ethernet/freescale/fman/fman_memac.c:689",
      "file": "drivers/net/ethernet/freescale/fman/fman_memac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_free",
        "drivers/net/ethernet/freescale/fman/fman_memac.c:memac_init"
      ]
    },
    {
      "addr": 18446603336500083336,
      "name": "free_init_resources",
      "external": false,
      "loc": "drivers/net/ethernet/freescale/fman/fman_tgec.c:403",
      "file": "drivers/net/ethernet/freescale/fman/fman_tgec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_free",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init",
        "drivers/net/ethernet/freescale/fman/fman_tgec.c:tgec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500045616,
      "name": "free_init_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336500069304,
      "name": "free_init_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446603336500078136,
      "name": "free_init_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446603336500083336,
      "name": "free_init_resources",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
void free_init_resources(struct fman * fman)
```
</details>
</li>
</ul>
