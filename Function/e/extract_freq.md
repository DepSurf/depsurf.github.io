# Function: <code>extract_freq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int extract_freq(u32 val, struct acpi_cpufreq_data * data)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585882144,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:238",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu",
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585882144,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586282416,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:236",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282416,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586486624,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:239",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586486624,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611104,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:239",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611104,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587094160,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:239",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587094160,
      "name": "extract_freq",
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587392336,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:239",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587392336,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587572288,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:244",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572288,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587848192,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:227",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587848192,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588053008,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:227",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053008,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588913680,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:230",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913680,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588926320,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:231",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588926320,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588814512,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:231",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588814512,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589507552,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:231",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507552,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590991792,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:231",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590991792,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592697984,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:236",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592697984,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593128944,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:237",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593128944,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593882112,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:237",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593882112,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587678000,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:227",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587678000,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587451472,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:227",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451472,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588009152,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:227",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009152,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```

```json
{
  "name": "extract_freq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588124592,
      "name": "extract_freq",
      "external": false,
      "loc": "drivers/cpufreq/acpi-cpufreq.c:227",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_target",
        "drivers/cpufreq/acpi-cpufreq.c:get_cur_freq_on_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124592,
      "name": "extract_freq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpufreq_policy * policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_cpufreq_data * data</code>
</li>
<li>
<b>Param reordered. </b>
<code>val, data</code> ➡️ <code>policy, val</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int extract_freq(struct cpufreq_policy * policy, u32 val)
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
