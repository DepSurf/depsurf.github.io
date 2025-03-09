# Function: <code>mmci_write_clkreg</code>

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
void mmci_write_clkreg(struct mmci_host * host, u32 clk)
```

```json
{
  "name": "mmci_write_clkreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501452028,
      "name": "mmci_write_clkreg",
      "external": true,
      "loc": "drivers/mmc/host/mmci.c:327",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/mmci.c:mmci_start_data",
        "drivers/mmc/host/mmci.c:mmci_start_data"
      ],
      "caller_func": [
        "drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_clkreg",
        "drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_clkreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501456424,
      "name": "mmci_write_clkreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void mmci_write_clkreg(struct mmci_host * host, u32 clk)
```

```json
{
  "name": "mmci_write_clkreg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233940560,
      "name": "mmci_write_clkreg",
      "external": true,
      "loc": "drivers/mmc/host/mmci.c:327",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/mmci.c:mmci_set_ios",
        "drivers/mmc/host/mmci.c:mmci_start_data",
        "drivers/mmc/host/mmci.c:mmci_start_data"
      ],
      "caller_func": [
        "drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_clkreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233941112,
      "name": "mmci_write_clkreg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void mmci_write_clkreg(struct mmci_host * host, u32 clk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mmci_write_clkreg(struct mmci_host * host, u32 clk)
```
</details>
</li>
</ul>
