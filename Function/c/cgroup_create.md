# Function: <code>cgroup_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580025290,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup.c:5207",
      "file": "kernel/cgroup.c",
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
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580059274,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup.c:5229",
      "file": "kernel/cgroup.c",
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
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580056418,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4182",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
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
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106761,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4777",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580165876,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4817",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
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
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213620,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:4904",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
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
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252256,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5206",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252256,
      "name": "cgroup_create",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580300496,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580300496,
      "name": "cgroup_create",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580370768,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5178",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370768,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580357664,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5170",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357664,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360832,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5154",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360832,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519280,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5344",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519280,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580716288,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5355",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580716288,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990880,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5572",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990880,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078448,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5553",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078448,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
struct cgroup * cgroup_create(struct cgroup * parent, const char * name, umode_t mode)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175952,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5588",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175952,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 762
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
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491551936,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491551936,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225516048,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225516048,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284539348,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
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
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271966314,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271966314,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269296,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269296,
      "name": "cgroup_create",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216800,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216800,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580260544,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260544,
      "name": "cgroup_create",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cgroup * cgroup_create(struct cgroup * parent)
```

```json
{
  "name": "cgroup_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580313904,
      "name": "cgroup_create",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5221",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_mkdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313904,
      "name": "cgroup_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
struct cgroup * cgroup_create(struct cgroup * parent)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * name</code>
</li>
<li>
<b>Param added. </b>
<code>umode_t mode</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct cgroup * cgroup_create(struct cgroup * parent)
```
</details>
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
