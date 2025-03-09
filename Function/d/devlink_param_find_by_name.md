# Function: <code>devlink_param_find_by_name</code>

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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588572272,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2885",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588572272,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588788368,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588788368,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589715596,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:3050",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
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
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589744460,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:3595",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
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
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589629804,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:3798",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
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
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590380829,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4383",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_param_register_one",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
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
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591915732,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:4913",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_param_unregister",
        "net/core/devlink.c:devlink_param_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
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
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593720164,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:5437",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_param_unregister",
        "net/core/devlink.c:devlink_param_register",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink_param_item * devlink_param_find_by_name(struct xarray * params, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595816960,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/devlink/leftover.c:3920",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devl_params_register",
        "net/devlink/leftover.c:devl_params_register",
        "net/devlink/leftover.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595816960,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct devlink_param_item * devlink_param_find_by_name(struct xarray * params, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596726464,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/devlink/param.c:125",
      "file": "net/devlink/param.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/param.c:devl_params_register",
        "net/devlink/param.c:devl_params_register",
        "net/devlink/param.c:devlink_nl_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596726464,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502358528,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502358528,
      "name": "devlink_param_find_by_name",
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235096588,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_param_unregister_one",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235096588,
      "name": "devlink_param_find_by_name",
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295886896,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295886896,
      "name": "devlink_param_find_by_name",
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278575770,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278575770,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588394752,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588394752,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588107440,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588107440,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588726928,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726928,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```

```json
{
  "name": "devlink_param_find_by_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588867344,
      "name": "devlink_param_find_by_name",
      "external": false,
      "loc": "net/core/devlink.c:2917",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588867344,
      "name": "devlink_param_find_by_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
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
struct devlink_param_item * devlink_param_find_by_name(struct list_head * param_list, const char * param_name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct devlink_param_item * devlink_param_find_by_name(struct xarray * params, const char * param_name)
```
</details>
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
