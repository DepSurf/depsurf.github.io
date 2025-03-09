# Function: <code>i2c_dw_prepare_clk</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587077696,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:187",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077696,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587237968,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587237968,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587504992,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587504992,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587708128,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708128,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588577888,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:473",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577888,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588601952,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:473",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588601952,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588486064,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:476",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588486064,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589154496,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:476",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589154496,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590606912,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:476",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590606912,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592267072,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:479",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592267072,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592692384,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:479",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592692384,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593438032,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:496",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_runtime_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593438032,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500873672,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500873672,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233382640,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233382640,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294335200,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294335200,
      "name": "i2c_dw_prepare_clk",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277666044,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277666044,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587664272,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664272,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```

```json
{
  "name": "i2c_dw_prepare_clk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587770656,
      "name": "i2c_dw_prepare_clk",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:252",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_prepare_recovery",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_resume",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587770656,
      "name": "i2c_dw_prepare_clk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```
</details>
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
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_dw_prepare_clk(struct dw_i2c_dev * dev, bool prepare)
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
