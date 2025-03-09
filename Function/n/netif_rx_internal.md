# Function: <code>netif_rx_internal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586288960,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:3533",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_forward_skb",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx_ni"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586288960,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586716192,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:3786",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586716192,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586902832,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:3782",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902832,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587028032,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:3868",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028032,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587539168,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4050",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587539168,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587843248,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4171",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843248,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587976976,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4480",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976976,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588278432,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4494",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278432,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588484112,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588484112,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589358480,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4758",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589358480,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364064,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4787",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364064,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589259456,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4895",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb_nomtu",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589259456,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589985280,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4886",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb_nomtu",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589985280,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591515600,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4927",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:dev_forward_skb_nomtu",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591515600,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593290048,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4914",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:dev_forward_skb_nomtu",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593290048,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593745632,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4889",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:dev_forward_skb_nomtu",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593745632,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594524576,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:5037",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_rx",
        "net/core/dev.c:dev_forward_skb_nomtu",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594524576,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502016904,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502016904,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234750284,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234750284,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295453104,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295453104,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278306150,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278306150,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588090896,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588090896,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587803808,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803808,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422672,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422672,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int netif_rx_internal(struct sk_buff * skb)
```

```json
{
  "name": "netif_rx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588558080,
      "name": "netif_rx_internal",
      "external": false,
      "loc": "net/core/dev.c:4396",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_rx_ni",
        "net/core/dev.c:netif_rx",
        "net/core/dev.c:dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588558080,
      "name": "netif_rx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
