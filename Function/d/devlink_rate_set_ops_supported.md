# Function: <code>devlink_rate_set_ops_supported</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool devlink_rate_set_ops_supported(const struct devlink_ops * ops, struct genl_info * info, enum devlink_rate_type type)
```

```json
{
  "name": "devlink_rate_set_ops_supported",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590369173,
      "name": "devlink_rate_set_ops_supported",
      "external": false,
      "loc": "net/core/devlink.c:1713",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_rate_new_doit"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590314000,
      "name": "devlink_rate_set_ops_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
bool devlink_rate_set_ops_supported(const struct devlink_ops * ops, struct genl_info * info, enum devlink_rate_type type)
```

```json
{
  "name": "devlink_rate_set_ops_supported",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591967429,
      "name": "devlink_rate_set_ops_supported",
      "external": false,
      "loc": "net/core/devlink.c:1916",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_rate_new_doit"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591900656,
      "name": "devlink_rate_set_ops_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
bool devlink_rate_set_ops_supported(const struct devlink_ops * ops, struct genl_info * info, enum devlink_rate_type type)
```

```json
{
  "name": "devlink_rate_set_ops_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593704576,
      "name": "devlink_rate_set_ops_supported",
      "external": false,
      "loc": "net/core/devlink.c:2191",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_rate_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593704576,
      "name": "devlink_rate_set_ops_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
bool devlink_rate_set_ops_supported(const struct devlink_ops * ops, struct genl_info * info, enum devlink_rate_type type)
```

```json
{
  "name": "devlink_rate_set_ops_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595817856,
      "name": "devlink_rate_set_ops_supported",
      "external": false,
      "loc": "net/devlink/leftover.c:1563",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_nl_cmd_rate_new_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595817856,
      "name": "devlink_rate_set_ops_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
bool devlink_rate_set_ops_supported(const struct devlink_ops * ops, struct genl_info * info, enum devlink_rate_type type)
```

```json
{
  "name": "devlink_rate_set_ops_supported",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596768288,
      "name": "devlink_rate_set_ops_supported",
      "external": false,
      "loc": "net/devlink/rate.c:394",
      "file": "net/devlink/rate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/rate.c:devlink_nl_rate_new_doit",
        "net/devlink/rate.c:devlink_nl_rate_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596768288,
      "name": "devlink_rate_set_ops_supported",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool devlink_rate_set_ops_supported(const struct devlink_ops * ops, struct genl_info * info, enum devlink_rate_type type)
```
</details>
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
