# Function: <code>__do_sys_clone</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579425941,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2233",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579459365,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2338",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579476621,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2517",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579502685,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2502",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531104,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2590",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531104,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513616,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2581",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513616,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516768,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2613",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516768,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588480,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2706",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588480,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579679520,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2783",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579679520,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579799856,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2815",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579799856,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848016,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:3048",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848016,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
```

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579885808,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:3038",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579885808,
      "name": "__do_sys_clone",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490636020,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2486",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__arm64_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224713708,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2486",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__se_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283454848,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2486",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__se_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271390610,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2486",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__se_sys_clone"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579476349,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2502",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579405245,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2502",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579476269,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2502",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
  "name": "__do_sys_clone",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579508141,
      "name": "__do_sys_clone",
      "external": false,
      "loc": "kernel/fork.c:2502",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:__ia32_sys_clone",
        "kernel/fork.c:__x64_sys_clone"
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
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int * parent_tidptr, int * child_tidptr, long unsigned int tls)
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
