# Function: <code>spi_alloc_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct spi_master * spi_alloc_master(struct device * dev, unsigned int size)
```

```json
{
  "name": "spi_alloc_master",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585043472,
      "name": "spi_alloc_master",
      "external": true,
      "loc": "drivers/spi/spi.c:1693",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043472,
      "name": "spi_alloc_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct spi_master * spi_alloc_master(struct device * dev, unsigned int size)
```

```json
{
  "name": "spi_alloc_master",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585430256,
      "name": "spi_alloc_master",
      "external": true,
      "loc": "drivers/spi/spi.c:1782",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585430256,
      "name": "spi_alloc_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct spi_master * spi_alloc_master(struct device * dev, unsigned int size)
```

```json
{
  "name": "spi_alloc_master",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585631200,
      "name": "spi_alloc_master",
      "external": true,
      "loc": "drivers/spi/spi.c:1809",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585631200,
      "name": "spi_alloc_master",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "spi_alloc_master",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499903448,
      "name": "spi_alloc_master",
      "external": false,
      "loc": "include/linux/spi/spi.h:654",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499911312,
      "name": "spi_alloc_master",
      "external": false,
      "loc": "include/linux/spi/spi.h:654",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "spi_alloc_master",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232453420,
      "name": "spi_alloc_master",
      "external": false,
      "loc": "include/linux/spi/spi.h:654",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232463560,
      "name": "spi_alloc_master",
      "external": false,
      "loc": "include/linux/spi/spi.h:654",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "spi_alloc_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293231656,
      "name": "spi_alloc_master",
      "external": false,
      "loc": "include/linux/spi/spi.h:654",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "spi_alloc_master",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277003640,
      "name": "spi_alloc_master",
      "external": false,
      "loc": "include/linux/spi/spi.h:654",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277004976,
      "name": "spi_alloc_master",
      "external": false,
      "loc": "include/linux/spi/spi.h:654",
      "file": "drivers/spi/spi-sifive.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-sifive.c:sifive_spi_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct spi_master * spi_alloc_master(struct device * dev, unsigned int size)
```
</details>
</li>
</ul>
