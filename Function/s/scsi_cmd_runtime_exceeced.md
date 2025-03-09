# Function: <code>scsi_cmd_runtime_exceeced</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_cmd_runtime_exceeced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587515824,
      "name": "scsi_cmd_runtime_exceeced",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:659",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587515824,
      "name": "scsi_cmd_runtime_exceeced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_cmd_runtime_exceeced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587397440,
      "name": "scsi_cmd_runtime_exceeced",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:627",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397440,
      "name": "scsi_cmd_runtime_exceeced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scsi_cmd_runtime_exceeced",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587982033,
      "name": "scsi_cmd_runtime_exceeced",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:627",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_cmd_runtime_exceeced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325408,
      "name": "scsi_cmd_runtime_exceeced",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:669",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325408,
      "name": "scsi_cmd_runtime_exceeced",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_cmd_runtime_exceeced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590891632,
      "name": "scsi_cmd_runtime_exceeced",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:665",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590891632,
      "name": "scsi_cmd_runtime_exceeced",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_cmd_runtime_exceeced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591235056,
      "name": "scsi_cmd_runtime_exceeced",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:664",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235056,
      "name": "scsi_cmd_runtime_exceeced",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_cmd_runtime_exceeced",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591582304,
      "name": "scsi_cmd_runtime_exceeced",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:662",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_complete",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action",
        "drivers/scsi/scsi_lib.c:scsi_io_completion_action"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582304,
      "name": "scsi_cmd_runtime_exceeced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool scsi_cmd_runtime_exceeced(struct scsi_cmnd * cmd)
```
</details>
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
