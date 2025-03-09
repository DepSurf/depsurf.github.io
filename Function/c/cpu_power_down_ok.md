# Function: <code>cpu_power_down_ok</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586134368,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134368,
      "name": "cpu_power_down_ok",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586282848,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282848,
      "name": "cpu_power_down_ok",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587051840,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051840,
      "name": "cpu_power_down_ok.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071587052048,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587136416,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136416,
      "name": "cpu_power_down_ok.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    },
    {
      "addr": 18446744071587136608,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023104,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:335",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023104,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587589856,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:336",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587589856,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588926224,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:342",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588926224,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590439760,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:342",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590439760,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590759424,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:342",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590759424,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590004480,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/pmdomain/governor.c:346",
      "file": "drivers/pmdomain/governor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590004480,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499112856,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499112856,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231663084,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231663084,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292301872,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292301872,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586046096,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586046096,
      "name": "cpu_power_down_ok",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585892080,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585892080,
      "name": "cpu_power_down_ok",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586232864,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586232864,
      "name": "cpu_power_down_ok",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
```

```json
{
  "name": "cpu_power_down_ok",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586341904,
      "name": "cpu_power_down_ok",
      "external": false,
      "loc": "drivers/base/power/domain_governor.c:252",
      "file": "drivers/base/power/domain_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586341904,
      "name": "cpu_power_down_ok",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
bool cpu_power_down_ok(struct dev_pm_domain * pd)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool cpu_power_down_ok(struct dev_pm_domain * pd)
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
