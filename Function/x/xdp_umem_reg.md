# Function: <code>xdp_umem_reg</code>

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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589122023,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:259",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589356087,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:310",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589813094,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:300",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590037994,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591068560,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:304",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068560,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591133472,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591133472,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591064288,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:154",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591064288,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591906880,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:153",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591906880,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593627744,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:153",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593627744,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595557376,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:151",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595557376,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596065696,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:151",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596065696,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1046
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
```

```json
{
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596933504,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:156",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596933504,
      "name": "xdp_umem_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503792328,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236411424,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297634748,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279697302,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589641594,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589366122,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590083626,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
  "name": "xdp_umem_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590133834,
      "name": "xdp_umem_reg",
      "external": false,
      "loc": "net/xdp/xdp_umem.c:340",
      "file": "net/xdp/xdp_umem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create"
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
int xdp_umem_reg(struct xdp_umem * umem, struct xdp_umem_reg * mr)
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
