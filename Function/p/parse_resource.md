# Function: <code>parse_resource</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580074143,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:362",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580126895,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:362",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580186297,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:362",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580234729,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:362",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580284793,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580333017,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
int parse_resource(char * c, int * intval)
```

```json
{
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580404288,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580404288,
      "name": "parse_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int parse_resource(char * c, int * intval)
```

```json
{
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391584,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391584,
      "name": "parse_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580394603,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_parse_limits"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580556692,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_parse_limits"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580755926,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_parse_limits"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581034198,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_parse_limits"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int parse_resource(char * c, int * intval)
```

```json
{
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581122448,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:358",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581122448,
      "name": "parse_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int parse_resource(char * c, int * intval)
```

```json
{
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220800,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:358",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220800,
      "name": "parse_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491595392,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225554864,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284578956,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272000730,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580301817,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580249161,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580293065,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
  "name": "parse_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580347417,
      "name": "parse_resource",
      "external": false,
      "loc": "kernel/cgroup/rdma.c:356",
      "file": "kernel/cgroup/rdma.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_resource_set_max"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int parse_resource(char * c, int * intval)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int parse_resource(char * c, int * intval)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int parse_resource(char * c, int * intval)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
