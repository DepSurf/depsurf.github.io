# Function: <code>seccomp_attach_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580137909,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:422",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580172656,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:422",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213279,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:421",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580223165,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:433",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580272881,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:435",
      "file": "kernel/seccomp.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580335051,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:444",
      "file": "kernel/seccomp.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580390820,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:505",
      "file": "kernel/seccomp.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:510",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442240,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
    },
    {
      "addr": 18446744071580445789,
      "name": "seccomp_attach_filter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580491676,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580576976,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:517",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580576976,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
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
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580566224,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:857",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566224,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
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
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569040,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:862",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569040,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
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
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738848,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:865",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738848,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
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
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952112,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:867",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952112,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
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
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246592,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:867",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246592,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
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
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581341568,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:867",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341568,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
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
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581448576,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:876",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581448576,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
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
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491768080,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225716060,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225716060,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284812816,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272086986,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272086986,
      "name": "seccomp_attach_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580460476,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580407532,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580451724,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
  "name": "seccomp_attach_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580507372,
      "name": "seccomp_attach_filter",
      "external": false,
      "loc": "kernel/seccomp.c:511",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter * filter)
```
</details>
</li>
</ul>
