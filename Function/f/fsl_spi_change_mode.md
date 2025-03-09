# Function: <code>fsl_spi_change_mode</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fsl_spi_change_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499904192,
      "name": "fsl_spi_change_mode",
      "external": false,
      "loc": "drivers/spi/spi-fsl-spi.c:89",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499904192,
      "name": "fsl_spi_change_mode.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void fsl_spi_change_mode(struct spi_device * spi)
```

```json
{
  "name": "fsl_spi_change_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232451452,
      "name": "fsl_spi_change_mode",
      "external": false,
      "loc": "drivers/spi/spi-fsl-spi.c:89",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232451452,
      "name": "fsl_spi_change_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void fsl_spi_change_mode(struct spi_device * spi)
```

```json
{
  "name": "fsl_spi_change_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293230032,
      "name": "fsl_spi_change_mode",
      "external": false,
      "loc": "drivers/spi/spi-fsl-spi.c:89",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293230032,
      "name": "fsl_spi_change_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void fsl_spi_change_mode(struct spi_device * spi)
```

```json
{
  "name": "fsl_spi_change_mode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277000456,
      "name": "fsl_spi_change_mode",
      "external": false,
      "loc": "drivers/spi/spi-fsl-spi.c:89",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-fsl-spi.c:fsl_spi_setup_transfer",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_chipselect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277000456,
      "name": "fsl_spi_change_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void fsl_spi_change_mode(struct spi_device * spi)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void fsl_spi_change_mode(struct spi_device * spi)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void fsl_spi_change_mode(struct spi_device * spi)
```
</details>
</li>
</ul>
