# Function: <code>pti_clone_p4d</code>

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
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602722550,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:315",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602894908,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:364",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604692272,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:422",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604792168,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:416",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604817930,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:418",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609155724,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:418",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609155724,
      "name": "pti_clone_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612226219,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:417",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612226219,
      "name": "pti_clone_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614367045,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:417",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614367045,
      "name": "pti_clone_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 75
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
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615298579,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:417",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615298579,
      "name": "pti_clone_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 65
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
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617078543,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:417",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617078543,
      "name": "pti_clone_p4d",
      "section": ".init.text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627732080,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:417",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627732080,
      "name": "pti_clone_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619491312,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:417",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619491312,
      "name": "pti_clone_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
void pti_clone_p4d(long unsigned int addr)
```

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621788304,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:417",
      "file": "arch/x86/mm/pti.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621788304,
      "name": "pti_clone_p4d",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604731810,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:418",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604699540,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:418",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604809377,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:418",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pti_clone_p4d",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604822058,
      "name": "pti_clone_p4d",
      "external": false,
      "loc": "arch/x86/mm/pti.c:418",
      "file": "arch/x86/mm/pti.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init",
        "arch/x86/mm/pti.c:pti_init"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void pti_clone_p4d(long unsigned int addr)
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
