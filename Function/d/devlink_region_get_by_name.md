# Function: <code>devlink_region_get_by_name</code>

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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588572176,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:351",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572176,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588788272,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788272,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589692693,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:362",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589725013,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:370",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589602213,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:373",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590357605,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:448",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591949717,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:651",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593756066,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:805",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devl_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595857671,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/devlink/leftover.c:558",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devl_region_create",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_new",
        "net/devlink/leftover.c:devlink_nl_cmd_region_del",
        "net/devlink/leftover.c:devlink_nl_cmd_region_get_doit"
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
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596737287,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/devlink/region.c:35",
      "file": "net/devlink/region.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/region.c:devl_region_create",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_new_doit",
        "net/devlink/region.c:devlink_nl_region_del_doit",
        "net/devlink/region.c:devlink_nl_region_get_doit"
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502358400,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502358400,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235096484,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235096484,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295886320,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295886320,
      "name": "devlink_region_get_by_name",
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278575666,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278575666,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394656,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394656,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588107344,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588107344,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726832,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726832,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
```

```json
{
  "name": "devlink_region_get_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588867248,
      "name": "devlink_region_get_by_name",
      "external": false,
      "loc": "net/core/devlink.c:354",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588867248,
      "name": "devlink_region_get_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
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
struct devlink_region * devlink_region_get_by_name(struct devlink * devlink, const char * region_name)
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
