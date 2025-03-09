# Function: <code>crypto_scomp_free_scratches</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void crypto_scomp_free_scratches(void * * scratches)
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016944,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:72",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016944,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583068679,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:73",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ],
      "caller_func": [
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068432,
      "name": "crypto_scomp_free_scratches.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583235153,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235008,
      "name": "crypto_scomp_free_scratches.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583443393,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583443248,
      "name": "crypto_scomp_free_scratches.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583565377,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:65",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565232,
      "name": "crypto_scomp_free_scratches.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583753696,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583753696,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583863408,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583863408,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584253504,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584253504,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584372192,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_alloc_scratches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584372192,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584406656,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406656,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584801888,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584801888,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585491440,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585491440,
      "name": "crypto_scomp_free_scratches",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586254528,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586254528,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586494896,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:61",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494896,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764944,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:61",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764944,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495680536,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495680536,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229031952,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229031952,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289823952,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289823952,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274829816,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274829816,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583832144,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832144,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583769200,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769200,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583815904,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583815904,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void crypto_scomp_free_scratches()
```

```json
{
  "name": "crypto_scomp_free_scratches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916976,
      "name": "crypto_scomp_free_scratches",
      "external": false,
      "loc": "crypto/scompress.c:68",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:crypto_exit_scomp_ops_async",
        "crypto/scompress.c:crypto_scomp_init_tfm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916976,
      "name": "crypto_scomp_free_scratches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void crypto_scomp_free_scratches(void * * scratches)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void crypto_scomp_free_scratches(void * * scratches)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void crypto_scomp_free_scratches()
```
</details>
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
