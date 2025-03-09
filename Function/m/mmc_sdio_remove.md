# Function: <code>mmc_sdio_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585962800,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:792",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_detect",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962800,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586368256,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:790",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586368256,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586572688,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:790",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586572688,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586697520,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:808",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697520,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587182256,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:808",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587182256,
      "name": "mmc_sdio_remove",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587482384,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:835",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482384,
      "name": "mmc_sdio_remove",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587662496,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:835",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587662496,
      "name": "mmc_sdio_remove",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587940816,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940816,
      "name": "mmc_sdio_remove",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588146688,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588146688,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589016923,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:864",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012336,
      "name": "mmc_sdio_remove",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589026475,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:908",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021872,
      "name": "mmc_sdio_remove",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588913482,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:908",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588908432,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589620188,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:910",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589614768,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591118751,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:912",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591113648,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592840782,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:926",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592835312,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593277432,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:926",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593271952,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594033368,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:926",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594027856,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501399464,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501399464,
      "name": "mmc_sdio_remove",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233888476,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233888476,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294963744,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294963744,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278006966,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_detect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278006966,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587768256,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587768256,
      "name": "mmc_sdio_remove",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588101216,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101216,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void mmc_sdio_remove(struct mmc_host * host)
```

```json
{
  "name": "mmc_sdio_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588218752,
      "name": "mmc_sdio_remove",
      "external": false,
      "loc": "drivers/mmc/core/sdio.c:852",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218752,
      "name": "mmc_sdio_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void mmc_sdio_remove(struct mmc_host * host)
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
