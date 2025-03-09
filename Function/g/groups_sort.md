# Function: <code>groups_sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579517722,
      "name": "groups_sort",
      "external": false,
      "loc": "kernel/groups.c:104",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:set_groups"
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
  "name": "groups_sort",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579531881,
      "name": "groups_sort",
      "external": false,
      "loc": "kernel/groups.c:104",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:set_groups"
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
  "name": "groups_sort",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556825,
      "name": "groups_sort",
      "external": false,
      "loc": "kernel/groups.c:80",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:set_groups"
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
  "name": "groups_sort",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543466,
      "name": "groups_sort",
      "external": false,
      "loc": "kernel/groups.c:88",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:set_groups"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579572011,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:SyS_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571344,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579600403,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599504,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579637400,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636592,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662221,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661408,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699293,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698480,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579739994,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738992,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579721402,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720400,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579728806,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:84",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727760,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579808854,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:84",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807808,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579919238,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:84",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918064,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580073972,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:84",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072608,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580126804,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:84",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125440,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580171153,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:84",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__do_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169584,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490881812,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__arm64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__arm64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490880160,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224897504,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__se_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224896668,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283714404,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283713008,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271532762,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271532048,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675613,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674800,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579603949,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603136,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672845,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672032,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void groups_sort(struct group_info * group_info)
```

```json
{
  "name": "groups_sort",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579706973,
      "name": "groups_sort",
      "external": true,
      "loc": "kernel/groups.c:89",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706160,
      "name": "groups_sort",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void groups_sort(struct group_info * group_info)
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
