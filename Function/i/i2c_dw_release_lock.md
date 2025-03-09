# Function: <code>i2c_dw_release_lock</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586340528,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:204",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586340528,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586804992,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:204",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586804992,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587078352,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:216",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587078352,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587238971,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:281",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587239152,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587506075,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506240,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587709211,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587709376,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588578723,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:516",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579152,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588602787,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:516",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588603216,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588486931,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:519",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588487360,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589155376,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:519",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589155808,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590609482,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:516",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590608368,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592270054,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:519",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592268832,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592695446,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:519",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694160,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593441318,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:536",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_fifo_size",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593440032,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500875204,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500875328,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233383892,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233384052,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294337004,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294337184,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277667390,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277667522,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587665355,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587665520,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_release_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587771739,
      "name": "i2c_dw_release_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:295",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771904,
      "name": "i2c_dw_release_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void i2c_dw_release_lock(struct dw_i2c_dev * dev)
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
