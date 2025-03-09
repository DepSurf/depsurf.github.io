# Function: <code>check_conflicting_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581343820,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1582",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581523983,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1608",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int check_conflicting_open(const struct dentry * dentry, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598736,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1641",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598736,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int check_conflicting_open(const struct dentry * dentry, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659712,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1641",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659712,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
int check_conflicting_open(const struct dentry * dentry, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805584,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1651",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805584,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int check_conflicting_open(const struct dentry * dentry, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977600,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1649",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977600,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582074878,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1766",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226800,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1772",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226800,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582326464,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582326464,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582615856,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1803",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582615856,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582688272,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1804",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582688272,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582718160,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1804",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582718160,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583045056,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1707",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045056,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583520976,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1682",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583520976,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120272,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1668",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120272,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584354848,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1669",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584354848,
      "name": "check_conflicting_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584573184,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1683",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:generic_add_lease",
        "fs/locks.c:generic_add_lease"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573184,
      "name": "check_conflicting_open.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493907864,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493907864,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227386128,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227386128,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287546848,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287546848,
      "name": "check_conflicting_open",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273463436,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273463436,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582295200,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295200,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232960,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232960,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285680,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285680,
      "name": "check_conflicting_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
int check_conflicting_open(struct file * filp, const long int arg, int flags)
```

```json
{
  "name": "check_conflicting_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582364544,
      "name": "check_conflicting_open",
      "external": false,
      "loc": "fs/locks.c:1800",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582364544,
      "name": "check_conflicting_open",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int check_conflicting_open(const struct dentry * dentry, const long int arg, int flags)
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int check_conflicting_open(const struct dentry * dentry, const long int arg, int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int check_conflicting_open(struct file * filp, const long int arg, int flags)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int check_conflicting_open(struct file * filp, const long int arg, int flags)
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
