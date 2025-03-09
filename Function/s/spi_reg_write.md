# Function: <code>spi_reg_write</code>

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
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "spi_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499267120,
      "name": "spi_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:28",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe-spi.c:spi_init",
        "drivers/mfd/stmpe-spi.c:spi_block_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499267160,
      "name": "spi_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "spi_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231783432,
      "name": "spi_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:28",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/stmpe-spi.c:spi_init",
        "drivers/mfd/stmpe-spi.c:spi_block_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231783432,
      "name": "spi_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "spi_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292454656,
      "name": "spi_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:28",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe-spi.c:spi_init",
        "drivers/mfd/stmpe-spi.c:spi_block_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292454704,
      "name": "spi_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "spi_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276524354,
      "name": "spi_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:28",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/stmpe-spi.c:spi_init",
        "drivers/mfd/stmpe-spi.c:spi_block_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276524386,
      "name": "spi_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int spi_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
</ul>
