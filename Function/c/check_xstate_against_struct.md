# Function: <code>check_xstate_against_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595007283,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:449",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
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
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595171247,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:520",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
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
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595413599,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:525",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
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
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596332950,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:526",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
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
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579088489,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:544",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
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
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579093845,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:544",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
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
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579099257,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:544",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579109628,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:538",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579109628,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111566,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:538",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111566,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579124421,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:576",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579124421,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591249775,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:581",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591249775,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591193541,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:616",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591193541,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592058912,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:517",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592058912,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
bool check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616963226,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:524",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616963226,
      "name": "check_xstate_against_struct",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1421
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
bool check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627579520,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:524",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627579520,
      "name": "check_xstate_against_struct",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1533
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
bool check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619332000,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:524",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619332000,
      "name": "check_xstate_against_struct",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1440
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
bool check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621624976,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:528",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621624976,
      "name": "check_xstate_against_struct",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1570
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111950,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:538",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111950,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579044016,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:538",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044016,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111502,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:538",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111502,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
void check_xstate_against_struct(int nr)
```

```json
{
  "name": "check_xstate_against_struct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579116590,
      "name": "check_xstate_against_struct",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:538",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579116590,
      "name": "check_xstate_against_struct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void check_xstate_against_struct(int nr)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
void check_xstate_against_struct(int nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void check_xstate_against_struct(int nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void check_xstate_against_struct(int nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void check_xstate_against_struct(int nr)
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
