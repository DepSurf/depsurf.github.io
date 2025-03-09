# Function: <code>cec_s_phys_addr</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587260023,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1546",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260112,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587521555,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1591",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587521360,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587521472,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587724627,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724432,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587724544,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500901916,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500901672,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446603336500901792,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233420572,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233420364,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 3233420476,
      "name": "cec_s_phys_addr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294358456,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294358176,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 13835058055294358352,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277680338,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277680120,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446743936277680232,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587365571,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365376,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587365488,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587133795,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133600,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587133712,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587680771,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587680576,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587680688,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587787155,
      "name": "cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1605",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid"
      ],
      "caller_func": [
        "drivers/media/cec/cec-core.c:cec_cec_notify",
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587786960,
      "name": "cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071587787072,
      "name": "cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
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
