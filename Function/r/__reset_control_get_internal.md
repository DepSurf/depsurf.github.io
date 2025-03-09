# Function: <code>__reset_control_get_internal</code>

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
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:279",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:379",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585196630,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:409",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_from_lookup"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585313350,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:409",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:__reset_control_get_from_lookup"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585526251,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:539",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585667309,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586392144,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:539",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__reset_control_get_from_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392144,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586507280,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:613",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__reset_control_get_from_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507280,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391696,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:747",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391696,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:748",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918272,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071592445439,
      "name": "__reset_control_get_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:749",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211152,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071594313468,
      "name": "__reset_control_get_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:749",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589619248,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    },
    {
      "addr": 18446744071596232290,
      "name": "__reset_control_get_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:749",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589922784,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071596760199,
      "name": "__reset_control_get_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:749",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590261280,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071597668749,
      "name": "__reset_control_get_internal.cold",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498332448,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__reset_control_get",
        "drivers/reset/core.c:__of_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498332448,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231024756,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__reset_control_get",
        "drivers/reset/core.c:__of_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231024756,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291517024,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__reset_control_get",
        "drivers/reset/core.c:__of_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291517024,
      "name": "__reset_control_get_internal",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276020232,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/reset/core.c:__reset_control_get",
        "drivers/reset/core.c:__of_reset_control_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276020232,
      "name": "__reset_control_get_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585428333,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585298381,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585617709,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reset_control_get_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585725837,
      "name": "__reset_control_get_internal",
      "external": false,
      "loc": "drivers/reset/core.c:538",
      "file": "drivers/reset/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct reset_control * __reset_control_get_internal(struct reset_controller_dev * rcdev, unsigned int index, bool shared, bool acquired)
```
</details>
</li>
</ul>
