# Function: <code>virtnet_send_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool virtnet_send_command(struct virtnet_info * vi, u8 class, u8 cmd, struct scatterlist * out)
```

```json
{
  "name": "virtnet_send_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077968,
      "name": "virtnet_send_command",
      "external": false,
      "loc": "drivers/net/virtio_net.c:981",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_mac_address",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_config_changed_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077968,
      "name": "virtnet_send_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool virtnet_send_command(struct virtnet_info * vi, u8 class, u8 cmd, struct scatterlist * out)
```

```json
{
  "name": "virtnet_send_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585469408,
      "name": "virtnet_send_command",
      "external": false,
      "loc": "drivers/net/virtio_net.c:927",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_config_changed_work",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585469408,
      "name": "virtnet_send_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool virtnet_send_command(struct virtnet_info * vi, u8 class, u8 cmd, struct scatterlist * out)
```

```json
{
  "name": "virtnet_send_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591743488,
      "name": "virtnet_send_command",
      "external": false,
      "loc": "drivers/net/virtio_net.c:2262",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_config_changed_work",
        "drivers/net/virtio_net.c:virtnet_set_coalesce",
        "drivers/net/virtio_net.c:virtnet_set_coalesce",
        "drivers/net/virtio_net.c:virtnet_commit_rss_command",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591743488,
      "name": "virtnet_send_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
bool virtnet_send_command(struct virtnet_info * vi, u8 class, u8 cmd, struct scatterlist * out)
```

```json
{
  "name": "virtnet_send_command",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592487088,
      "name": "virtnet_send_command",
      "external": false,
      "loc": "drivers/net/virtio_net.c:2514",
      "file": "drivers/net/virtio_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_config_changed_work",
        "drivers/net/virtio_net.c:virtnet_set_coalesce",
        "drivers/net/virtio_net.c:virtnet_send_rx_notf_coal_cmds",
        "drivers/net/virtio_net.c:virtnet_commit_rss_command",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid",
        "drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:virtnet_set_rx_mode",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_set_mac_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592487088,
      "name": "virtnet_send_command",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
bool virtnet_send_command(struct virtnet_info * vi, u8 class, u8 cmd, struct scatterlist * out)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool virtnet_send_command(struct virtnet_info * vi, u8 class, u8 cmd, struct scatterlist * out)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
