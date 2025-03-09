# Function: <code>round_jiffies_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579809824,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:333",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_rq_timed_out_timer",
        "block/blk-mq.c:blk_mq_rq_timer",
        "drivers/net/tun.c:tun_flow_cleanup",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809824,
      "name": "round_jiffies_up",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837808,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:431",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837808,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579866864,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:431",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866864,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876368,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:434",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876368,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919616,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:434",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_timeout_work",
        "block/blk-mq.c:blk_mq_timeout_work",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919616,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966288,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:451",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_timeout_work",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966288,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012944,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:450",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012944,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057088,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:450",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057088,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106144,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106144,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580175376,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_get_transaction",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580175376,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580159248,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:455",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_get_transaction",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580159248,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580163856,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:456",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:jbd2_get_transaction",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163856,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580308480,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:456",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580308480,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580521776,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:479",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521776,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777248,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:479",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777248,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580860304,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:479",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860304,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950608,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:479",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950608,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491325088,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491325088,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225313532,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225313532,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284244448,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284244448,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271822652,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271822652,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075344,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075344,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020160,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020160,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066416,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066416,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
long unsigned int round_jiffies_up(long unsigned int j)
```

```json
{
  "name": "round_jiffies_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117184,
      "name": "round_jiffies_up",
      "external": true,
      "loc": "kernel/time/timer.c:454",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/jbd2/transaction.c:start_this_handle",
        "block/blk-timeout.c:blk_add_timer",
        "block/blk-timeout.c:blk_add_timer",
        "drivers/net/tun.c:tun_flow_update",
        "drivers/net/tun.c:tun_flow_cleanup",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117184,
      "name": "round_jiffies_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
