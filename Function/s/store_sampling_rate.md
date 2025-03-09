# Function: <code>store_sampling_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585873353,
      "name": "store_sampling_rate",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_ondemand.c:286",
      "file": "drivers/cpufreq/cpufreq_ondemand.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_ondemand.c:store_sampling_rate_gov_sys",
        "drivers/cpufreq/cpufreq_ondemand.c:store_sampling_rate_gov_pol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585876009,
      "name": "store_sampling_rate",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_conservative.c:177",
      "file": "drivers/cpufreq/cpufreq_conservative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_conservative.c:store_sampling_rate_gov_pol",
        "drivers/cpufreq/cpufreq_conservative.c:store_sampling_rate_gov_sys"
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277808,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:46",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277808,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586482000,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:46",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482000,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606592,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:45",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606592,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587089744,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:47",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587089744,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587387840,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:47",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587387840,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587567776,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:47",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587567776,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587843504,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843504,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588048336,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048336,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588908960,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588908960,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588921472,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921472,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588810048,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588810048,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589502688,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589502688,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501317816,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501317816,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233804208,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233804208,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294852592,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294852592,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587673328,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587673328,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447200,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447200,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588004480,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588004480,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```

```json
{
  "name": "store_sampling_rate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588119920,
      "name": "store_sampling_rate",
      "external": true,
      "loc": "drivers/cpufreq/cpufreq_governor.c:44",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588119920,
      "name": "store_sampling_rate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
```
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
ssize_t store_sampling_rate(struct gov_attr_set * attr_set, const char * buf, size_t count)
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
