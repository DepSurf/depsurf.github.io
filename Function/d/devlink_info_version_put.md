# Function: <code>devlink_info_version_put</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3910",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584064,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 18446744071588618600,
      "name": "devlink_info_version_put.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588802368,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802368,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688544,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:4391",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688544,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589720976,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:5080",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589720976,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589596640,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:5283",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596640,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590345968,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:5893",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590345968,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591940032,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:6388",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591940032,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value, enum devlink_info_version_type version_type)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593748112,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:6902",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put_ext",
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put_ext",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593748112,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value, enum devlink_info_version_type version_type)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595900096,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/devlink/dev.c:667",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_info_version_running_put_ext",
        "net/devlink/dev.c:devlink_info_version_running_put",
        "net/devlink/dev.c:devlink_info_version_stored_put_ext",
        "net/devlink/dev.c:devlink_info_version_stored_put",
        "net/devlink/dev.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595900096,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value, enum devlink_info_version_type version_type)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596684432,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/devlink/dev.c:768",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_info_version_running_put_ext",
        "net/devlink/dev.c:devlink_info_version_running_put",
        "net/devlink/dev.c:devlink_info_version_stored_put_ext",
        "net/devlink/dev.c:devlink_info_version_stored_put",
        "net/devlink/dev.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596684432,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502375360,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502375360,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
```

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235110272,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235110272,
      "name": "devlink_info_version_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295908768,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295908768,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278591708,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278591708,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588408752,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408752,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588121440,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588121440,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588740928,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588740928,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_info_version_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588881456,
      "name": "devlink_info_version_put",
      "external": false,
      "loc": "net/core/devlink.c:3964",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_info_version_running_put",
        "net/core/devlink.c:devlink_info_version_stored_put",
        "net/core/devlink.c:devlink_info_version_fixed_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588881456,
      "name": "devlink_info_version_put.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum devlink_info_version_type version_type</code>
</li>
</ul>
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int devlink_info_version_put(struct devlink_info_req * req, int attr, const char * version_name, const char * version_value)
```
</details>
</li>
</ul>
