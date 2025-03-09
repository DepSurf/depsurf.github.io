# Function: <code>tcp_collapse_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586637166,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4653",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587079888,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4716",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_collapse",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587267984,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4757",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267984,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587400608,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4717",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400608,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587922080,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4676",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922080,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270992,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4785",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270992,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588459120,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4809",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588459120,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588865088,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4816",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865088,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589089584,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589089584,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590053568,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4908",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590053568,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590098592,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5047",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590098592,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590012496,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5055",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012496,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590783552,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5089",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590783552,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592415776,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5119",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592415776,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594268000,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5132",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594268000,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594654096,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5137",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594654096,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595458160,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5275",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595458160,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502707704,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502707704,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235406764,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235406764,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296320272,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296320272,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278833576,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278833576,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588695968,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588695968,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588407952,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407952,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589132144,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132144,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
```

```json
{
  "name": "tcp_collapse_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589171968,
      "name": "tcp_collapse_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4867",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589171968,
      "name": "tcp_collapse_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
struct sk_buff * tcp_collapse_one(struct sock * sk, struct sk_buff * skb, struct sk_buff_head * list, struct rb_root * root)
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
