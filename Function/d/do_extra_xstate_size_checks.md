# Function: <code>do_extra_xstate_size_checks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595007247,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:483",
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
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595171213,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:556",
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
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595413565,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:561",
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
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596332916,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:562",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void do_extra_xstate_size_checks()
```

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088410,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:580",
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
      "addr": 18446744071579088410,
      "name": "do_extra_xstate_size_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
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
void do_extra_xstate_size_checks()
```

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579093770,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:580",
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
      "addr": 18446744071579093770,
      "name": "do_extra_xstate_size_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
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
void do_extra_xstate_size_checks()
```

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579099178,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:580",
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
      "addr": 18446744071579099178,
      "name": "do_extra_xstate_size_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 992
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
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604712559,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:574",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604724392,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:574",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void do_extra_xstate_size_checks()
```

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579125094,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:612",
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
      "addr": 18446744071579125094,
      "name": "do_extra_xstate_size_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
void do_extra_xstate_size_checks()
```

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591250453,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:623",
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
      "addr": 18446744071591250453,
      "name": "do_extra_xstate_size_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void do_extra_xstate_size_checks()
```

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591194211,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:658",
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
      "addr": 18446744071591194211,
      "name": "do_extra_xstate_size_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
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
void do_extra_xstate_size_checks()
```

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592059860,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:559",
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
      "addr": 18446744071592059860,
      "name": "do_extra_xstate_size_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604650695,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:574",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604618483,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:574",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604728458,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:574",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_extra_xstate_size_checks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604728504,
      "name": "do_extra_xstate_size_checks",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:574",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void do_extra_xstate_size_checks()
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void do_extra_xstate_size_checks()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void do_extra_xstate_size_checks()
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void do_extra_xstate_size_checks()
```
</details>
</li>
</ul>
