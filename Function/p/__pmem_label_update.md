# Function: <code>__pmem_label_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584745167,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:493",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585097347,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:493",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
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
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585285522,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:493",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585371431,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:615",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585799159,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:617",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042080,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:626",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042080,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1371
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586182192,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:756",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586182192,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586419152,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:764",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586419152,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586565920,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586565920,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587350608,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587350608,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1461
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587412272,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587412272,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1329
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587294288,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587294288,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:814",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861024,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1261
    },
    {
      "addr": 18446744071592522898,
      "name": "__pmem_label_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:873",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212432,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2197
    },
    {
      "addr": 18446744071594393674,
      "name": "__pmem_label_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 689
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:873",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590768000,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2148
    },
    {
      "addr": 18446744071596257443,
      "name": "__pmem_label_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:873",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591109408,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2144
    },
    {
      "addr": 18446744071596785508,
      "name": "__pmem_label_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:873",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591454736,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2144
    },
    {
      "addr": 18446744071597694443,
      "name": "__pmem_label_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499455784,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499455784,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292716944,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292716944,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2064
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276678202,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276678202,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586256400,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586256400,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586074768,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586074768,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513888,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513888,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
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
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
```

```json
{
  "name": "__pmem_label_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586625632,
      "name": "__pmem_label_update",
      "external": false,
      "loc": "drivers/nvdimm/label.c:759",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586625632,
      "name": "__pmem_label_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1454
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __pmem_label_update(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_pmem * nspm, int pos, long unsigned int flags)
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
