# Function: <code>mls_write_level</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582322695,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2523",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582543975,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2523",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582636823,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2527",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582728560,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2566",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582728560,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582884544,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2566",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884544,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583082576,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2566",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583082576,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583197952,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2591",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197952,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583384528,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2537",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384528,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583490416,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490416,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583846620,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2681",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583968956,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2723",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583997484,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2721",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584364444,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2720",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584989113,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2714",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585704588,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2714",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585920876,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2718",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
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
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586168748,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2743",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495257136,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495257136,
      "name": "mls_write_level",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228638028,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228638028,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289230256,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289230256,
      "name": "mls_write_level",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274480946,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274480946,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583459152,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583459152,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583396224,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583396224,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583442928,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583442928,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int mls_write_level(struct mls_level * l, void * fp)
```

```json
{
  "name": "mls_write_level",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583539184,
      "name": "mls_write_level",
      "external": false,
      "loc": "security/selinux/ss/policydb.c:2539",
      "file": "security/selinux/ss/policydb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/policydb.c:user_write",
        "security/selinux/ss/policydb.c:sens_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539184,
      "name": "mls_write_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int mls_write_level(struct mls_level * l, void * fp)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int mls_write_level(struct mls_level * l, void * fp)
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
