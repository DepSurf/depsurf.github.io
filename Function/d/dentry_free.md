# Function: <code>dentry_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581086560,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:294",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:__dentry_kill",
        "fs/dcache.c:shrink_dentry_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086560,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581249920,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:302",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249920,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581327712,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:302",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327712,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581381040,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:334",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381040,
      "name": "dentry_free",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581522480,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:334",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522480,
      "name": "dentry_free",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680944,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680944,
      "name": "dentry_free",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767568,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767568,
      "name": "dentry_free",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884608,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071581900016,
      "name": "dentry_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581957840,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581957840,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189600,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189600,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582237072,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237072,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582262816,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:338",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582262816,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580608,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:338",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580608,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583111408,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:363",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583111408,
      "name": "dentry_free",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679200,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:363",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679200,
      "name": "dentry_free",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583897136,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:363",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897136,
      "name": "dentry_free",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103920,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:362",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103920,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493455224,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493455224,
      "name": "dentry_free",
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227022880,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227022880,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287010224,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287010224,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273139072,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273139072,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581926576,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926576,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581864160,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864160,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581917888,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917888,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void dentry_free(struct dentry * dentry)
```

```json
{
  "name": "dentry_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581988736,
      "name": "dentry_free",
      "external": false,
      "loc": "fs/dcache.c:336",
      "file": "fs/dcache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dcache.c:shrink_dentry_list",
        "fs/dcache.c:__dentry_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581988736,
      "name": "dentry_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
