# Function: <code>dpm_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584449824,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:225",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:dpm_wait_fn",
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449824,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584786064,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:227",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786064,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584977728,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:229",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977728,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062400,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:231",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062400,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585485232,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:231",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485232,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585729792,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:227",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585729792,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585862496,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:228",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585862496,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586099392,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_for_suppliers",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586099392,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586246912,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586246912,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587016719,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:239",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587101343,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:239",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586987647,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:240",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587553775,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:237",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588887855,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:236",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590397551,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:236",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590715119,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:236",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591077087,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:236",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499066464,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499066464,
      "name": "dpm_wait",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231619856,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231619856,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292242080,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292242080,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586008640,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008640,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585856240,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856240,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586196928,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586196928,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586305600,
      "name": "dpm_wait",
      "external": false,
      "loc": "drivers/base/power/main.c:235",
      "file": "drivers/base/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_pm_wait_for_dev",
        "drivers/base/power/main.c:dpm_wait_for_subordinate",
        "drivers/base/power/main.c:dpm_wait_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586305600,
      "name": "dpm_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dpm_wait(struct device * dev, bool async)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void dpm_wait(struct device * dev, bool async)
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
