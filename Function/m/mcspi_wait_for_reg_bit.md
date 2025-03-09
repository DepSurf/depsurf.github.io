# Function: <code>mcspi_wait_for_reg_bit</code>

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
int mcspi_wait_for_reg_bit(void * reg, long unsigned int bit)
```

```json
{
  "name": "mcspi_wait_for_reg_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499908384,
      "name": "mcspi_wait_for_reg_bit",
      "external": false,
      "loc": "drivers/spi/spi-omap2-mcspi.c:349",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499908384,
      "name": "mcspi_wait_for_reg_bit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int mcspi_wait_for_reg_bit(void * reg, long unsigned int bit)
```

```json
{
  "name": "mcspi_wait_for_reg_bit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232456672,
      "name": "mcspi_wait_for_reg_bit",
      "external": false,
      "loc": "drivers/spi/spi-omap2-mcspi.c:349",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_pio",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_txrx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232456672,
      "name": "mcspi_wait_for_reg_bit",
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
int mcspi_wait_for_reg_bit(void * reg, long unsigned int bit)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int mcspi_wait_for_reg_bit(void * reg, long unsigned int bit)
```
</details>
</li>
</ul>
