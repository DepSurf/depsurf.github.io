# Function: <code>groups16_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579911465,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:111",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_getgroups16"
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
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579941353,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:111",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_getgroups16"
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
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972617,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:111",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_getgroups16"
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
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978041,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:112",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_getgroups16"
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
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580024457,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:113",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_getgroups16"
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079152,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079152,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126496,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126496,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172064,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172064,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219904,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219904,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287456,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287456,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270960,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270960,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275600,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275600,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580427920,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580427920,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651248,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651248,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918720,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918720,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581005696,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581005696,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101856,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101856,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491459444,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:__arm64_sys_getgroups16"
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
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225445140,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:__se_sys_getgroups16"
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580188704,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580188704,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136144,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136144,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180176,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180176,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```

```json
{
  "name": "groups16_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232416,
      "name": "groups16_to_user",
      "external": false,
      "loc": "kernel/uid16.c:114",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_getgroups16",
        "kernel/uid16.c:__x64_sys_getgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232416,
      "name": "groups16_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
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
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int groups16_to_user(old_gid_t * grouplist, struct group_info * group_info)
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
