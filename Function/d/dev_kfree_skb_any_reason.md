# Function: <code>dev_kfree_skb_any_reason</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void dev_kfree_skb_any_reason(struct sk_buff * skb, enum skb_drop_reason reason)
```

```json
{
  "name": "dev_kfree_skb_any_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593717392,
      "name": "dev_kfree_skb_any_reason",
      "external": true,
      "loc": "net/core/dev.c:3160",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/net_failover.c:net_failover_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593717392,
      "name": "dev_kfree_skb_any_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void dev_kfree_skb_any_reason(struct sk_buff * skb, enum skb_drop_reason reason)
```

```json
{
  "name": "dev_kfree_skb_any_reason",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594498832,
      "name": "dev_kfree_skb_any_reason",
      "external": true,
      "loc": "net/core/dev.c:3163",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit",
        "drivers/net/net_failover.c:net_failover_start_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:netpoll_start_xmit",
        "net/8021q/vlan_core.c:vlan_do_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594498832,
      "name": "dev_kfree_skb_any_reason",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void dev_kfree_skb_any_reason(struct sk_buff * skb, enum skb_drop_reason reason)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
