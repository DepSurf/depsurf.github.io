# Function: <code>spi_mem_default_supports_op</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586397664,
      "name": "spi_mem_default_supports_op",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:129",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586397664,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586539952,
      "name": "spi_mem_default_supports_op",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539952,
      "name": "spi_mem_default_supports_op",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586787184,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586787184,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586933440,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586933440,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587748960,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:140",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748960,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587807680,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:140",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807680,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587688922,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:172",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587687440,
      "name": "spi_mem_default_supports_op",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588279201,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:173",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_exec_op"
      ],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277536,
      "name": "spi_mem_default_supports_op",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:164",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594421828,
      "name": "spi_mem_default_supports_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589659648,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:164",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596266587,
      "name": "spi_mem_default_supports_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591269776,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:164",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596794648,
      "name": "spi_mem_default_supports_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591624592,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:164",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_exec_op",
        "drivers/spi/spi-mem.c:spi_mem_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597717670,
      "name": "spi_mem_default_supports_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071592357456,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499898456,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499898456,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232447808,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232447808,
      "name": "spi_mem_default_supports_op",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293223328,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293223328,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276996584,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276996584,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586690464,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586690464,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586558800,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586558800,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586888000,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888000,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_default_supports_op",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586994384,
      "name": "spi_mem_default_supports_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:138",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_internal_supports_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586994384,
      "name": "spi_mem_default_supports_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool spi_mem_default_supports_op(struct spi_mem * mem, const struct spi_mem_op * op)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
