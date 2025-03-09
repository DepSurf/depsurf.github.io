# Function: <code>groups_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579518847,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:81",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579532943,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:81",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579557519,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:57",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543992,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:58",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579571864,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:SyS_setgroups"
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
int groups_from_user(struct group_info * group_info, gid_t * grouplist)
```

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599872,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599872,
      "name": "groups_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579637274,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579662091,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699163,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579739877,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579721285,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579728681,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:54",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579808729,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:54",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579919104,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:54",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580073805,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:54",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580126637,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:54",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580170989,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:54",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__do_sys_setgroups"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int groups_from_user(struct group_info * group_info, gid_t * grouplist)
```

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490880800,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/groups.c:__arm64_sys_setgroups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490880800,
      "name": "groups_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224897256,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283714036,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271532660,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579675483,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579603819,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579672715,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
  "name": "groups_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579706843,
      "name": "groups_from_user",
      "external": false,
      "loc": "kernel/groups.c:59",
      "file": "kernel/groups.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__ia32_sys_setgroups",
        "kernel/groups.c:__x64_sys_setgroups"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int groups_from_user(struct group_info * group_info, gid_t * grouplist)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int groups_from_user(struct group_info * group_info, gid_t * grouplist)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int groups_from_user(struct group_info * group_info, gid_t * grouplist)
```
</details>
</li>
</ul>
