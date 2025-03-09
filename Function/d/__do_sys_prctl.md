# Function: <code>__do_sys_prctl</code>

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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534604,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2279",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579570716,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2280",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579594105,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2287",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579620153,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650592,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2295",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650592,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1638
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631136,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2299",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631136,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1799
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637840,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2316",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637840,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1773
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714368,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2287",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714368,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1760
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816048,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2363",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816048,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1843
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952272,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2368",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952272,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1843
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002032,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2423",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002032,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2341
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
```

```json
{
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580041568,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2460",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041568,
      "name": "__do_sys_prctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2461
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490786616,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__arm64_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224822668,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283611480,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271469064,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579596457,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525097,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579593737,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
  "name": "__do_sys_prctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579627401,
      "name": "__do_sys_prctl",
      "external": false,
      "loc": "kernel/sys.c:2277",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl"
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
long int __do_sys_prctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5)
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
