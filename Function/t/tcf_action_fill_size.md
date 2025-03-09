# Function: <code>tcf_action_fill_size</code>

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
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588116317,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:139",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
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
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588297576,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:181",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588687168,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588687168,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588911264,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588911264,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589798416,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:209",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589798416,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589834560,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:225",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589834560,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589739680,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:236",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589739680,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590498336,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:236",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590498336,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592101168,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:474",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592101168,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593922304,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:475",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593922304,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594299152,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:468",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594299152,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595098384,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:468",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595098384,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502503016,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502503016,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235215024,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235215024,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296068880,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296068880,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278677558,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278677558,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588517648,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588517648,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588229648,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229648,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588849824,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588849824,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
size_t tcf_action_fill_size(const struct tc_action * act)
```

```json
{
  "name": "tcf_action_fill_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588992080,
      "name": "tcf_action_fill_size",
      "external": false,
      "loc": "net/sched/act_api.c:205",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992080,
      "name": "tcf_action_fill_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
size_t tcf_action_fill_size(const struct tc_action * act)
```
</details>
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
