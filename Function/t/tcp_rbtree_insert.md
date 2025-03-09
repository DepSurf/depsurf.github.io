# Function: <code>tcp_rbtree_insert</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587270886,
      "name": "tcp_rbtree_insert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4775",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587402645,
      "name": "tcp_rbtree_insert",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4735",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587946576,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4694",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587946576,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588296448,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4803",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296448,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588485280,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4827",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588485280,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588892576,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4834",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588892576,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589116656,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116656,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590060410,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4926",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590091328,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590105411,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5065",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137408,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590018960,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5073",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590051632,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590790040,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5107",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590825232,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592423864,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5137",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592458400,
      "name": "tcp_rbtree_insert",
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594276840,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5150",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594312688,
      "name": "tcp_rbtree_insert",
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594663701,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5155",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594699104,
      "name": "tcp_rbtree_insert",
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595467556,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:5293",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595503600,
      "name": "tcp_rbtree_insert",
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502732584,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502732584,
      "name": "tcp_rbtree_insert",
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235436320,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235436320,
      "name": "tcp_rbtree_insert",
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296354832,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296354832,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278858392,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278858392,
      "name": "tcp_rbtree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588723040,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723040,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588435024,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588435024,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589159216,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159216,
      "name": "tcp_rbtree_insert",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
```

```json
{
  "name": "tcp_rbtree_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589199184,
      "name": "tcp_rbtree_insert",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:4885",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_fragment",
        "net/ipv4/tcp_output.c:tcp_event_new_data_sent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589199184,
      "name": "tcp_rbtree_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void tcp_rbtree_insert(struct rb_root * root, struct sk_buff * skb)
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
