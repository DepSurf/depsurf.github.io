# Function: <code>rcar_sysc_power</code>

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
int rcar_sysc_power(const struct rcar_sysc_ch * sysc_ch, bool on)
```

```json
{
  "name": "rcar_sysc_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498143680,
      "name": "rcar_sysc_power",
      "external": false,
      "loc": "drivers/soc/renesas/rcar-sysc.c:97",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_on",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_on",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_off",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498143680,
      "name": "rcar_sysc_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int rcar_sysc_power(const struct rcar_sysc_ch * sysc_ch, bool on)
```

```json
{
  "name": "rcar_sysc_power",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230893480,
      "name": "rcar_sysc_power",
      "external": false,
      "loc": "drivers/soc/renesas/rcar-sysc.c:97",
      "file": "drivers/soc/renesas/rcar-sysc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power_cpu",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_on",
        "drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230893480,
      "name": "rcar_sysc_power",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int rcar_sysc_power(const struct rcar_sysc_ch * sysc_ch, bool on)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int rcar_sysc_power(const struct rcar_sysc_ch * sysc_ch, bool on)
```
</details>
</li>
</ul>
