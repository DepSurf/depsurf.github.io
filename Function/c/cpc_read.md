# Function: <code>cpc_read</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243073,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:882",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243073,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584319792,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:887",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584319792,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719280,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:939",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719280,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584946864,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:968",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946864,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050832,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:968",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050832,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585255024,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:964",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585255024,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392928,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:966",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392928,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586101824,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:948",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586101824,
      "name": "cpc_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586222240,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:934",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222240,
      "name": "cpc_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586096832,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:926",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586096832,
      "name": "cpc_read.isra.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586595920,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:926",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586595920,
      "name": "cpc_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:976",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857680,
      "name": "cpc_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071594287145,
      "name": "cpc_read.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:979",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202000,
      "name": "cpc_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071596222836,
      "name": "cpc_read.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:980",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589496304,
      "name": "cpc_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071596750582,
      "name": "cpc_read.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:983",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803968,
      "name": "cpc_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071597658217,
      "name": "cpc_read.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497666416,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:966",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497666416,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178448,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:966",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178448,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585120144,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:966",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585120144,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585343328,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:966",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343328,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```

```json
{
  "name": "cpc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585450640,
      "name": "cpc_read",
      "external": false,
      "loc": "drivers/acpi/cppc_acpi.c:966",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_perf_caps",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf",
        "drivers/acpi/cppc_acpi.c:cppc_get_desired_perf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585450640,
      "name": "cpc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```
</details>
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
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
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cpc_read(int cpu, struct cpc_register_resource * reg_res, u64 * val)
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
