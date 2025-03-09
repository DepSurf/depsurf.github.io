# Function: <code>cgroup_free_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579971920,
      "name": "cgroup_free_root",
      "external": false,
      "loc": "kernel/cgroup.c:1124",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971920,
      "name": "cgroup_free_root",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580021544,
      "name": "cgroup_free_root",
      "external": false,
      "loc": "kernel/cgroup.c:1166",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_mount"
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
  "name": "cgroup_free_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580055229,
      "name": "cgroup_free_root",
      "external": false,
      "loc": "kernel/cgroup.c:1169",
      "file": "kernel/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_mount"
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055879,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1062",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_work_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580042144,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580106051,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1231",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_work_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091648,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580165092,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1234",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150736,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580212844,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1269",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580198368,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580261417,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580245248,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580309658,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580293472,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580379250,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1302",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364608,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580366178,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1299",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351488,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580369223,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1299",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354608,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580529111,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1330",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511584,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580726126,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1333",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708128,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581001656,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1352",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580981440,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581090232,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1336",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069328,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581187732,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1316",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166752,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491561816,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491543568,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225526260,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225508464,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284537900,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284513536,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271975560,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271959152,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580278458,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580262272,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580225940,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209776,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580269706,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580253520,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void cgroup_free_root(struct cgroup_root * root)
```

```json
{
  "name": "cgroup_free_root",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580323174,
      "name": "cgroup_free_root",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:1310",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306848,
      "name": "cgroup_free_root",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void cgroup_free_root(struct cgroup_root * root)
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
