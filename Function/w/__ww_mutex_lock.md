# Function: <code>__ww_mutex_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587373440,
      "name": "__ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:914",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373440,
      "name": "__ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int __ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587874272,
      "name": "__ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:918",
      "file": "kernel/locking/mutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587874272,
      "name": "__ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```

```json
{
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588090656,
      "name": "__ww_mutex_lock",
      "external": true,
      "loc": "kernel/locking/mutex.c:1018",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588086784,
      "name": "__ww_mutex_lock.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071588090656,
      "name": "__ww_mutex_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588315552,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:897",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315552,
      "name": "__ww_mutex_lock.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1704
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588881024,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:897",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588881024,
      "name": "__ww_mutex_lock.isra.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1635
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589257936,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:898",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257936,
      "name": "__ww_mutex_lock.isra.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1629
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589500224,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1076",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589500224,
      "name": "__ww_mutex_lock.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1867
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589960560,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1081",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589960560,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2029
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590188224,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590188224,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2029
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591204544,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591204544,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1898
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591699680,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1110",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591699680,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1947
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591643840,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1108",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591643840,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2079
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592817488,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:733",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592817488,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1928
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594718960,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:751",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594718960,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2673
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596469200,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:751",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596469200,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2663
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597013456,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:751",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597013456,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2523
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597942800,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:756",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597942800,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2523
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503932912,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503932912,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2180
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236542356,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236542356,
      "name": "__ww_mutex_lock.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2096
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297785424,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297785424,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2940
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279800792,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279800792,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1302
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589790512,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589790512,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2029
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589512992,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589512992,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2029
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590233920,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590233920,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2029
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
  "name": "__ww_mutex_lock",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590285920,
      "name": "__ww_mutex_lock",
      "external": false,
      "loc": "kernel/locking/mutex.c:1107",
      "file": "kernel/locking/mutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath",
        "kernel/locking/mutex.c:__ww_mutex_lock_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590285920,
      "name": "__ww_mutex_lock.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2048
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int __ww_mutex_lock(struct ww_mutex * lock, struct ww_acquire_ctx * ctx)
```
</details>
</li>
</ul>
