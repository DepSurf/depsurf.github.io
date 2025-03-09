# Function: <code>cgroup1_root_to_use</code>

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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580276931,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1131",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580325075,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1107",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393360,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071580398516,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1112",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380400,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
    },
    {
      "addr": 18446744071591315291,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1118",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383360,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 673
    },
    {
      "addr": 18446744071591257476,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1139",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545424,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
    },
    {
      "addr": 18446744071592161573,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1130",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743632,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
    },
    {
      "addr": 18446744071593934617,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1142",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581020176,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    },
    {
      "addr": 18446744071596000183,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1142",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581108512,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    },
    {
      "addr": 18446744071596518346,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int cgroup1_root_to_use(struct fs_context * fc)
```

```json
{
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1141",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206320,
      "name": "cgroup1_root_to_use",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
    },
    {
      "addr": 18446744071597418589,
      "name": "cgroup1_root_to_use.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491583256,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225545152,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284565004,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271992482,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580293875,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580241235,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580285123,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
  "name": "cgroup1_root_to_use",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580339046,
      "name": "cgroup1_root_to_use",
      "external": false,
      "loc": "kernel/cgroup/cgroup-v1.c:1113",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
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
int cgroup1_root_to_use(struct fs_context * fc)
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
