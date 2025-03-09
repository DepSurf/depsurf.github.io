# Function: <code>lookup_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581051362,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:2950",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581212041,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3078",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581289578,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3042",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581338838,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3093",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581479876,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3091",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write, int * opened)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581638080,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3113",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:path_openat",
        "fs/namei.c:path_openat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581638080,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1836
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581727575,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3127",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:path_openat"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3125",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844112,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1703
    },
    {
      "addr": 18446744071581859031,
      "name": "lookup_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581916576,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916576,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582145312,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3003",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145312,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582191552,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3009",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191552,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582218128,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3119",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218128,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582536224,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3186",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582536224,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1471
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583049296,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3280",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583049296,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1527
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583614896,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3318",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614896,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1581
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583825936,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3397",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825936,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1445
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
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584032048,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3405",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:open_last_lookups",
        "fs/namei.c:open_last_lookups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584032048,
      "name": "lookup_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1379
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493397392,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493397392,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1740
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226983216,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226983216,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1788
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286952976,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286952976,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2076
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273110586,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273110586,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1298
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581885312,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581885312,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822912,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822912,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581876624,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581876624,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1752
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```

```json
{
  "name": "lookup_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946128,
      "name": "lookup_open",
      "external": false,
      "loc": "fs/namei.c:3118",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946128,
      "name": "lookup_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1748
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
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write, int * opened)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write, int * opened)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int lookup_open(struct nameidata * nd, struct path * path, struct file * file, const struct open_flags * op, bool got_write)
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
