# Function: <code>hsu_dma_do_irq</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int hsu_dma_do_irq(struct hsu_dma_chip * chip, short unsigned int nr, u32 status)
```

```json
{
  "name": "hsu_dma_do_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589361504,
      "name": "hsu_dma_do_irq",
      "external": true,
      "loc": "drivers/dma/hsu/hsu.c:210",
      "file": "drivers/dma/hsu/hsu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589361504,
      "name": "hsu_dma_do_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int hsu_dma_do_irq(struct hsu_dma_chip * chip, short unsigned int nr, u32 status)
```

```json
{
  "name": "hsu_dma_do_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589660144,
      "name": "hsu_dma_do_irq",
      "external": true,
      "loc": "drivers/dma/hsu/hsu.c:210",
      "file": "drivers/dma/hsu/hsu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589660144,
      "name": "hsu_dma_do_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int hsu_dma_do_irq(struct hsu_dma_chip * chip, short unsigned int nr, u32 status)
```

```json
{
  "name": "hsu_dma_do_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589970624,
      "name": "hsu_dma_do_irq",
      "external": true,
      "loc": "drivers/dma/hsu/hsu.c:210",
      "file": "drivers/dma/hsu/hsu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:dnv_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq",
        "drivers/tty/serial/8250/8250_mid.c:tng_handle_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589970624,
      "name": "hsu_dma_do_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int hsu_dma_do_irq(struct hsu_dma_chip * chip, short unsigned int nr, u32 status)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
