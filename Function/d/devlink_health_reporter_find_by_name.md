# Function: <code>devlink_health_reporter_find_by_name</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588571296,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4594",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588571296,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787984,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787984,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589671383,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:5166",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589699419,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:5870",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589580967,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:6073",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590335399,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:6686",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591925892,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:7178",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593731711,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:7733",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595910212,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/devlink/health.c:93",
      "file": "net/devlink/health.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_reporter_get_from_attrs",
        "net/devlink/health.c:devl_health_reporter_create"
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
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596744340,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/devlink/health.c:93",
      "file": "net/devlink/health.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_reporter_get_from_attrs",
        "net/devlink/health.c:devl_health_reporter_create"
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502358064,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502358064,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235096204,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235096204,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295884672,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295884672,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278575414,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278575414,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394368,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394368,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588107056,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588107056,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726544,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726544,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```

```json
{
  "name": "devlink_health_reporter_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866960,
      "name": "devlink_health_reporter_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4649",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_health_reporter_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866960,
      "name": "devlink_health_reporter_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_find_by_name(struct devlink * devlink, const char * reporter_name)
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
