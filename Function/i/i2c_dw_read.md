# Function: <code>i2c_dw_read</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586341807,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:362",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586806271,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:362",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587079865,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:367",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587240748,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587508291,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587711427,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588580864,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:407",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580864,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588604656,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:407",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588604656,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588488784,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:502",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588488784,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157376,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:502",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157376,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590610176,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:502",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590610176,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592270752,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:502",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592270752,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592696144,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:564",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592696144,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
void i2c_dw_read(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593446288,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:578",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593446288,
      "name": "i2c_dw_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500876608,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233385968,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294339572,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277669134,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587667571,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
  "name": "i2c_dw_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587773955,
      "name": "i2c_dw_read",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:371",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master"
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
void i2c_dw_read(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
