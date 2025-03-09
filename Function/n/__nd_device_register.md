# Function: <code>__nd_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584709552,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:175",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584709552,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059888,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:436",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059888,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585243712,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:438",
      "file": "drivers/nvdimm/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585243712,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585324146,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:501",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325920,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585752114,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:501",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753888,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585998098,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:505",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000016,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586135634,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135488,
      "name": "__nd_device_register.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071586137056,
      "name": "__nd_device_register",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586370659,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:524",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370464,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071586372032,
      "name": "__nd_device_register",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586518355,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518160,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071586520160,
      "name": "__nd_device_register",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587298563,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:527",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298368,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587300800,
      "name": "__nd_device_register",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587359811,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:527",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359616,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587362048,
      "name": "__nd_device_register",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587241827,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:524",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241632,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071587244048,
      "name": "__nd_device_register",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808339,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:517",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808128,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071587810544,
      "name": "__nd_device_register",
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590710853,
      "name": "__nd_device_register",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:511",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register_sync"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590707952,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591052005,
      "name": "__nd_device_register",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:511",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register_sync"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591049152,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591396565,
      "name": "__nd_device_register",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:511",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register_sync"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591393712,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499402008,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499401784,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446603336499405728,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292642988,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292642624,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 13835058055292645952,
      "name": "__nd_device_register",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276633530,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276633358,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446743936276635340,
      "name": "__nd_device_register",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586208835,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208640,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071586210640,
      "name": "__nd_device_register",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586027203,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027008,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071586029008,
      "name": "__nd_device_register",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586466323,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466128,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071586468128,
      "name": "__nd_device_register",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __nd_device_register(struct device * dev)
```

```json
{
  "name": "__nd_device_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586578003,
      "name": "__nd_device_register",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:522",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nd_device_register"
      ],
      "caller_func": [
        "drivers/nvdimm/bus.c:nd_device_register",
        "drivers/nvdimm/btt_devs.c:nd_btt_probe",
        "drivers/nvdimm/btt_devs.c:nd_btt_create",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_probe",
        "drivers/nvdimm/pfn_devs.c:nd_pfn_create",
        "drivers/nvdimm/dax_devs.c:nd_dax_probe",
        "drivers/nvdimm/dax_devs.c:nd_dax_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586577808,
      "name": "__nd_device_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071586579808,
      "name": "__nd_device_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __nd_device_register(struct device * dev)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __nd_device_register(struct device * dev)
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
