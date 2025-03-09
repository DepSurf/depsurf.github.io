# Function: <code>__put_seccomp_filter</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271856,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:500",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271856,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332832,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:509",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332832,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387552,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:569",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387552,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440176,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:574",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440176,
      "name": "__put_seccomp_filter",
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580489104,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489104,
      "name": "__put_seccomp_filter",
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580574656,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:585",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574656,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580563952,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:525",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_filter_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580563952,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567040,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:530",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_filter_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567040,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580737104,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:533",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_filter_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580737104,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949328,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:535",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_filter_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949328,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243712,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:535",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_filter_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243712,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338672,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:535",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_filter_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338672,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581445632,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:540",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "kernel/seccomp.c:seccomp_filter_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581445632,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491763896,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491763896,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225712312,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225712312,
      "name": "__put_seccomp_filter",
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284809232,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284809232,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272089680,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter"
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580457904,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580457904,
      "name": "__put_seccomp_filter",
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580404976,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404976,
      "name": "__put_seccomp_filter",
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580449152,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449152,
      "name": "__put_seccomp_filter",
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
void __put_seccomp_filter(struct seccomp_filter * orig)
```

```json
{
  "name": "__put_seccomp_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504784,
      "name": "__put_seccomp_filter",
      "external": false,
      "loc": "kernel/seccomp.c:575",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504784,
      "name": "__put_seccomp_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void __put_seccomp_filter(struct seccomp_filter * orig)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __put_seccomp_filter(struct seccomp_filter * orig)
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
