# Function: <code>groups16_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579911695,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:129",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_setgroups16"
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
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579941583,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:129",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_setgroups16"
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
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579972833,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:129",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_setgroups16"
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
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978248,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:130",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_setgroups16"
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
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580024664,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:131",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:SyS_setgroups16"
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
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580079616,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079616,
      "name": "groups16_from_user",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126960,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126960,
      "name": "groups16_from_user",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172528,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172528,
      "name": "groups16_from_user",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220368,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220368,
      "name": "groups16_from_user",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287920,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287920,
      "name": "groups16_from_user",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271424,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271424,
      "name": "groups16_from_user",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276064,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276064,
      "name": "groups16_from_user",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580428384,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580428384,
      "name": "groups16_from_user",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651776,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651776,
      "name": "groups16_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919344,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919344,
      "name": "groups16_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006304,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006304,
      "name": "groups16_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581103857,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:__do_sys_setgroups16"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491458696,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:__arm64_sys_setgroups16"
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
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225445432,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:__se_sys_setgroups16"
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
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189168,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189168,
      "name": "groups16_from_user",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136608,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136608,
      "name": "groups16_from_user",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180640,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180640,
      "name": "groups16_from_user",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```

```json
{
  "name": "groups16_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232880,
      "name": "groups16_from_user",
      "external": false,
      "loc": "kernel/uid16.c:132",
      "file": "kernel/uid16.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_setgroups16",
        "kernel/uid16.c:__x64_sys_setgroups16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232880,
      "name": "groups16_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
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
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int groups16_from_user(struct group_info * group_info, old_gid_t * grouplist)
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
