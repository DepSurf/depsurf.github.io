# Function: <code>__uprobe_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580451121,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:834",
      "file": "kernel/events/uprobes.c",
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
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580526544,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:836",
      "file": "kernel/events/uprobes.c",
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
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580589888,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:837",
      "file": "kernel/events/uprobes.c",
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
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580620109,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
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
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580700973,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:845",
      "file": "kernel/events/uprobes.c",
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
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580833372,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:843",
      "file": "kernel/events/uprobes.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1112",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901120,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
    },
    {
      "addr": 18446744071580907782,
      "name": "__uprobe_register.cold.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1100",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580998800,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071581005580,
      "name": "__uprobe_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581053632,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071581060456,
      "name": "__uprobe_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236208,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1142",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236208,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581278912,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1142",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278912,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295136,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1140",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295136,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581540048,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1141",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581540048,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890288,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1135",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890288,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323264,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1138",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323264,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582524592,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1135",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524592,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693520,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1135",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693520,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492411328,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492411328,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 804
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226295040,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226295040,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 864
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285676864,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285676864,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022480,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071581029304,
      "name": "__uprobe_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968576,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071580975384,
      "name": "__uprobe_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013680,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071581020504,
      "name": "__uprobe_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "__uprobe_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__uprobe_register",
      "external": false,
      "loc": "kernel/events/uprobes.c:1152",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_register_refctr",
        "kernel/events/uprobes.c:uprobe_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074944,
      "name": "__uprobe_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 726
    },
    {
      "addr": 18446744071581081848,
      "name": "__uprobe_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```
</details>
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
int __uprobe_register(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
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
