# Function: <code>__devlink_params_register</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6302",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588612656,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    },
    {
      "addr": 18446744071588619722,
      "name": "__devlink_params_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588835568,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835568,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589715408,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:7944",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589715408,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589744272,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:8832",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589744272,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589629616,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:9095",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589629616,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590380208,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:9956",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590380208,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502408480,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502408480,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235145048,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235145048,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295956496,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295956496,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1596
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278616564,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278616564,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588441952,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588441952,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588154640,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154640,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774128,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774128,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
```

```json
{
  "name": "__devlink_params_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588914656,
      "name": "__devlink_params_register",
      "external": false,
      "loc": "net/core/devlink.c:6999",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_params_register",
        "net/core/devlink.c:devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588914656,
      "name": "__devlink_params_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int __devlink_params_register(struct devlink * devlink, unsigned int port_index, struct list_head * param_list, const struct devlink_param * params, size_t params_count, enum devlink_command reg_cmd, enum devlink_command unreg_cmd)
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
