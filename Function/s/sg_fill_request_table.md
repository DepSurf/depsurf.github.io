# Function: <code>sg_fill_request_table</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585545622,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:832",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585977318,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:832",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586225745,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:869",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586366271,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:869",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586610626,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586758066,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void sg_fill_request_table(Sg_fd * sfp, sg_req_info_t * rinfo)
```

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587548560,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:858",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548560,
      "name": "sg_fill_request_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void sg_fill_request_table(Sg_fd * sfp, sg_req_info_t * rinfo)
```

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587615152,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:858",
      "file": "drivers/scsi/sg.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sg.c:sg_ioctl_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587615152,
      "name": "sg_fill_request_table",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587511662,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:857",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl_common"
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
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588087863,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:861",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl_common"
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
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589452901,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:857",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl_common"
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
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591030645,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:857",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl_common"
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
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591384117,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:857",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl_common"
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
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591734692,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:857",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl_common"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499675036,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232123584,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293001492,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276848288,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586448546,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586324790,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586712626,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sg_fill_request_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586818765,
      "name": "sg_fill_request_table",
      "external": false,
      "loc": "drivers/scsi/sg.c:864",
      "file": "drivers/scsi/sg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_ioctl"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void sg_fill_request_table(Sg_fd * sfp, sg_req_info_t * rinfo)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void sg_fill_request_table(Sg_fd * sfp, sg_req_info_t * rinfo)
```
</details>
</li>
</ul>
