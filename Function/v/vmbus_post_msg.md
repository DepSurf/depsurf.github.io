# Function: <code>vmbus_post_msg</code>

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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int vmbus_post_msg(void * buffer, size_t buflen, bool can_sleep)
```

```json
{
  "name": "vmbus_post_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmbus_post_msg",
      "external": true,
      "loc": "drivers/hv/connection.c:393",
      "file": "drivers/hv/connection.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/connection.c:vmbus_negotiate_version",
        "drivers/hv/channel.c:vmbus_close_internal",
        "drivers/hv/channel.c:vmbus_teardown_gpadl",
        "drivers/hv/channel.c:vmbus_establish_gpadl",
        "drivers/hv/channel.c:vmbus_establish_gpadl",
        "drivers/hv/channel.c:vmbus_send_tl_connect_request",
        "drivers/hv/channel.c:__vmbus_open",
        "drivers/hv/channel_mgmt.c:vmbus_request_offers",
        "drivers/hv/channel_mgmt.c:vmbus_initiate_unload",
        "drivers/hv/channel_mgmt.c:vmbus_release_relid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587563248,
      "name": "vmbus_post_msg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587561536,
      "name": "vmbus_post_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int vmbus_post_msg(void * buffer, size_t buflen, bool can_sleep)
```
</details>
</li>
</ul>
