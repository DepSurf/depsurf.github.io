# Function: <code>acct_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579942570,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:190",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:SyS_acct"
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
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579973386,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:190",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:SyS_acct"
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
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580003866,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:190",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:SyS_acct"
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
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011066,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:192",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:SyS_acct"
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
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580057946,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:SyS_acct"
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580114768,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114768,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161760,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161760,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580207664,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207664,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580256000,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580256000,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580323184,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580323184,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308480,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308480,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312016,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312016,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580465552,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580465552,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580659008,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:212",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580659008,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928768,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:212",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928768,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015184,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:212",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015184,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111056,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:212",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111056,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491497396,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:__arm64_sys_acct"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225480636,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:__se_sys_acct"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284458324,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:__se_sys_acct"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271941038,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/acct.c:__se_sys_acct"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224800,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224800,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172240,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172240,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216272,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216272,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
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
int acct_on(struct filename * pathname)
```

```json
{
  "name": "acct_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580268976,
      "name": "acct_on",
      "external": false,
      "loc": "kernel/acct.c:193",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268976,
      "name": "acct_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 629
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
int acct_on(struct filename * pathname)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int acct_on(struct filename * pathname)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acct_on(struct filename * pathname)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acct_on(struct filename * pathname)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acct_on(struct filename * pathname)
```
</details>
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
