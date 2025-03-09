# Function: <code>free_cache_attributes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_cache_attributes(unsigned int cpu)
```

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584425040,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:164",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/cacheinfo.c:detect_cache_attributes",
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_cpu_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425040,
      "name": "free_cache_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void free_cache_attributes(unsigned int cpu)
```

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584760816,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:164",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_sysfs_init",
        "drivers/base/cacheinfo.c:cacheinfo_cpu_callback",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584760816,
      "name": "free_cache_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void free_cache_attributes(unsigned int cpu)
```

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584950768,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:293",
      "file": "drivers/base/cacheinfo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950768,
      "name": "free_cache_attributes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585035948,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:293",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585035648,
      "name": "free_cache_attributes.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585458780,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:306",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585458512,
      "name": "free_cache_attributes.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585702332,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:292",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702064,
      "name": "free_cache_attributes.part.5",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585830588,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:286",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585830320,
      "name": "free_cache_attributes.part.6",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586065611,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586065328,
      "name": "free_cache_attributes.part.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213499,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213216,
      "name": "free_cache_attributes.part.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_cache_attributes(unsigned int cpu)
```

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978752,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down",
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978752,
      "name": "free_cache_attributes",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_cache_attributes(unsigned int cpu)
```

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587065312,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down",
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065312,
      "name": "free_cache_attributes",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_cache_attributes(unsigned int cpu)
```

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586949120,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down",
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949120,
      "name": "free_cache_attributes",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587514094,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587513888,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588841679,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588841456,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590344367,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:330",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down",
        "drivers/base/cacheinfo.c:detect_cache_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590343744,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590664431,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:458",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591026079,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:461",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499020812,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499020328,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231582616,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231582264,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292183536,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292182864,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276388354,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276387870,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585973707,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585973424,
      "name": "free_cache_attributes.part.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585822971,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585822688,
      "name": "free_cache_attributes.part.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586163515,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163232,
      "name": "free_cache_attributes.part.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_cache_attributes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586272219,
      "name": "free_cache_attributes",
      "external": false,
      "loc": "drivers/base/cacheinfo.c:291",
      "file": "drivers/base/cacheinfo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ],
      "caller_func": [
        "drivers/base/cacheinfo.c:cacheinfo_cpu_pre_down"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586271936,
      "name": "free_cache_attributes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void free_cache_attributes(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void free_cache_attributes(unsigned int cpu)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void free_cache_attributes(unsigned int cpu)
```
</details>
</li>
</ul>
