# Function: <code>__mutex_unlock_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __mutex_unlock_slowpath(atomic_t * lock_count)
```

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373952,
      "name": "__mutex_unlock_slowpath",
      "external": true,
      "loc": "kernel/locking/mutex.c:757",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373952,
      "name": "__mutex_unlock_slowpath",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __mutex_unlock_slowpath(atomic_t * lock_count)
```

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587874784,
      "name": "__mutex_unlock_slowpath",
      "external": true,
      "loc": "kernel/locking/mutex.c:761",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:ww_mutex_unlock",
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587874784,
      "name": "__mutex_unlock_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588086864,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:848",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086864,
      "name": "__mutex_unlock_slowpath.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588313488,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1012",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313488,
      "name": "__mutex_unlock_slowpath.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878976,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1012",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878976,
      "name": "__mutex_unlock_slowpath.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589257456,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1013",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257456,
      "name": "__mutex_unlock_slowpath.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589499744,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1191",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589499744,
      "name": "__mutex_unlock_slowpath.isra.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589960176,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1196",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589960176,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590187840,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590187840,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591204128,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591204128,
      "name": "__mutex_unlock_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591699264,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1225",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591699264,
      "name": "__mutex_unlock_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591641776,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1223",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591641776,
      "name": "__mutex_unlock_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592815520,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:845",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592815520,
      "name": "__mutex_unlock_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594718384,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:901",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594718384,
      "name": "__mutex_unlock_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596468560,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:901",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596468560,
      "name": "__mutex_unlock_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597010368,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:901",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597010368,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597939712,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:906",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:atomic_dec_and_mutex_lock",
        "kernel/locking/mutex.c:ww_mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597939712,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503930304,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503930304,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236541536,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236541536,
      "name": "__mutex_unlock_slowpath.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297781840,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297781840,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279800370,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279800370,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589790128,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589790128,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589512608,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512608,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590233536,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233536,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__mutex_unlock_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590283696,
      "name": "__mutex_unlock_slowpath",
      "external": false,
      "loc": "kernel/locking/mutex.c:1222",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:mutex_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590283696,
      "name": "__mutex_unlock_slowpath.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void __mutex_unlock_slowpath(atomic_t * lock_count)
```
</details>
</li>
</ul>
