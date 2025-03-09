# Function: <code>__do_sys_keyctl</code>

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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582944905,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1637",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583053454,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1637",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583236781,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583342605,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583677488,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1869",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677488,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583798992,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1869",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798992,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 858
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583823136,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1869",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823136,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186176,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1869",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186176,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584787088,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1869",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584787088,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585484304,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1869",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484304,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 855
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585715776,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1874",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585715776,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 861
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585962896,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1873",
      "file": "security/keys/keyctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585962896,
      "name": "__do_sys_keyctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 861
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495087148,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__arm64_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228481076,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288986916,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274350418,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__se_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583311341,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583248445,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583295373,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
  "name": "__do_sys_keyctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583390013,
      "name": "__do_sys_keyctl",
      "external": false,
      "loc": "security/keys/keyctl.c:1714",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:__ia32_sys_keyctl",
        "security/keys/keyctl.c:__x64_sys_keyctl"
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
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
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
