# Function: <code>lookup_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581045929,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1626",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:walk_component"
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581201424,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1626",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201424,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278688,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1622",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278688,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328224,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1625",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328224,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581468464,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1623",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581468464,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626736,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1640",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626736,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713296,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1681",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713296,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830704,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1679",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830704,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903168,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903168,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582138478,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1554",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582185070,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1554",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582207278,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1639",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582525245,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1667",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583047226,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1713",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583612858,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1695",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583832154,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1700",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584038170,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1703",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493383640,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493383640,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226970444,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226970444,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286937712,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286937712,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273099832,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273099832,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581871904,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581871904,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809504,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809504,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863216,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863216,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```

```json
{
  "name": "lookup_slow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934976,
      "name": "lookup_slow",
      "external": false,
      "loc": "fs/namei.c:1674",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_mountpoint",
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:walk_component"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934976,
      "name": "lookup_slow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct dentry * lookup_slow(const struct qstr * name, struct dentry * dir, unsigned int flags)
```
</details>
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
