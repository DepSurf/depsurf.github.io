# Function: <code>__tcf_action_put</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588291040,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:101",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291040,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588688688,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688688,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588912816,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588912816,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589801088,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801088,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836864,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:141",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836864,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589741904,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:141",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_delete",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589741904,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590500704,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:141",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590500704,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592105600,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:379",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592105600,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593927056,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:380",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593927056,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594302176,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:373",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594302176,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595101136,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:373",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595101136,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502506232,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502506232,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235217932,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235217932,
      "name": "__tcf_action_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296072000,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296072000,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278677836,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278677836,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588519200,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519200,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588231200,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231200,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588851376,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851376,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int __tcf_action_put(struct tc_action * p, bool bind)
```

```json
{
  "name": "__tcf_action_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588992784,
      "name": "__tcf_action_put",
      "external": false,
      "loc": "net/sched/act_api.c:125",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_put_many",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992784,
      "name": "__tcf_action_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __tcf_action_put(struct tc_action * p, bool bind)
```
</details>
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
