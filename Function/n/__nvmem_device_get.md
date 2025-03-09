# Function: <code>__nvmem_device_get</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586863440,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:547",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586863440,
      "name": "__nvmem_device_get.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587351232,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:549",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:devm_nvmem_cell_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587351232,
      "name": "__nvmem_device_get.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587654597,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:623",
      "file": "drivers/nvmem/core.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587785219,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:794",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:540",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089408,
      "name": "__nvmem_device_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    },
    {
      "addr": 18446744071588093381,
      "name": "__nvmem_device_get.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295232,
      "name": "__nvmem_device_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071588299124,
      "name": "__nvmem_device_get.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:777",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176464,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071589181503,
      "name": "__nvmem_device_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:952",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172000,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071591625119,
      "name": "__nvmem_device_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:955",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589065712,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071591568389,
      "name": "__nvmem_device_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:966",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589784192,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071592690821,
      "name": "__nvmem_device_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:946",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295648,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446744071594576064,
      "name": "__nvmem_device_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593046480,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:944",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593046480,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593498960,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:1094",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593498960,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594246752,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:1105",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get",
        "drivers/nvmem/core.c:nvmem_device_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594246752,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501816800,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:of_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501816800,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234335604,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:of_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234335604,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295213840,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:of_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295213840,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278163694,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:of_nvmem_cell_get",
        "drivers/nvmem/core.c:of_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278163694,
      "name": "__nvmem_device_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587898992,
      "name": "__nvmem_device_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071587902884,
      "name": "__nvmem_device_get.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587618272,
      "name": "__nvmem_device_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071587622164,
      "name": "__nvmem_device_get.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588232288,
      "name": "__nvmem_device_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071588236180,
      "name": "__nvmem_device_get.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nvmem_device_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__nvmem_device_get",
      "external": false,
      "loc": "drivers/nvmem/core.c:537",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_get_from_lookup",
        "drivers/nvmem/core.c:devm_nvmem_device_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367616,
      "name": "__nvmem_device_get.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071588371508,
      "name": "__nvmem_device_get.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct nvmem_device * __nvmem_device_get(void * data, int (*)(struct device *, const void *) match)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct nvmem_device * __nvmem_device_get(struct device_node * np, const char * nvmem_name)
```
</details>
</li>
</ul>
