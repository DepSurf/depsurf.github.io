# Function: <code>d_lru_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581088100,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:390",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581253655,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:361",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581331447,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:361",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/dcache.c:dput"
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
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581387114,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:393",
      "file": "fs/dcache.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581527232,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:393",
      "file": "fs/dcache.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680768,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:392",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680768,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767376,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767376,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884416,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884416,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581956784,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581956784,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189312,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189312,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236784,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236784,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262528,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:399",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262528,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580320,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:399",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580320,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583110816,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:424",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110816,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678784,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:424",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678784,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583896448,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:424",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583896448,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104096,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:423",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104096,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493457936,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493457936,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227021884,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227021884,
      "name": "d_lru_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287008912,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287008912,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273137456,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273137456,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581925520,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925520,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863104,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863104,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581916832,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581916832,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
```

```json
{
  "name": "d_lru_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581986752,
      "name": "d_lru_add",
      "external": false,
      "loc": "fs/dcache.c:397",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:dput_to_list",
        "fs/dcache.c:dput",
        "fs/dcache.c:dput"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581986752,
      "name": "d_lru_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void d_lru_add(struct dentry * dentry)
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
