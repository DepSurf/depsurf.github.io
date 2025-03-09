# Function: <code>irq_sysfs_add</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785792,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:257",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785792,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783248,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:269",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783248,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816624,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:267",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816624,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:284",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850368,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579853282,
      "name": "irq_sysfs_add.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:284",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897360,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071579900240,
      "name": "irq_sysfs_add.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932176,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071579935072,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982304,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071579985200,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031695,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029824,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071580033328,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580015407,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013440,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071591302499,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580016191,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014336,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071591245342,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148363,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs"
      ],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146336,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071592137868,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580293214,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
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
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580503790,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
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
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580575542,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:318",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
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
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580639833,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:318",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491168216,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491168216,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225194044,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225194044,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284067008,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284067008,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271720628,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271720628,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951040,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071579953936,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888928,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071579891808,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942576,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071579945472,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```

```json
{
  "name": "irq_sysfs_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_sysfs_add",
      "external": false,
      "loc": "kernel/irq/irqdesc.c:286",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:__irq_alloc_descs",
        "kernel/irq/irqdesc.c:irq_sysfs_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988960,
      "name": "irq_sysfs_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071579991850,
      "name": "irq_sysfs_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void irq_sysfs_add(int irq, struct irq_desc * desc)
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
