# Function: <code>sysctl_cpy_dir</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580908928,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1126",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908928,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580962080,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962080,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581124464,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1466",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124464,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1496",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158304,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071591323154,
      "name": "sysctl_cpy_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1582",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173008,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071591265042,
      "name": "sysctl_cpy_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1612",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412080,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071592187707,
      "name": "sysctl_cpy_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1744",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581737904,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071593962371,
      "name": "sysctl_cpy_dir.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582147808,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1983",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147808,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582345264,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:2001",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345264,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582511968,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:2019",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582511968,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492307272,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492307272,
      "name": "sysctl_cpy_dir.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226192988,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name",
        "kernel/bpf/cgroup.c:sysctl_cpy_dir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226192988,
      "name": "sysctl_cpy_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285545504,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285545504,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272438182,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272438182,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580930880,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930880,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580876944,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876944,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922128,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922128,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_cpy_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580982400,
      "name": "sysctl_cpy_dir",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1145",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:bpf_sysctl_get_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982400,
      "name": "sysctl_cpy_dir.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
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
ssize_t sysctl_cpy_dir(const struct ctl_dir * dir, char * * bufp, size_t * lenp)
```
</details>
</li>
</ul>
