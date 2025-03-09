# Function: <code>jiffies_to_clock_t</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579807376,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:629",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:do_notify_parent",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807376,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835184,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:636",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:do_notify_parent",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835184,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864240,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:636",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:do_notify_parent",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "kernel/sys.c:do_sys_times",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864240,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872464,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:726",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872464,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915872,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:693",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr.c:__ipmr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/ip6mr.c:__ip6mr_fill_mroute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915872,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960512,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:705",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960512,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007088,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:643",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007088,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050640,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050640,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099696,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099696,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162080,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:621",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_openreq4",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:get_timewait6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_openreq6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162080,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146224,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:621",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_openreq4",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:get_timewait6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_openreq6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146224,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150912,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:621",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150912,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295440,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:621",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295440,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580504192,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:621",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504192,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757536,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:621",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757536,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840208,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:621",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840208,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580929632,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:662",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_ioctl.c:scsi_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/tcp_ipv4.c:get_tcp4_sock",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/nexthop.c:nla_put_nh_group_res",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock",
        "net/ipv6/tcp_ipv6.c:get_tcp6_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580929632,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491310944,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491310944,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225310160,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225310160,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284236768,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284236768,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271819772,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271819772,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068896,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068896,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013712,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "drivers/net/vxlan.c:vxlan_fdb_info",
        "drivers/net/vxlan.c:vxlan_fdb_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013712,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059968,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059968,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
clock_t jiffies_to_clock_t(long unsigned int x)
```

```json
{
  "name": "jiffies_to_clock_t",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110784,
      "name": "jiffies_to_clock_t",
      "external": true,
      "loc": "kernel/time/time.c:711",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/neighbour.c:neigh_fill_info",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/core/rtnetlink.c:rtnl_put_cacheinfo",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/tcp_ipv4.c:tcp4_seq_show",
        "net/ipv4/igmp.c:igmp_mc_seq_show",
        "net/ipv4/ipmr_base.c:mr_fill_mroute",
        "net/ipv6/addrconf.c:inet6_addr_modify",
        "net/ipv6/addrconf.c:inet6_addr_add",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/route.c:rtm_to_fib6_config",
        "net/ipv6/mcast.c:igmp6_mc_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show",
        "net/ipv6/tcp_ipv6.c:tcp6_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110784,
      "name": "jiffies_to_clock_t",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
