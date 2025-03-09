# Function: <code>__tcf_idr_release</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587765696,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:87",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765696,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588106416,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:87",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588106416,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588292254,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:121",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291248,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588690166,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688896,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588914294,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913024,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589804668,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589801200,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589840508,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:161",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836976,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
  "name": "__tcf_idr_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589745420,
      "name": "__tcf_idr_release",
      "external": false,
      "loc": "net/sched/act_api.c:161",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release",
        "net/sched/act_api.c:tcf_idr_release"
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
  "name": "__tcf_idr_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590503884,
      "name": "__tcf_idr_release",
      "external": false,
      "loc": "net/sched/act_api.c:161",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release",
        "net/sched/act_api.c:tcf_idr_release"
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
  "name": "__tcf_idr_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592107996,
      "name": "__tcf_idr_release",
      "external": false,
      "loc": "net/sched/act_api.c:399",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
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
  "name": "__tcf_idr_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593927804,
      "name": "__tcf_idr_release",
      "external": false,
      "loc": "net/sched/act_api.c:400",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
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
  "name": "__tcf_idr_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594304780,
      "name": "__tcf_idr_release",
      "external": false,
      "loc": "net/sched/act_api.c:393",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
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
  "name": "__tcf_idr_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595103836,
      "name": "__tcf_idr_release",
      "external": false,
      "loc": "net/sched/act_api.c:393",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idr_release"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502506828,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502506488,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235218404,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235218104,
      "name": "__tcf_idr_release",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296076316,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296072400,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278681288,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278679436,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588520678,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519408,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588232678,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231408,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588852854,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851584,
      "name": "__tcf_idr_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_idr_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588994278,
      "name": "__tcf_idr_release",
      "external": true,
      "loc": "net/sched/act_api.c:145",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_idrinfo_destroy",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992992,
      "name": "__tcf_idr_release",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int __tcf_idr_release(struct tc_action * p, bool bind, bool strict)
```
</details>
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
