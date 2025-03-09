# Function: <code>xfrm_inner_mode_input</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589284160,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284160,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589508592,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589508592,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2210
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
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590502880,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:432",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590502880,
      "name": "xfrm_inner_mode_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590562480,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:434",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590562480,
      "name": "xfrm_inner_mode_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590487792,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:434",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590487792,
      "name": "xfrm_inner_mode_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591292176,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:434",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591292176,
      "name": "xfrm_inner_mode_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592960361,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:434",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
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
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594846389,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:435",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
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
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595237528,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:423",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
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
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596078222,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:423",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503173264,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503173264,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
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
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235848272,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235848272,
      "name": "xfrm_inner_mode_input",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296899792,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296899792,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2760
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279215400,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279215400,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1980
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589112960,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589112960,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588838000,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588838000,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589549824,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589549824,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xfrm_inner_mode_input",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589597280,
      "name": "xfrm_inner_mode_input",
      "external": false,
      "loc": "net/xfrm/xfrm_input.c:430",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589597280,
      "name": "xfrm_inner_mode_input.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2226
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state * x, const struct xfrm_mode * inner_mode, struct sk_buff * skb)
```
</details>
</li>
</ul>
