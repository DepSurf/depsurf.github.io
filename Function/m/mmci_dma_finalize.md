# Function: <code>mmci_dma_finalize</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmci_dma_finalize(struct mmci_host * host, struct mmc_data * data)
```

```json
{
  "name": "mmci_dma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501456052,
      "name": "mmci_dma_finalize",
      "external": true,
      "loc": "drivers/mmc/host/mmci.c:533",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_data_irq"
      ],
      "caller_func": [
        "drivers/mmc/host/mmci.c:mmci_data_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501450672,
      "name": "mmci_dma_finalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446603336501459488,
      "name": "mmci_dma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void mmci_dma_finalize(struct mmci_host * host, struct mmc_data * data)
```

```json
{
  "name": "mmci_dma_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233938412,
      "name": "mmci_dma_finalize",
      "external": true,
      "loc": "drivers/mmc/host/mmci.c:533",
      "file": "drivers/mmc/host/mmci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/mmci.c:mmci_data_irq"
      ],
      "caller_func": [
        "drivers/mmc/host/mmci.c:mmci_data_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233937072,
      "name": "mmci_dma_finalize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 3233943876,
      "name": "mmci_dma_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void mmci_dma_finalize(struct mmci_host * host, struct mmc_data * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void mmci_dma_finalize(struct mmci_host * host, struct mmc_data * data)
```
</details>
</li>
</ul>
