# Function: <code>xfeature_is_supervisor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:328",
      "file": "arch/x86/kernel/fpu/xstate.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595171799,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:116",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
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
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595414151,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:121",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
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
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596333417,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:122",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087954,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:116",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087954,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093314,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:116",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093314,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098722,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:116",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098722,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579109113,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:110",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579109113,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111113,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:110",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111113,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
bool xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579125007,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:112",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:setup_xstate_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125007,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
bool xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591249688,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:114",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:setup_xstate_features"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591249688,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
bool xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591193454,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:114",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591193454,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
bool xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592058635,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:119",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks",
        "arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592058635,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616965640,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:132",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627583332,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:132",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619335627,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:132",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621628299,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:133",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid"
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
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111497,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:110",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111497,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604618542,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:110",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579111049,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:110",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579111049,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
int xfeature_is_supervisor(int xfeature_nr)
```

```json
{
  "name": "xfeature_is_supervisor",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579116137,
      "name": "xfeature_is_supervisor",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:110",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579116137,
      "name": "xfeature_is_supervisor",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool xfeature_is_supervisor(int xfeature_nr)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int xfeature_is_supervisor(int xfeature_nr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
