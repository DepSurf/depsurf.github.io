# Function: <code>devlink_dpipe_table_register</code>

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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6027",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588618349,
      "name": "devlink_dpipe_table_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071588574320,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588791744,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588791744,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589676032,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:7661",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676032,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589704544,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:8549",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589704544,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589583424,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:8808",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589583424,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590330016,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:9653",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590330016,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591919936,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:10517",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591919936,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502362528,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502362528,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235100296,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235100296,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295905984,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295905984,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278579074,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278579074,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588398128,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588398128,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588110816,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588110816,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588730304,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588730304,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
```

```json
{
  "name": "devlink_dpipe_table_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588870672,
      "name": "devlink_dpipe_table_register",
      "external": true,
      "loc": "net/core/devlink.c:6724",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588870672,
      "name": "devlink_dpipe_table_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int devlink_dpipe_table_register(struct devlink * devlink, const char * table_name, struct devlink_dpipe_table_ops * table_ops, void * priv, bool counter_control_extern)
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
