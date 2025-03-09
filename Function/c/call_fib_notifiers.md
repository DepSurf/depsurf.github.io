# Function: <code>call_fib_notifiers</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587485270,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_trie.c:189",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ],
      "caller_func": [
        "net/ipv4/fib_rules.c:fib4_rule_delete",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493520,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587635840,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:19",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_rules.c:fib4_rule_delete",
        "net/ipv4/fib_rules.c:fib4_rule_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587635840,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669152,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:21",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:call_ipmr_mfc_entry_notifiers",
        "net/ipv4/ipmr.c:call_ipmr_vif_entry_notifiers",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669152,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996144,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:24",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996144,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588155504,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:24",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588155504,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588477024,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:24",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477024,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588682448,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588682448,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589548240,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589548240,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589557200,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589557200,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589455152,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589455152,
      "name": "call_fib_notifiers",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590192592,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192592,
      "name": "call_fib_notifiers",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591755744,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591755744,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593546560,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593546560,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594015632,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594015632,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594802000,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:29",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594802000,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502237064,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502237064,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234982016,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234982016,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295727888,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295727888,
      "name": "call_fib_notifiers",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278478724,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278478724,
      "name": "call_fib_notifiers",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289184,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289184,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002000,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002000,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621008,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621008,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588758800,
      "name": "call_fib_notifiers",
      "external": true,
      "loc": "net/core/fib_notifier.c:31",
      "file": "net/core/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/fib_rules.c:fib_nl_delrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/ipv4/fib_notifier.c:call_fib4_notifiers",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:vif_add",
        "net/ipv4/ipmr.c:vif_delete",
        "net/ipv6/fib6_notifier.c:call_fib6_notifiers",
        "net/ipv6/ip6mr.c:ip6_mroute_setsockopt",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:mif6_delete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588758800,
      "name": "call_fib_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int call_fib_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```
</details>
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
