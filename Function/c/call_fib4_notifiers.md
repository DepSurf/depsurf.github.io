# Function: <code>call_fib4_notifiers</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588160208,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160208,
      "name": "call_fib4_notifiers",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588515296,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588515296,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588710416,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710416,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129168,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129168,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353312,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353312,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590333824,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:__fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590333824,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590386560,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590386560,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590302864,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590302864,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592729296,
      "name": "call_fib4_notifiers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591090240,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:19",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594615736,
      "name": "call_fib4_notifiers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592741008,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:19",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596350593,
      "name": "call_fib4_notifiers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594612096,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:19",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596879545,
      "name": "call_fib4_notifiers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595004048,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:19",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597803674,
      "name": "call_fib4_notifiers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595816720,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502993832,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502993832,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235683736,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235683736,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296682496,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296682496,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279069916,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279069916,
      "name": "call_fib4_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588959488,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588959488,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588671424,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588671424,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589395872,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395872,
      "name": "call_fib4_notifiers",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```

```json
{
  "name": "call_fib4_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589438960,
      "name": "call_fib4_notifiers",
      "external": true,
      "loc": "net/ipv4/fib_notifier.c:20",
      "file": "net/ipv4/fib_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_sync_up",
        "net/ipv4/fib_semantics.c:fib_sync_down_dev",
        "net/ipv4/fib_trie.c:call_fib_entry_notifiers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589438960,
      "name": "call_fib4_notifiers",
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int call_fib4_notifiers(struct net * net, enum fib_event_type event_type, struct fib_notifier_info * info)
```
</details>
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
