# Function: <code>i2c_dw_acquire_lock</code>

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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586340448,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:188",
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
      "addr": 18446744071586340448,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586804912,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:188",
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
      "addr": 18446744071586804912,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587078272,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:200",
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
      "addr": 18446744071587078272,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587238544,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:265",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587238544,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587506814,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587505680,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587709950,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587708816,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588578277,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:500",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580203,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588579088,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588602341,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:500",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591579534,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588603152,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588486453,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:503",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591522287,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588487296,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589154885,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:503",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_init_regmap"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592631529,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589155744,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590609422,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:500",
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
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594515009,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590608288,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592269998,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:503",
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
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592268720,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592695390,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:503",
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
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694032,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593441262,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:520",
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
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_set_timings_master"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593439904,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500874736,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500874736,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233383404,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233383404,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294336352,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294336352,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277667010,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277667010,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666094,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587664960,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```

```json
{
  "name": "i2c_dw_acquire_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_dw_acquire_lock",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:279",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772478,
      "name": "i2c_dw_acquire_lock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587771344,
      "name": "i2c_dw_acquire_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
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
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_dw_acquire_lock(struct dw_i2c_dev * dev)
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
