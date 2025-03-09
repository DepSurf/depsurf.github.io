# Function: <code>itlb_multihit_show_state</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579138956,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1441",
      "file": "arch/x86/kernel/cpu/bugs.c",
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579155008,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1558",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155008,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152256,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1566",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152256,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579158624,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1566",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158624,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1721",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579189184,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071592061974,
      "name": "itlb_multihit_show_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2223",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238000,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 18446744071593828536,
      "name": "itlb_multihit_show_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2274",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297040,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071595960684,
      "name": "itlb_multihit_show_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2549",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303168,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071596477994,
      "name": "itlb_multihit_show_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
ssize_t itlb_multihit_show_state(char * buf)
```

```json
{
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:2687",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_show_itlb_multihit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332976,
      "name": "itlb_multihit_show_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071597373767,
      "name": "itlb_multihit_show_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579139324,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1441",
      "file": "arch/x86/kernel/cpu/bugs.c",
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
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579070476,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1441",
      "file": "arch/x86/kernel/cpu/bugs.c",
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
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579138876,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1441",
      "file": "arch/x86/kernel/cpu/bugs.c",
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
  "name": "itlb_multihit_show_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579144012,
      "name": "itlb_multihit_show_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1441",
      "file": "arch/x86/kernel/cpu/bugs.c",
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
ssize_t itlb_multihit_show_state(char * buf)
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
