# Function: <code>calc_lcoefs</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584154928,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154928,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584548576,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:779",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548576,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659584,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:866",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659584,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687872,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:866",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687872,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110656,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:866",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110656,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585840112,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:865",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840112,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586620864,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:862",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620864,
      "name": "calc_lcoefs",
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586879168,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:868",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879168,
      "name": "calc_lcoefs",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587157120,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:868",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157120,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496004960,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496004960,
      "name": "calc_lcoefs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229344448,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229344448,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290237888,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290237888,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275101436,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275101436,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584123664,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123664,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584059328,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059328,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584107424,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107424,
      "name": "calc_lcoefs",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```

```json
{
  "name": "calc_lcoefs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584211392,
      "name": "calc_lcoefs",
      "external": false,
      "loc": "block/blk-iocost.c:781",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_refresh_params",
        "block/blk-iocost.c:ioc_refresh_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211392,
      "name": "calc_lcoefs",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void calc_lcoefs(u64 bps, u64 seqiops, u64 randiops, u64 * page, u64 * seqio, u64 * randio)
```
</details>
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
