# Function: <code>netlink_has_listeners</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586492640,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1952",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586492640,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586937856,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1259",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937856,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587133040,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1276",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133040,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587263360,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1310",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263360,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587782384,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1323",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587782384,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588124768,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1362",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124768,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588307632,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1355",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588307632,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588705600,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1347",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588705600,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588929488,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588929488,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589819744,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "lib/kobject_uevent.c:uevent_net_broadcast_untagged",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589819744,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589855936,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1349",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "lib/kobject_uevent.c:uevent_net_broadcast_untagged",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589855936,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589761024,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1359",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589761024,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590520128,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1364",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590520128,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592125136,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1364",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_userspace_pm_active"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592125136,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593948096,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1384",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_userspace_pm_active",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593948096,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594324384,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1384",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_userspace_pm_active",
        "net/handshake/netlink.c:handshake_genl_notify",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594324384,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595123952,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1386",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/sock.c:__sk_free",
        "net/core/netdev-genl.c:netdev_genl_dev_notify",
        "net/core/page_pool_user.c:netdev_nl_page_pool_event",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_del_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/sched/cls_api.c:__tcf_chain_put",
        "net/sched/act_api.c:tcf_action_add",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_action_reoffload_cb",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "net/devlink/port.c:devlink_port_notify",
        "net/devlink/region.c:devlink_nl_region_notify",
        "net/devlink/rate.c:devlink_rate_notify",
        "net/devlink/linecard.c:devlink_linecard_notify",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_userspace_pm_active",
        "net/handshake/netlink.c:handshake_genl_notify",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595123952,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502522600,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502522600,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235233288,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235233288,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296091296,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296091296,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278693952,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278693952,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588535872,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535872,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588247872,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588247872,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588868048,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/netfilter/nfnetlink.c:nfnetlink_has_listeners",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588868048,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int netlink_has_listeners(struct sock * sk, unsigned int group)
```

```json
{
  "name": "netlink_has_listeners",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589009536,
      "name": "netlink_has_listeners",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/sock.c:__sk_free",
        "net/xfrm/xfrm_state.c:xfrm_replay_timer_handler",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp",
        "net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn",
        "net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009536,
      "name": "netlink_has_listeners",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
