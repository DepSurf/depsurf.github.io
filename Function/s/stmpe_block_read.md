# Function: <code>stmpe_block_read</code>

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
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```

```json
{
  "name": "stmpe_block_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499261224,
      "name": "stmpe_block_read",
      "external": true,
      "loc": "drivers/mfd/stmpe.c:222",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499261224,
      "name": "stmpe_block_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```

```json
{
  "name": "stmpe_block_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231778320,
      "name": "stmpe_block_read",
      "external": true,
      "loc": "drivers/mfd/stmpe.c:222",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231778320,
      "name": "stmpe_block_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```

```json
{
  "name": "stmpe_block_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292447072,
      "name": "stmpe_block_read",
      "external": true,
      "loc": "drivers/mfd/stmpe.c:222",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_irq",
        "drivers/mfd/stmpe.c:stmpe_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292447072,
      "name": "stmpe_block_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```

```json
{
  "name": "stmpe_block_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276519330,
      "name": "stmpe_block_read",
      "external": true,
      "loc": "drivers/mfd/stmpe.c:222",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-stmpe.c:stmpe_gpio_irq",
        "drivers/mfd/stmpe.c:stmpe_probe",
        "drivers/mfd/stmpe.c:stmpe_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276519330,
      "name": "stmpe_block_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int stmpe_block_read(struct stmpe * stmpe, u8 reg, u8 length, u8 * values)
```
</details>
</li>
</ul>
