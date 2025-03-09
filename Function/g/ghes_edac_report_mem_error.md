# Function: <code>ghes_edac_report_mem_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": false,
      "loc": "include/acpi/ghes.h:59",
      "file": "drivers/acpi/apei/ghes.c",
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
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": false,
      "loc": "include/acpi/ghes.h:59",
      "file": "drivers/acpi/apei/ghes.c",
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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": false,
      "loc": "include/acpi/ghes.h:59",
      "file": "drivers/acpi/apei/ghes.c",
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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": false,
      "loc": "include/acpi/ghes.h:65",
      "file": "drivers/acpi/apei/ghes.c",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(struct ghes * ghes, int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587047824,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:175",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_do_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587047824,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3786
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587346288,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:184",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587346288,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3787
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587524512,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:198",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524512,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4112
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587798368,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:196",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587798368,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4303
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588003088,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:204",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588003088,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4344
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588857280,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:202",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588857280,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3730
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:238",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591595360,
      "name": "ghes_edac_report_mem_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588872224,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4097
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:238",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591538508,
      "name": "ghes_edac_report_mem_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588758944,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4084
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:238",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592652412,
      "name": "ghes_edac_report_mem_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589450400,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4081
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:270",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594536981,
      "name": "ghes_edac_report_mem_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071590929728,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1165
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
int ghes_edac_report_mem_error(struct notifier_block * nb, long unsigned int val, void * data)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592631776,
      "name": "ghes_edac_report_mem_error",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:269",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592631776,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1190
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
int ghes_edac_report_mem_error(struct notifier_block * nb, long unsigned int val, void * data)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593062416,
      "name": "ghes_edac_report_mem_error",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:269",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593062416,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1190
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
int ghes_edac_report_mem_error(struct notifier_block * nb, long unsigned int val, void * data)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593814304,
      "name": "ghes_edac_report_mem_error",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:269",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593814304,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1190
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501249768,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:204",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501249768,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2964
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587959232,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:204",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959232,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4344
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```

```json
{
  "name": "ghes_edac_report_mem_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588074576,
      "name": "ghes_edac_report_mem_error",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:204",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588074576,
      "name": "ghes_edac_report_mem_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4369
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
void ghes_edac_report_mem_error(struct ghes * ghes, int sev, struct cper_sec_mem_err * mem_err)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ghes * ghes</code>
</li>
<li>
<b>Param reordered. </b>
<code>ghes, sev, mem_err</code> ➡️ <code>sev, mem_err</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct notifier_block * nb</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int val</code>
</li>
<li>
<b>Param added. </b>
<code>void * data</code>
</li>
<li>
<b>Param removed. </b>
<code>int sev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cper_sec_mem_err * mem_err</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err * mem_err)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
