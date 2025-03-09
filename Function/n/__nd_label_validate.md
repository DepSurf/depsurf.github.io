# Function: <code>__nd_label_validate</code>

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
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585364490,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:75",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_validate"
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
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585792588,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:77",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_validate"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586039155,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:91",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_validate"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586179246,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:92",
      "file": "drivers/nvdimm/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586413904,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
    },
    {
      "addr": 18446744071586424280,
      "name": "__nd_label_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586560544,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586560544,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587344928,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344928,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587406464,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406464,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587288400,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288400,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855184,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1151
    },
    {
      "addr": 18446744071592522560,
      "name": "__nd_label_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:94",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589206336,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
    },
    {
      "addr": 18446744071594393014,
      "name": "__nd_label_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:94",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590761936,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1189
    },
    {
      "addr": 18446744071596256983,
      "name": "__nd_label_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:94",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591103376,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    },
    {
      "addr": 18446744071596785131,
      "name": "__nd_label_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:94",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591448656,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    },
    {
      "addr": 18446744071597694066,
      "name": "__nd_label_validate.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499450200,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499450200,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292709120,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292709120,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1452
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276673362,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276673362,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586251024,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251024,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586069392,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586069392,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586508512,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586508512,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```

```json
{
  "name": "__nd_label_validate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586620256,
      "name": "__nd_label_validate",
      "external": false,
      "loc": "drivers/nvdimm/label.c:86",
      "file": "drivers/nvdimm/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620256,
      "name": "__nd_label_validate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1170
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata * ndd)
```
</details>
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
int __nd_label_validate(struct nvdimm_drvdata * ndd)
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
