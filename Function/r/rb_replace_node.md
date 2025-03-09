# Function: <code>rb_replace_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582973440,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:537",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "security/apparmor/label.c:__label_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973440,
      "name": "rb_replace_node",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262416,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:537",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "security/apparmor/label.c:__label_replace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262416,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583381184,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:552",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "security/apparmor/label.c:__label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381184,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588231472,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:554",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231472,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588780512,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:589",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/rbtree.c:rb_replace_node_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588780512,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589159584,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:589",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/rbtree.c:rb_replace_node_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159584,
      "name": "rb_replace_node",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589389520,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:589",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_expire",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "lib/rbtree.c:rb_replace_node_cached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589389520,
      "name": "rb_replace_node",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589845232,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589845232,
      "name": "rb_replace_node",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590071328,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590071328,
      "name": "rb_replace_node",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069152,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069152,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585218496,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218496,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585101344,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "security/landlock/ruleset.c:insert_rule",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585101344,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585549744,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "security/landlock/ruleset.c:insert_rule",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585549744,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706000,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "security/landlock/ruleset.c:insert_rule",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706000,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595867936,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "fs/xattr.c:simple_xattr_set",
        "security/apparmor/label.c:aa_label_replace",
        "security/landlock/ruleset.c:insert_rule",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595867936,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596385424,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "fs/xattr.c:simple_xattr_set",
        "security/apparmor/label.c:aa_label_replace",
        "security/landlock/ruleset.c:insert_rule",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596385424,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597280672,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:alloc_stable_node_chain",
        "fs/xattr.c:simple_xattr_set",
        "security/apparmor/label.c:aa_label_replace",
        "security/landlock/ruleset.c:insert_rule",
        "drivers/gpu/drm/drm_mm.c:drm_mm_replace_node",
        "drivers/gpu/drm/drm_mm.c:drm_mm_replace_node",
        "drivers/gpu/drm/drm_mm.c:drm_mm_replace_node",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597280672,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503850304,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503850304,
      "name": "rb_replace_node",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236470008,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236470008,
      "name": "rb_replace_node",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297704304,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297704304,
      "name": "rb_replace_node",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279739460,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279739460,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589673584,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589673584,
      "name": "rb_replace_node",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399376,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399376,
      "name": "rb_replace_node",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116960,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116960,
      "name": "rb_replace_node",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void rb_replace_node(struct rb_node * victim, struct rb_node * new, struct rb_root * root)
```

```json
{
  "name": "rb_replace_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590167344,
      "name": "rb_replace_node",
      "external": true,
      "loc": "lib/rbtree.c:553",
      "file": "lib/rbtree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:alloc_stable_node_chain",
        "security/apparmor/label.c:aa_label_replace",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590167344,
      "name": "rb_replace_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
