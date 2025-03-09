# Function: <code>i2c_dw_set_timings_master</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587241765,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587510101,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587713237,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:36",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588582496,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071588585309,
      "name": "i2c_dw_set_timings_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:36",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588605984,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071591579670,
      "name": "i2c_dw_set_timings_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:40",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490288,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071591522456,
      "name": "i2c_dw_set_timings_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:40",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589158880,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071592631597,
      "name": "i2c_dw_set_timings_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:40",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590611744,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
    },
    {
      "addr": 18446744071594515128,
      "name": "i2c_dw_set_timings_master.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592272960,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:40",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592272960,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 894
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
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592698384,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:40",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592698384,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593443280,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:41",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593443280,
      "name": "i2c_dw_set_timings_master",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500878992,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233387836,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294340624,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277669806,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587669381,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
  "name": "i2c_dw_set_timings_master",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587775765,
      "name": "i2c_dw_set_timings_master",
      "external": false,
      "loc": "drivers/i2c/busses/i2c-designware-master.c:35",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
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
int i2c_dw_set_timings_master(struct dw_i2c_dev * dev)
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
