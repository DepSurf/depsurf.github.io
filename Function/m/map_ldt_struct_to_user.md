# Function: <code>map_ldt_struct_to_user</code>

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
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579059514,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:180",
      "file": "arch/x86/kernel/ldt.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579067033,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:180",
      "file": "arch/x86/kernel/ldt.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579069392,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:180",
      "file": "arch/x86/kernel/ldt.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579075872,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579075872,
      "name": "map_ldt_struct_to_user",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078352,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078352,
      "name": "map_ldt_struct_to_user",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085248,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085248,
      "name": "map_ldt_struct_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108256,
      "name": "map_ldt_struct_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446744071592053899,
      "name": "map_ldt_struct_to_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139248,
      "name": "map_ldt_struct_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071593820743,
      "name": "map_ldt_struct_to_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183504,
      "name": "map_ldt_struct_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071595958575,
      "name": "map_ldt_struct_to_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187456,
      "name": "map_ldt_struct_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071596475977,
      "name": "map_ldt_struct_to_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
```

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:264",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216672,
      "name": "map_ldt_struct_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071597371742,
      "name": "map_ldt_struct_to_user.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579069744,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:180",
      "file": "arch/x86/kernel/ldt.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579002433,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:180",
      "file": "arch/x86/kernel/ldt.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579069328,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:180",
      "file": "arch/x86/kernel/ldt.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_ldt_struct_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579073166,
      "name": "map_ldt_struct_to_user",
      "external": false,
      "loc": "arch/x86/kernel/ldt.c:180",
      "file": "arch/x86/kernel/ldt.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void map_ldt_struct_to_user(struct mm_struct * mm)
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
