# Function: <code>proc_dostring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401456,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:1904",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401456,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413360,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2024",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413360,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433664,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2009",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433664,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421616,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2033",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:seccomp_actions_logged_handler",
        "kernel/seccomp.c:seccomp_actions_logged_handler",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421616,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579449376,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2025",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:seccomp_actions_logged_handler",
        "kernel/seccomp.c:seccomp_actions_logged_handler",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449376,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464304,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2030",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464304,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497968,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2078",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497968,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516096,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2128",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516096,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542160,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542160,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579574016,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:359",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574016,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579555632,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:358",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555632,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560256,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:370",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560256,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579633200,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:379",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633200,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579729984,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:259",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/coredump.c:proc_dostring_coredump",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/cdrom/cdrom.c:cdrom_sysctl_info",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579729984,
      "name": "proc_dostring",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579859872,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:261",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/coredump.c:proc_dostring_coredump",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/cdrom/cdrom.c:cdrom_sysctl_info",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579859872,
      "name": "proc_dostring",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910048,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:260",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "fs/coredump.c:proc_dostring_coredump",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/cdrom/cdrom.c:cdrom_sysctl_info",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910048,
      "name": "proc_dostring",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949296,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:260",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "fs/coredump.c:proc_dostring_coredump",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/cdrom/cdrom.c:cdrom_sysctl_info",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949296,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490700032,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490700032,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224758696,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224758696,
      "name": "proc_dostring",
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283517456,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283517456,
      "name": "proc_dostring",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271422210,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271422210,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515824,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515824,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444624,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444624,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515744,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515744,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
int proc_dostring(struct ctl_table * table, int write, void * buffer, size_t * lenp, loff_t * ppos)
```

```json
{
  "name": "proc_dostring",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548704,
      "name": "proc_dostring",
      "external": true,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/printk/printk.c:devkmsg_sysctl_set_loglvl",
        "kernel/seccomp.c:read_actions_logged",
        "kernel/utsname_sysctl.c:proc_do_uts_string",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "drivers/char/random.c:proc_do_uuid",
        "net/core/sysctl_net_core.c:proc_do_rss_key",
        "net/core/sysctl_net_core.c:set_default_qdisc",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key",
        "net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control",
        "net/ipv4/sysctl_net_ipv4.c:proc_tcp_congestion_control",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548704,
      "name": "proc_dostring",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
