# Function: <code>tps65217_reg_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tps65217_reg_read(struct tps65217 * tps, unsigned int reg, unsigned int * val)
```

```json
{
  "name": "tps65217_reg_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584634224,
      "name": "tps65217_reg_read",
      "external": true,
      "loc": "drivers/mfd/tps65217.c:55",
      "file": "drivers/mfd/tps65217.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/tps65217.c:tps65217_update_bits"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634224,
      "name": "tps65217_reg_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int tps65217_reg_read(struct tps65217 * tps, unsigned int reg, unsigned int * val)
```

```json
{
  "name": "tps65217_reg_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231855380,
      "name": "tps65217_reg_read",
      "external": true,
      "loc": "drivers/mfd/tps65217.c:198",
      "file": "drivers/mfd/tps65217.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/tps65217.c:tps65217_probe",
        "drivers/mfd/tps65217.c:tps65217_update_bits",
        "drivers/mfd/tps65217.c:tps65217_irq_thread"
      ],
      "caller_func": [
        "drivers/regulator/tps65217-regulator.c:tps65217_regulator_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231854068,
      "name": "tps65217_reg_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int tps65217_reg_read(struct tps65217 * tps, unsigned int reg, unsigned int * val)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int tps65217_reg_read(struct tps65217 * tps, unsigned int reg, unsigned int * val)
```
</details>
</li>
</ul>
