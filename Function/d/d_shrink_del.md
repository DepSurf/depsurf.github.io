# Function: <code>d_shrink_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581088849,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:406",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581254404,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:377",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581332196,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:377",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581387828,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:409",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581527972,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:409",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list"
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680192,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:408",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680192,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766912,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766912,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883984,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883984,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956352,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956352,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582188848,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582188848,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236352,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236352,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262096,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:419",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262096,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582592968,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:419",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583123150,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:444",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583693726,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:444",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583911611,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:444",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
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
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584117233,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:445",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493455680,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493455680,
      "name": "d_shrink_del",
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227021380,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227021380,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287008736,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287008736,
      "name": "d_shrink_del",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273136912,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273136912,
      "name": "d_shrink_del",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925088,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925088,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862672,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862672,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581916400,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916400,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
```

```json
{
  "name": "d_shrink_del",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986064,
      "name": "d_shrink_del",
      "external": false,
      "loc": "fs/dcache.c:417",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986064,
      "name": "d_shrink_del",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void d_shrink_del(struct dentry * dentry)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void d_shrink_del(struct dentry * dentry)
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
