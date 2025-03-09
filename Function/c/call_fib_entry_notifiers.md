# Function: <code>call_fib_entry_notifiers</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_info * fi, u8 tos, u8 type, u32 tb_id, u32 nlflags)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587485264,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:197",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587485264,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587633146,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:103",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588157691,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:103",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588503008,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:104",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588503008,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588698080,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:104",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588698080,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589115792,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589115792,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589339872,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589339872,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590322264,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:91",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:__fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590374985,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:91",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590291376,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:91",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591075968,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:91",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592725661,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594596589,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594988347,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595800843,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:93",
      "file": "net/ipv4/fib_trie.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_trie.c:fib_notify_alias_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502979568,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502979568,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235669264,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235669264,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296664032,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296664032,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279057486,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279057486,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588946048,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588946048,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588657984,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657984,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589382432,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589382432,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589425392,
      "name": "call_fib_entry_notifiers",
      "external": false,
      "loc": "net/ipv4/fib_trie.c:92",
      "file": "net/ipv4/fib_trie.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_info_notify_update",
        "net/ipv4/fib_trie.c:fib_table_flush",
        "net/ipv4/fib_trie.c:fib_table_delete",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert",
        "net/ipv4/fib_trie.c:fib_table_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589425392,
      "name": "call_fib_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_info * fi, u8 tos, u8 type, u32 tb_id, u32 nlflags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_info * fi, u8 tos, u8 type, u32 tb_id, u32 nlflags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int call_fib_entry_notifiers(struct net * net, enum fib_event_type event_type, u32 dst, int dst_len, struct fib_alias * fa, struct netlink_ext_ack * extack)
```
</details>
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
