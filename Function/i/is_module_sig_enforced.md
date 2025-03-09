# Function: <code>is_module_sig_enforced</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025296,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:285",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025296,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580099928,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:284",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_read_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081248,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128592,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:284",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128592,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580195039,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:275",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174112,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580243287,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580221952,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580314298,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:280",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290032,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580299591,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:282",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273952,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580302188,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:285",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580278576,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580455484,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:286",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592158247,
      "name": "is_module_sig_enforced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580434272,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580486063,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module/signing.c:29",
      "file": "kernel/module/signing.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/signing.c:module_sig_check"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593925526,
      "name": "is_module_sig_enforced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580485696,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580737311,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module/signing.c:29",
      "file": "kernel/module/signing.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/signing.c:module_sig_check"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595994094,
      "name": "is_module_sig_enforced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580736880,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580819407,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module/signing.c:29",
      "file": "kernel/module/signing.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/signing.c:module_sig_check"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596512400,
      "name": "is_module_sig_enforced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580818976,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580908847,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module/signing.c:29",
      "file": "kernel/module/signing.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/signing.c:module_sig_check"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597411601,
      "name": "is_module_sig_enforced.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580908416,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491485468,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491462296,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225468116,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225446220,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284440112,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284408080,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271930016,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271913110,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580212087,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580190752,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580159527,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138192,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580203559,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182224,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool is_module_sig_enforced()
```

```json
{
  "name": "is_module_sig_enforced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580256023,
      "name": "is_module_sig_enforced",
      "external": true,
      "loc": "kernel/module.c:277",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module"
      ],
      "caller_func": [
        "security/integrity/ima/ima_main.c:ima_load_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580234464,
      "name": "is_module_sig_enforced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool is_module_sig_enforced()
```
</details>
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
