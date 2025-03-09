# Function: <code>mds_select_mitigation</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604718243,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:229",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604728172,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:238",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604728172,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609074569,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:241",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609074569,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612138262,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:241",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612138262,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614277515,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:241",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614277515,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 140
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615201372,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:251",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615201372,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 168
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616973125,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:270",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616973125,
      "name": "mds_select_mitigation",
      "section": ".init.text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627590928,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:278",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627590928,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 207
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619344752,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:244",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619344752,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 207
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621638128,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:241",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621638128,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 214
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604654475,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:238",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604654475,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604622195,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:238",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604622195,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604732238,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:238",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604732238,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
void mds_select_mitigation()
```

```json
{
  "name": "mds_select_mitigation",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604732284,
      "name": "mds_select_mitigation",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:238",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604732284,
      "name": "mds_select_mitigation",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void mds_select_mitigation()
```
</details>
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
void mds_select_mitigation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mds_select_mitigation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mds_select_mitigation()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mds_select_mitigation()
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
