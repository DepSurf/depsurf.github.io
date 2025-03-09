# Function: <code>sidtab_convert_tree</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583186608,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:360",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583186608,
      "name": "sidtab_convert_tree.isra.4",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583373872,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:365",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583373872,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583479824,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583479824,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583825552,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:361",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583825552,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946992,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:361",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946992,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583973984,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:371",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973984,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584339584,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:371",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584339584,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584960464,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:371",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960464,
      "name": "sidtab_convert_tree",
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673664,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:375",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673664,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585903488,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:375",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585903488,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151808,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:375",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151808,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495244984,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495244984,
      "name": "sidtab_convert_tree.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```

```json
{
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228626644,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert",
        "security/selinux/ss/sidtab.c:sidtab_convert_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228626644,
      "name": "sidtab_convert_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289213168,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289213168,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274470458,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274470458,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448560,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448560,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583385632,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583385632,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583432336,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583432336,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
  "name": "sidtab_convert_tree",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583528608,
      "name": "sidtab_convert_tree",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:359",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583528608,
      "name": "sidtab_convert_tree.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
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
int sidtab_convert_tree(union sidtab_entry_inner * edst, union sidtab_entry_inner * esrc, u32 * pos, u32 count, u32 level, struct sidtab_convert_params * convert)
```
</details>
</li>
</ul>
