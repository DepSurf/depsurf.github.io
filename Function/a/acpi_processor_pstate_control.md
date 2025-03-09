# Function: <code>acpi_processor_pstate_control</code>

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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226821,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:467",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226821,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584299184,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:465",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584299184,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584698288,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:465",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698288,
      "name": "acpi_processor_pstate_control",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584924480,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:466",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924480,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585028384,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:466",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028384,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585232144,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:453",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232144,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585368848,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:439",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585368848,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586076832,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:439",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586076832,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586198272,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:438",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198272,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586073488,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:437",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586073488,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586568656,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:435",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_notify_smm",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586568656,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587827904,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:435",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_notify_smm",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827904,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589169184,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:432",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_notify_smm",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589169184,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589462768,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:454",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_notify_smm",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589462768,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589770768,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:454",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_notify_smm",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589770768,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497643704,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:439",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497643704,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168320,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:439",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168320,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585082560,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:439",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082560,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585320432,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:439",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320432,
      "name": "acpi_processor_pstate_control",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_pstate_control()
```

```json
{
  "name": "acpi_processor_pstate_control",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585426576,
      "name": "acpi_processor_pstate_control",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:439",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585426576,
      "name": "acpi_processor_pstate_control",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int acpi_processor_pstate_control()
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
int acpi_processor_pstate_control()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_pstate_control()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_pstate_control()
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
