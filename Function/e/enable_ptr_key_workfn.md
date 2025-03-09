# Function: <code>enable_ptr_key_workfn</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603250601,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:1657",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178448,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605061709,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:644",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589408496,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605179512,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589864272,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605220078,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590090080,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585087952,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:721",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087952,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585237056,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:724",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237056,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119952,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:750",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119952,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585569280,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:751",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585569280,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586723216,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:755",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723216,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511358412,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503868472,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3244022628,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236516552,
      "name": "enable_ptr_key_workfn",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302919404,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297729056,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270888680,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279779138,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605108722,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589692336,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605076800,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418128,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605197116,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590135712,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
```

```json
{
  "name": "enable_ptr_key_workfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605224288,
      "name": "enable_ptr_key_workfn",
      "external": false,
      "loc": "lib/vsprintf.c:699",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:initialize_ptr_random"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590186096,
      "name": "enable_ptr_key_workfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void enable_ptr_key_workfn(struct work_struct * work)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void enable_ptr_key_workfn(struct work_struct * work)
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
