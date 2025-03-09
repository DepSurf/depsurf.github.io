# Function: <code>devlink_nl_region_notify</code>

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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3547",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_nl_cmd_region_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586592,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071588618626,
      "name": "devlink_nl_region_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588808416,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588808416,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589691808,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3781",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del",
        "net/core/devlink.c:__devlink_region_snapshot_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589691808,
      "name": "devlink_nl_region_notify",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589724016,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:4340",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_port_region_create",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del",
        "net/core/devlink.c:__devlink_region_snapshot_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724016,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589601120,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:4543",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_port_region_create",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del",
        "net/core/devlink.c:__devlink_region_snapshot_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589601120,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590356512,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:5144",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_port_region_create",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del",
        "net/core/devlink.c:__devlink_region_snapshot_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590356512,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591948480,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:5637",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_port_region_create",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_region_snapshot_del",
        "net/core/devlink.c:__devlink_region_snapshot_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591948480,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593754400,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:6074",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devl_region_destroy",
        "net/core/devlink.c:devlink_port_region_create",
        "net/core/devlink.c:devl_region_create",
        "net/core/devlink.c:devlink_notify_unregister",
        "net/core/devlink.c:devlink_notify_register",
        "net/core/devlink.c:devlink_region_snapshot_del",
        "net/core/devlink.c:__devlink_region_snapshot_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593754400,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595856000,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/devlink/leftover.c:4546",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devl_region_destroy",
        "net/devlink/leftover.c:devlink_port_region_create",
        "net/devlink/leftover.c:devl_region_create",
        "net/devlink/leftover.c:devlink_notify_unregister",
        "net/devlink/leftover.c:devlink_notify_register",
        "net/devlink/leftover.c:devlink_region_snapshot_del",
        "net/devlink/leftover.c:__devlink_region_snapshot_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595856000,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596735776,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/devlink/region.c:229",
      "file": "net/devlink/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/region.c:devl_region_destroy",
        "net/devlink/region.c:devlink_port_region_create",
        "net/devlink/region.c:devl_region_create",
        "net/devlink/region.c:devlink_region_snapshot_del",
        "net/devlink/region.c:__devlink_region_snapshot_create",
        "net/devlink/region.c:devlink_regions_notify_unregister",
        "net/devlink/region.c:devlink_regions_notify_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596735776,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502380432,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502380432,
      "name": "devlink_nl_region_notify",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235117520,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235117520,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295912288,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295912288,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278593816,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278593816,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588414800,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414800,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588127488,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588127488,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588746976,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588746976,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
```

```json
{
  "name": "devlink_nl_region_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588887504,
      "name": "devlink_nl_region_notify",
      "external": false,
      "loc": "net/core/devlink.c:3586",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_region_snapshot_create",
        "net/core/devlink.c:devlink_region_destroy",
        "net/core/devlink.c:devlink_region_create",
        "net/core/devlink.c:devlink_region_snapshot_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588887504,
      "name": "devlink_nl_region_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
void devlink_nl_region_notify(struct devlink_region * region, struct devlink_snapshot * snapshot, enum devlink_command cmd)
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
