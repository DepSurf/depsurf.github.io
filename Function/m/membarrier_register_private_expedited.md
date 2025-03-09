# Function: <code>membarrier_register_private_expedited</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579745789,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:108",
      "file": "kernel/sched/membarrier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:SyS_membarrier"
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579779312,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:221",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579779312,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822192,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:221",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822192,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850384,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:212",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850384,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899568,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899568,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942624,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942624,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930624,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:501",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930624,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937936,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:501",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937936,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062880,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:502",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062880,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147440,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:501",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147440,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580343840,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:501",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343840,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410864,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:502",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__ia32_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier",
        "kernel/sched/build_utility.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410864,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580466992,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:508",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:__do_sys_membarrier",
        "kernel/sched/build_utility.c:__do_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466992,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491098216,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__arm64_sys_membarrier",
        "kernel/sched/membarrier.c:__arm64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491098216,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225101252,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:__se_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225101252,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283988000,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:__se_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283988000,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271680742,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:__se_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271680742,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871680,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871680,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806624,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806624,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859840,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859840,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int membarrier_register_private_expedited(int flags)
```

```json
{
  "name": "membarrier_register_private_expedited",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905216,
      "name": "membarrier_register_private_expedited",
      "external": false,
      "loc": "kernel/sched/membarrier.c:278",
      "file": "kernel/sched/membarrier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__ia32_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier",
        "kernel/sched/membarrier.c:__x64_sys_membarrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905216,
      "name": "membarrier_register_private_expedited",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int membarrier_register_private_expedited(int flags)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
