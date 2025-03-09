# Function: <code>spi_mem_exec_op</code>

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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586398016,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:190",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586398016,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586540864,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586540864,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1053
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586788240,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586788240,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586934496,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934496,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587749168,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:275",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749168,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1178
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807920,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:282",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807920,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587688048,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:298",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587688048,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:299",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592542513,
      "name": "spi_mem_exec_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071588278144,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1835
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:312",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594421870,
      "name": "spi_mem_exec_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071589659968,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1818
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:312",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596266629,
      "name": "spi_mem_exec_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071591270112,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1842
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:312",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596794690,
      "name": "spi_mem_exec_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071591624928,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1976
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:312",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_poll_status",
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597717712,
      "name": "spi_mem_exec_op.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071592357792,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1877
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499899648,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499899648,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232448676,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232448676,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293224416,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293224416,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276997588,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_no_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276997588,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691520,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691520,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586559856,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586559856,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586889056,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586889056,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
```

```json
{
  "name": "spi_mem_exec_op",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586995440,
      "name": "spi_mem_exec_op",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:273",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write",
        "drivers/spi/spi-mem.c:spi_mem_dirmap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586995440,
      "name": "spi_mem_exec_op",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1087
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
int spi_mem_exec_op(struct spi_mem * mem, const struct spi_mem_op * op)
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
