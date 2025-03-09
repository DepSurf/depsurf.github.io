# Function: <code>context_to_sid</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583824656,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:57",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583824656,
      "name": "context_to_sid",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946112,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:57",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946112,
      "name": "context_to_sid",
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
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583973104,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:58",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583973104,
      "name": "context_to_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338704,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:58",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338704,
      "name": "context_to_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584959936,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:58",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584959936,
      "name": "context_to_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585673104,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:59",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585673104,
      "name": "context_to_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585902864,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:59",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902864,
      "name": "context_to_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
```

```json
{
  "name": "context_to_sid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586151184,
      "name": "context_to_sid",
      "external": false,
      "loc": "security/selinux/ss/sidtab.c:59",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_context_to_sid",
        "security/selinux/ss/sidtab.c:sidtab_set_initial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586151184,
      "name": "context_to_sid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u32 context_to_sid(struct sidtab * s, struct context * context, u32 hash)
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
