# Function: <code>__nd_attach_ndns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584746064,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:46",
      "file": "drivers/nvdimm/claim.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584746064,
      "name": "__nd_attach_ndns.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071584746480,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585099658,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:47",
      "file": "drivers/nvdimm/claim.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585099168,
      "name": "__nd_attach_ndns.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071585099584,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585288698,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:46",
      "file": "drivers/nvdimm/claim.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585287616,
      "name": "__nd_attach_ndns.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071585288624,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585374576,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:51",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585374576,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585803632,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:51",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585803632,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586049776,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:51",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049776,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586190032,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:51",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190032,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586427216,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586427216,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573856,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573856,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587358720,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587358720,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587419968,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:44",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419968,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587301936,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:44",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587301936,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:44",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592523075,
      "name": "__nd_attach_ndns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587868800,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:44",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594394635,
      "name": "__nd_attach_ndns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589218240,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:44",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596258433,
      "name": "__nd_attach_ndns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071590774064,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:44",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596786512,
      "name": "__nd_attach_ndns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591115456,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:44",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597695447,
      "name": "__nd_attach_ndns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591460880,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499463712,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499463712,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292728896,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292728896,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276684918,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276684918,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586264336,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264336,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586082704,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586082704,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586521824,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586521824,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```

```json
{
  "name": "__nd_attach_ndns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586633552,
      "name": "__nd_attach_ndns",
      "external": true,
      "loc": "drivers/nvdimm/claim.c:43",
      "file": "drivers/nvdimm/claim.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/claim.c:nd_namespace_store",
        "drivers/nvdimm/claim.c:nd_attach_ndns",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_devinit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586633552,
      "name": "__nd_attach_ndns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool __nd_attach_ndns(struct device * dev, struct nd_namespace_common * attach, struct nd_namespace_common * * _ndns)
```
</details>
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
