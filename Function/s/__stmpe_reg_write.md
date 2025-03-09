# Function: <code>__stmpe_reg_write</code>

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
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "__stmpe_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499260072,
      "name": "__stmpe_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe.c:70",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/stmpe.c:stmpe_reg_write",
        "drivers/mfd/stmpe.c:__stmpe_set_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499260072,
      "name": "__stmpe_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "__stmpe_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231777480,
      "name": "__stmpe_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe.c:70",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/stmpe.c:stmpe_reg_write",
        "drivers/mfd/stmpe.c:__stmpe_set_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231777480,
      "name": "__stmpe_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "__stmpe_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292445776,
      "name": "__stmpe_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe.c:70",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/stmpe.c:stmpe_reg_write",
        "drivers/mfd/stmpe.c:__stmpe_set_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292445776,
      "name": "__stmpe_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```

```json
{
  "name": "__stmpe_reg_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276518354,
      "name": "__stmpe_reg_write",
      "external": false,
      "loc": "drivers/mfd/stmpe.c:70",
      "file": "drivers/mfd/stmpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/stmpe.c:stmpe_reg_write",
        "drivers/mfd/stmpe.c:__stmpe_set_bits"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276518354,
      "name": "__stmpe_reg_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int __stmpe_reg_write(struct stmpe * stmpe, u8 reg, u8 val)
```
</details>
</li>
</ul>
