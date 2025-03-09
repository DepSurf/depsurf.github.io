# Function: <code>tegra_read_chipid</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
u32 tegra_read_chipid()
```

```json
{
  "name": "tegra_read_chipid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243843776,
      "name": "tegra_read_chipid",
      "external": true,
      "loc": "drivers/soc/tegra/fuse/tegra-apbmisc.c:28",
      "file": "drivers/soc/tegra/fuse/tegra-apbmisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_revision",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_get_chip_id"
      ],
      "caller_func": [
        "drivers/clk/tegra/clk-periph-gate.c:clk_periph_disable",
        "drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_revision",
        "drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_get_chip_id",
        "drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230901720,
      "name": "tegra_read_chipid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3230901776,
      "name": "tegra_read_chipid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 tegra_read_chipid()
```
</details>
</li>
</ul>
