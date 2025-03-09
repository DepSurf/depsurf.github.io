# Function: <code>sdio_get_pending_irqs</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588161439,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sdio_get_pending_irqs(struct mmc_host * host, u8 * pending)
```

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589025792,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589025792,
      "name": "sdio_get_pending_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int sdio_get_pending_irqs(struct mmc_host * host, u8 * pending)
```

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589035456,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589035456,
      "name": "sdio_get_pending_irqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588922991,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589630076,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591129938,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592853138,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593290000,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594046032,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501415976,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233904116,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294984748,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278020718,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587783007,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588115967,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sdio_get_pending_irqs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588233503,
      "name": "sdio_get_pending_irqs",
      "external": false,
      "loc": "drivers/mmc/core/sdio_irq.c:30",
      "file": "drivers/mmc/core/sdio_irq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int sdio_get_pending_irqs(struct mmc_host * host, u8 * pending)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int sdio_get_pending_irqs(struct mmc_host * host, u8 * pending)
```
</details>
</li>
</ul>
