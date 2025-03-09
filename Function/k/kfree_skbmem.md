# Function: <code>kfree_skbmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586206304,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:616",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:kfree_skb",
        "net/core/skbuff.c:consume_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586206304,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586627120,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586627120,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586811920,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586811920,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586940864,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:616",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586940864,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587429440,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:576",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429440,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587734976,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:576",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734976,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587869104,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:583",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869104,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588172688,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588172688,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588377888,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377888,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247424,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:616",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247424,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246272,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:630",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246272,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589141712,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:678",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141712,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861584,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:694",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861584,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591387008,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:694",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387008,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593150912,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:868",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:kfree_skb_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593150912,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593604672,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:959",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593604672,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594378864,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:1045",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594378864,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501895376,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501895376,
      "name": "kfree_skbmem",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234658280,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234658280,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295309200,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295309200,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278213936,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278213936,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587984672,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587984672,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697776,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697776,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588316448,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588316448,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void kfree_skbmem(struct sk_buff * skb)
```

```json
{
  "name": "kfree_skbmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588451584,
      "name": "kfree_skbmem",
      "external": false,
      "loc": "net/core/skbuff.c:617",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__consume_stateless_skb",
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451584,
      "name": "kfree_skbmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
