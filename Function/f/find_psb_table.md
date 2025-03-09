# Function: <code>find_psb_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585890793,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:629",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586290608,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:629",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586290608,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1683
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586494832,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:629",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586494832,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1689
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586619605,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:629",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
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
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587102645,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:629",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:625",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399600,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
    },
    {
      "addr": 18446744071587403429,
      "name": "find_psb_table.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:625",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587579968,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1416
    },
    {
      "addr": 18446744071587583409,
      "name": "find_psb_table.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853040,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1346
    },
    {
      "addr": 18446744071587859025,
      "name": "find_psb_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588057856,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1346
    },
    {
      "addr": 18446744071588063809,
      "name": "find_psb_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588923152,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071588925532,
      "name": "find_psb_table.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588935584,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071591599777,
      "name": "find_psb_table.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823520,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071591543325,
      "name": "find_psb_table.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589517392,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 775
    },
    {
      "addr": 18446744071592658815,
      "name": "find_psb_table.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591006624,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071594543772,
      "name": "find_psb_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592714400,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592714400,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593151280,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593151280,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593904832,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593904832,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 896
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587682848,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1346
    },
    {
      "addr": 18446744071587688801,
      "name": "find_psb_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587459184,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1299
    },
    {
      "addr": 18446744071587463193,
      "name": "find_psb_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588014000,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1346
    },
    {
      "addr": 18446744071588019953,
      "name": "find_psb_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
int find_psb_table(struct powernow_k8_data * data)
```

```json
{
  "name": "find_psb_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "find_psb_table",
      "external": false,
      "loc": "drivers/cpufreq/powernow-k8.c:622",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588129472,
      "name": "find_psb_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1346
    },
    {
      "addr": 18446744071588135425,
      "name": "find_psb_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int find_psb_table(struct powernow_k8_data * data)
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
