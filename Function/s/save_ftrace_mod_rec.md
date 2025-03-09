# Function: <code>save_ftrace_mod_rec</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580296752,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5881",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296752,
      "name": "save_ftrace_mod_rec.isra.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580357904,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5867",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357904,
      "name": "save_ftrace_mod_rec.isra.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580413968,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5827",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580413968,
      "name": "save_ftrace_mod_rec.isra.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580466912,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5875",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466912,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580515600,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515600,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599952,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6405",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599952,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580589984,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6543",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589984,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580592992,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6548",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580592992,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764160,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6549",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764160,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580981008,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6983",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981008,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277664,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:7099",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277664,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372720,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6914",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372720,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581479520,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:6916",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581479520,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491795416,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491795416,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```

```json
{
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225741884,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225741884,
      "name": "save_ftrace_mod_rec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284848128,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284848128,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272109220,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272109220,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580484400,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484400,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580431728,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431728,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580475648,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475648,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
  "name": "save_ftrace_mod_rec",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580531856,
      "name": "save_ftrace_mod_rec",
      "external": false,
      "loc": "kernel/trace/ftrace.c:5912",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_free_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531856,
      "name": "save_ftrace_mod_rec.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void save_ftrace_mod_rec(struct ftrace_mod_map * mod_map, struct dyn_ftrace * rec)
```
</details>
</li>
</ul>
