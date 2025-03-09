# Function: <code>spi_mem_dirmap_destroy</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586539184,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:545",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539184,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586786720,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586786720,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586932976,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586932976,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587748896,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:547",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747616,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587807616,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:552",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806272,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587687136,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:569",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685792,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588277232,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:570",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275776,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589664080,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:583",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589658432,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591274400,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:583",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591268416,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591629376,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:583",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591623232,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592362192,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:583",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592356096,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499897576,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499897576,
      "name": "spi_mem_dirmap_destroy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232447084,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232447084,
      "name": "spi_mem_dirmap_destroy",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293222240,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293222240,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276995818,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276995818,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586690000,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586690000,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586558336,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586558336,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586887536,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586887536,
      "name": "spi_mem_dirmap_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```

```json
{
  "name": "spi_mem_dirmap_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586993920,
      "name": "spi_mem_dirmap_destroy",
      "external": true,
      "loc": "drivers/spi/spi-mem.c:544",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586993920,
      "name": "spi_mem_dirmap_destroy",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc * desc)
```
</details>
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
