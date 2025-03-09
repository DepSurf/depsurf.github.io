# Function: <code>i2c_dw_irq_handler_master</code>

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
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586341325,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:558",
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
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586805789,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:558",
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
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587079196,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:564",
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
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587239995,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:572",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 18446744071587507072,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1673
    },
    {
      "addr": 18446744071587511137,
      "name": "i2c_dw_irq_handler_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 18446744071587710208,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1673
    },
    {
      "addr": 18446744071587714253,
      "name": "i2c_dw_irq_handler_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588584784,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:613",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584784,
      "name": "i2c_dw_irq_handler_master.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588608528,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:613",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608528,
      "name": "i2c_dw_irq_handler_master.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588493109,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:718",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589161730,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:718",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590614559,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:714",
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
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500876168,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 18446603336500876168,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
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
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233384884,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 3233384884,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1544
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
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294338160,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 13835058055294338160,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2060
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
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277668250,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 18446743936277668250,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1260
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 18446744071587666352,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1673
    },
    {
      "addr": 18446744071587670397,
      "name": "i2c_dw_irq_handler_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_irq_handler_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_irq_handler_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:577",
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
      "addr": 18446744071587772736,
      "name": "i2c_dw_irq_handler_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1673
    },
    {
      "addr": 18446744071587776781,
      "name": "i2c_dw_irq_handler_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_dw_irq_handler_master(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
