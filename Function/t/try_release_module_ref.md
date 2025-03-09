# Function: <code>try_release_module_ref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579924932,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:882",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:SyS_delete_module"
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
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579954484,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:884",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:SyS_delete_module"
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
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579985492,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:887",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:SyS_delete_module"
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
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579990818,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:907",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:SyS_delete_module"
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
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580037378,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:915",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:SyS_delete_module"
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580082720,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:914",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580082720,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130080,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:915",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130080,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176864,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:911",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176864,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224752,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224752,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580291648,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:926",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580291648,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275072,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:960",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275072,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580298226,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:865",
      "file": "kernel/module.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580451186,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:866",
      "file": "kernel/module.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580476007,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module/main.c:646",
      "file": "kernel/module/main.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580734155,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module/main.c:647",
      "file": "kernel/module/main.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580814251,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module/main.c:652",
      "file": "kernel/module/main.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580903643,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module/main.c:652",
      "file": "kernel/module/main.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491480068,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:__arm64_sys_delete_module"
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
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225462288,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:__se_sys_delete_module"
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
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284431412,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:__se_sys_delete_module"
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
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271926134,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:__se_sys_delete_module"
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580193552,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193552,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580140992,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140992,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185024,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185024,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int try_release_module_ref(struct module * mod)
```

```json
{
  "name": "try_release_module_ref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237264,
      "name": "try_release_module_ref",
      "external": false,
      "loc": "kernel/module.c:923",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237264,
      "name": "try_release_module_ref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int try_release_module_ref(struct module * mod)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int try_release_module_ref(struct module * mod)
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
int try_release_module_ref(struct module * mod)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int try_release_module_ref(struct module * mod)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int try_release_module_ref(struct module * mod)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int try_release_module_ref(struct module * mod)
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
