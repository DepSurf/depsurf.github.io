# Function: <code>cros_ec_send_command</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int cros_ec_send_command(struct cros_ec_device * ec_dev, struct cros_ec_command * msg)
```

```json
{
  "name": "cros_ec_send_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592941840,
      "name": "cros_ec_send_command",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:181",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info_legacy",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592941840,
      "name": "cros_ec_send_command",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int cros_ec_send_command(struct cros_ec_device * ec_dev, struct cros_ec_command * msg)
```

```json
{
  "name": "cros_ec_send_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593391600,
      "name": "cros_ec_send_command",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:181",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info_legacy",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593391600,
      "name": "cros_ec_send_command",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int cros_ec_send_command(struct cros_ec_device * ec_dev, struct cros_ec_command * msg)
```

```json
{
  "name": "cros_ec_send_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594136864,
      "name": "cros_ec_send_command",
      "external": false,
      "loc": "drivers/platform/chrome/cros_ec_proto.c:181",
      "file": "drivers/platform/chrome/cros_ec_proto.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info_legacy",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info",
        "drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594136864,
      "name": "cros_ec_send_command",
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int cros_ec_send_command(struct cros_ec_device * ec_dev, struct cros_ec_command * msg)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
