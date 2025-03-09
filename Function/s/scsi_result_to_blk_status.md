# Function: <code>scsi_result_to_blk_status</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586120640,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:733",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120640,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586265888,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:640",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265888,
      "name": "scsi_result_to_blk_status",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586509728,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586509728,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586657664,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586657664,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447424,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:617",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447424,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587515392,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:620",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515392,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587407120,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:587",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587407120,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587975040,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:592",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975040,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589330704,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:594",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589330704,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
blk_status_t scsi_result_to_blk_status(int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590901408,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:593",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590901408,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
blk_status_t scsi_result_to_blk_status(int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591242224,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:590",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242224,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
blk_status_t scsi_result_to_blk_status(int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591589472,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:588",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591589472,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499554848,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499554848,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232019280,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232019280,
      "name": "scsi_result_to_blk_status",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292851168,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292851168,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276754468,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276754468,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586348144,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348144,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586189472,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189472,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586605632,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586605632,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```

```json
{
  "name": "scsi_result_to_blk_status",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586718032,
      "name": "scsi_result_to_blk_status",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:633",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:scsi_io_completion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718032,
      "name": "scsi_result_to_blk_status",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd * cmd, int result)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct scsi_cmnd * cmd</code>
</li>
<li>
<b>Param reordered. </b>
<code>cmd, result</code> ➡️ <code>result</code>
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
