# Function: <code>secpath_set</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587749744,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:124",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587749744,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588277792,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:141",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277792,
      "name": "secpath_set",
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
int secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588632800,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:148",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588632800,
      "name": "secpath_set",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588848576,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:112",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588848576,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589283536,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589283536,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589507968,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507968,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590499728,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:115",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590499728,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590559152,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:117",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590559152,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590484512,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:117",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590484512,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591289792,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:117",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289792,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592956368,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:117",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592956368,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594842208,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:119",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594842208,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595233536,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:119",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595233536,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596074016,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:119",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596074016,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503171968,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503171968,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235847568,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235847568,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296898768,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296898768,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279214798,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279214798,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589112336,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589112336,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588837376,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588837376,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589549200,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589549200,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
struct sec_path * secpath_set(struct sk_buff * skb)
```

```json
{
  "name": "secpath_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589596528,
      "name": "secpath_set",
      "external": true,
      "loc": "net/xfrm/xfrm_input.c:114",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_output.c:xfrm_output",
        "net/ipv6/xfrm6_input.c:xfrm6_input_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596528,
      "name": "secpath_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int secpath_set(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct sec_path *</code>
</li>
</ul>
</details>
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
