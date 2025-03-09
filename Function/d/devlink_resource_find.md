# Function: <code>devlink_resource_find</code>

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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588569280,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2392",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588569280,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588786336,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588786336,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589680059,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2426",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589678848,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 978
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589709659,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2758",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589708448,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 978
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589595243,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2961",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594048,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590344747,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:3523",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590343376,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591932283,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:4038",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591930688,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593737403,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:4303",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devl_resource_size_get",
        "net/core/devlink.c:devl_resource_register",
        "net/core/devlink.c:devl_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devl_resource_size_get",
        "net/core/devlink.c:devl_resource_register",
        "net/core/devlink.c:devl_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593735392,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595841103,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/devlink/leftover.c:3521",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_resource_occ_get_unregister",
        "net/devlink/leftover.c:devlink_resource_occ_get_register",
        "net/devlink/leftover.c:devl_resource_size_get",
        "net/devlink/leftover.c:devl_resource_register",
        "net/devlink/leftover.c:devl_resource_register",
        "net/devlink/leftover.c:devlink_nl_cmd_resource_set"
      ],
      "caller_func": [
        "net/devlink/leftover.c:devlink_resource_occ_get_unregister",
        "net/devlink/leftover.c:devlink_resource_occ_get_register",
        "net/devlink/leftover.c:devl_resource_size_get",
        "net/devlink/leftover.c:devl_resource_register",
        "net/devlink/leftover.c:devl_resource_register",
        "net/devlink/leftover.c:devlink_nl_cmd_resource_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595839136,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596724623,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/devlink/resource.c:39",
      "file": "net/devlink/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/resource.c:devlink_resource_occ_get_unregister",
        "net/devlink/resource.c:devlink_resource_occ_get_register",
        "net/devlink/resource.c:devl_resource_size_get",
        "net/devlink/resource.c:devl_resource_register",
        "net/devlink/resource.c:devl_resource_register",
        "net/devlink/resource.c:devlink_nl_resource_set_doit"
      ],
      "caller_func": [
        "net/devlink/resource.c:devlink_resource_occ_get_unregister",
        "net/devlink/resource.c:devlink_resource_occ_get_register",
        "net/devlink/resource.c:devl_resource_size_get",
        "net/devlink/resource.c:devl_resource_register",
        "net/devlink/resource.c:devl_resource_register",
        "net/devlink/resource.c:devlink_nl_resource_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596722656,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502355984,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502355984,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235093364,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235093364,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295881072,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295881072,
      "name": "devlink_resource_find",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278573576,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278573576,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392720,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392720,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105408,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105408,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588724896,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588724896,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
```

```json
{
  "name": "devlink_resource_find",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588865312,
      "name": "devlink_resource_find",
      "external": false,
      "loc": "net/core/devlink.c:2394",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_resource_occ_get_unregister",
        "net/core/devlink.c:devlink_resource_occ_get_register",
        "net/core/devlink.c:devlink_resource_size_get",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_resource_register",
        "net/core/devlink.c:devlink_nl_cmd_resource_set",
        "net/core/devlink.c:devlink_resource_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865312,
      "name": "devlink_resource_find",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
struct devlink_resource * devlink_resource_find(struct devlink * devlink, struct devlink_resource * resource, u64 resource_id)
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
