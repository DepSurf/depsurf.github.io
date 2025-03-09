# Function: <code>__rtnl_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586357252,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:74",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/rtnetlink.c:rtnetlink_rcv_msg",
        "net/core/rtnetlink.c:rtnl_newlink"
      ],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/sched/ematch.c:tcf_em_tree_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380256,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586813296,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:84",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnetlink_rcv_msg",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/sched/ematch.c:tcf_em_tree_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813296,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587001104,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:84",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnetlink_rcv_msg",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type",
        "net/sched/ematch.c:tcf_em_tree_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001104,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587126128,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:86",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnetlink_rcv_msg",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587126128,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587630096,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:86",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587630096,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587940352,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:97",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940352,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588088224,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:97",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588088224,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588403216,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588403216,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588609600,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588609600,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589450322,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589467968,
      "name": "__rtnl_unlock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589451602,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/dev.c:netdev_wait_allrefs",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469056,
      "name": "__rtnl_unlock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589348642,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589367488,
      "name": "__rtnl_unlock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590079246,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097952,
      "name": "__rtnl_unlock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591626979,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:94",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648272,
      "name": "__rtnl_unlock",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593409556,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:95",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593431408,
      "name": "__rtnl_unlock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593873652,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:98",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593896368,
      "name": "__rtnl_unlock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594656877,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:99",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister"
      ],
      "caller_func": [
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/dev.c:netdev_wait_allrefs_any",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594679664,
      "name": "__rtnl_unlock",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502155976,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502155976,
      "name": "__rtnl_unlock",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234898796,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234898796,
      "name": "__rtnl_unlock",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295624880,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295624880,
      "name": "__rtnl_unlock",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278411124,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278411124,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216336,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216336,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587929168,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929168,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548160,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548160,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void __rtnl_unlock()
```

```json
{
  "name": "__rtnl_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588685648,
      "name": "__rtnl_unlock",
      "external": true,
      "loc": "net/core/rtnetlink.c:92",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:default_device_exit_batch",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/dev.c:netdev_run_todo",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_link_unregister",
        "net/core/lwtunnel.c:lwtunnel_valid_encap_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588685648,
      "name": "__rtnl_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
