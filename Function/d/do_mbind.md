# Function: <code>do_mbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820640,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1135",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:compat_SyS_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820640,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580946064,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1167",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:compat_SyS_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946064,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581018481,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1169",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581064353,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1098",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581175537,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1161",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581320229,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1137",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581404421,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1177",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581516568,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1216",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581581032,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1217",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793488,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1286",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793488,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 956
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581841312,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1266",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581841312,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872160,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1278",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872160,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582163840,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1249",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582163840,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1068
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582620864,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1242",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582620864,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145072,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1257",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145072,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1111
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583355168,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1262",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583355168,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1339
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
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1218",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590944,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2155
    },
    {
      "addr": 18446744071597472705,
      "name": "do_mbind.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493018880,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1217",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```

```json
{
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286446432,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1217",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_mbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286446432,
      "name": "do_mbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1808
    }
  ]
}
```
</details>
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581549768,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1217",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581491416,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1217",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541080,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1217",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
  "name": "do_mbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581606096,
      "name": "do_mbind",
      "external": false,
      "loc": "mm/mempolicy.c:1217",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_mbind"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
long int do_mbind(long unsigned int start, long unsigned int len, short unsigned int mode, short unsigned int mode_flags, nodemask_t * nmask, long unsigned int flags)
```
</details>
</li>
</ul>
