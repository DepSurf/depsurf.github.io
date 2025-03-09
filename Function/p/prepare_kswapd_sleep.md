# Function: <code>prepare_kswapd_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580573723,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3038",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643344,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3102",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643344,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580710416,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3113",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580710416,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580745040,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3204",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580745040,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580832256,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3228",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832256,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580969264,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3237",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969264,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581046000,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3448",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046000,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581108512,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3406",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108512,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581165504,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165504,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581352096,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3466",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352096,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581395040,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3464",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395040,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581414448,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3662",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414448,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581665920,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3819",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665920,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582039936,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3965",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582039936,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582489824,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:6906",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582489824,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582704176,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:7270",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582704176,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int highest_zoneidx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873696,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:6637",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873696,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492547856,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492547856,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226408212,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226408212,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285843680,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285843680,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272593524,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272593524,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581134352,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134352,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581081296,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081296,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581125552,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125552,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```

```json
{
  "name": "prepare_kswapd_sleep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581188064,
      "name": "prepare_kswapd_sleep",
      "external": false,
      "loc": "mm/vmscan.c:3492",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188064,
      "name": "prepare_kswapd_sleep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool prepare_kswapd_sleep(pg_data_t * pgdat, int order, int classzone_idx)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
</li>
</ul>
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
