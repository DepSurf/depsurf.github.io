# Function: <code>__reset_control_release</code>

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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584552178,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:312",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_put_internal"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584962608,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:412",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962608,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585195504,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:442",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585195504,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585314096,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:442",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314096,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585525328,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:581",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585525328,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585666336,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666336,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586393278,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:581",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_array_put"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586508414,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:655",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_array_put"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586393484,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:792",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_bulk_put",
        "drivers/reset/core.c:__reset_control_bulk_get"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586920092,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:792",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_bulk_put",
        "drivers/reset/core.c:__reset_control_bulk_get"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588212490,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:793",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_bulk_put",
        "drivers/reset/core.c:__reset_control_bulk_get"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589620650,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:793",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_bulk_put",
        "drivers/reset/core.c:__reset_control_bulk_get"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589924170,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:793",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_bulk_put",
        "drivers/reset/core.c:__reset_control_bulk_get"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590262888,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:793",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_put_internal"
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
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498333944,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_put_internal"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231026180,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_put_internal"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291513384,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_put_internal"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276021328,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:of_reset_control_array_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276021328,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585427360,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427360,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585297408,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585297408,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585616736,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585616736,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __reset_control_release(struct kref * kref)
```

```json
{
  "name": "__reset_control_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585724864,
      "name": "__reset_control_release",
      "external": false,
      "loc": "drivers/reset/core.c:580",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724864,
      "name": "__reset_control_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void __reset_control_release(struct kref * kref)
```
</details>
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
void __reset_control_release(struct kref * kref)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __reset_control_release(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __reset_control_release(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __reset_control_release(struct kref * kref)
```
</details>
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
