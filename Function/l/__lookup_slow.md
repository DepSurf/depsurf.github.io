# Function: <code>__lookup_slow</code>

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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626400,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1601",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626400,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581712960,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712960,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830352,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1640",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830352,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902816,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902816,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132336,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1517",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132336,
      "name": "__lookup_slow",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178832,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1517",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178832,
      "name": "__lookup_slow",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582203680,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1602",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582203680,
      "name": "__lookup_slow",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521456,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1630",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521456,
      "name": "__lookup_slow",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583041712,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1676",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583041712,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583606560,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1658",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583606560,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583827408,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1663",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583827408,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033456,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1666",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033456,
      "name": "__lookup_slow",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493383216,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493383216,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226970076,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226970076,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286937104,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286937104,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273099492,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273099492,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871552,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871552,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809152,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809152,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862864,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862864,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "__lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934624,
      "name": "__lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1635",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:lookup_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934624,
      "name": "__lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
struct dentry * __lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
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
