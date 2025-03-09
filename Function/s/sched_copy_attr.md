# Function: <code>sched_copy_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556314,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4111",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setattr"
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579566986,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4361",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setattr"
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579591962,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4398",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setattr"
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579576218,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4298",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setattr"
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605914,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4342",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:SyS_sched_setattr"
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608448,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4477",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608448,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645760,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4462",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645760,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670400,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:4899",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670400,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579707472,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579707472,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754880,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5352",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754880,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579741152,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:6171",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741152,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748144,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:6472",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748144,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820640,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:7636",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820640,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942208,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:7744",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942208,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099008,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:7886",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099008,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580156976,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:7995",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__do_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156976,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580202208,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:8046",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580202208,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490907396,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__arm64_sys_sched_setattr"
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224945384,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_setattr"
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283748184,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_setattr"
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
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271563140,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__se_sys_sched_setattr"
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683792,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683792,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612112,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612112,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579681008,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579681008,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```

```json
{
  "name": "sched_copy_attr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579715920,
      "name": "sched_copy_attr",
      "external": false,
      "loc": "kernel/sched/core.c:5119",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__ia32_sys_sched_setattr",
        "kernel/sched/core.c:__x64_sys_sched_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715920,
      "name": "sched_copy_attr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int sched_copy_attr(struct sched_attr * uattr, struct sched_attr * attr)
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
