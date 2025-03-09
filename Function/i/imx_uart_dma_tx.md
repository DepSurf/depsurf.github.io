# Function: <code>imx_uart_dma_tx</code>

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
void imx_uart_dma_tx(struct imx_port * sport)
```

```json
{
  "name": "imx_uart_dma_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498653656,
      "name": "imx_uart_dma_tx",
      "external": false,
      "loc": "drivers/tty/serial/imx.c:587",
      "file": "drivers/tty/serial/imx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498653656,
      "name": "imx_uart_dma_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
void imx_uart_dma_tx(struct imx_port * sport)
```

```json
{
  "name": "imx_uart_dma_tx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231283484,
      "name": "imx_uart_dma_tx",
      "external": false,
      "loc": "drivers/tty/serial/imx.c:587",
      "file": "drivers/tty/serial/imx.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/imx.c:imx_uart_int",
        "drivers/tty/serial/imx.c:imx_uart_txint",
        "drivers/tty/serial/imx.c:imx_uart_start_tx",
        "drivers/tty/serial/imx.c:imx_uart_dma_tx_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231283484,
      "name": "imx_uart_dma_tx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
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
void imx_uart_dma_tx(struct imx_port * sport)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void imx_uart_dma_tx(struct imx_port * sport)
```
</details>
</li>
</ul>
