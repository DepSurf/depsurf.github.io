# Function: <code>module_disable_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923296,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1894",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923296,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953152,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1909",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:klp_write_object_relocations",
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953152,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579992793,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1901",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981856,
      "name": "module_disable_ro.part.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071579984352,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580000531,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1928",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985920,
      "name": "module_disable_ro.part.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071579989664,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047050,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032512,
      "name": "module_disable_ro.part.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071580036224,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580105557,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1935",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088560,
      "name": "module_disable_ro.part.60",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071580093728,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150875,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1936",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "kernel/module.c:load_module"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135456,
      "name": "module_disable_ro.part.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071580141008,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580187696,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:1944",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187696,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580236400,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580236400,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491478512,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/ftrace.c:ftrace_make_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491478512,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225460772,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225460772,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
  "name": "module_disable_ro",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "module_disable_ro",
      "external": false,
      "loc": "include/linux/module.h:857",
      "file": "kernel/livepatch/core.c",
      "inline": "declared, inlined",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580205200,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580205200,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152640,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152640,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196672,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196672,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void module_disable_ro(const struct module * mod)
```

```json
{
  "name": "module_disable_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580249120,
      "name": "module_disable_ro",
      "external": true,
      "loc": "kernel/module.c:2001",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249120,
      "name": "module_disable_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void module_disable_ro(const struct module * mod)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void module_disable_ro(const struct module * mod)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void module_disable_ro(const struct module * mod)
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
