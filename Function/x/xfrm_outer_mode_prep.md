# Function: <code>xfrm_outer_mode_prep</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589299440,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589299440,
      "name": "xfrm_outer_mode_prep",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589523792,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523792,
      "name": "xfrm_outer_mode_prep",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590517808,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:67",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590517808,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590577664,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:67",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590577664,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590503536,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:67",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590503536,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591309152,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:67",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309152,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592976672,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:67",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592976672,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594864512,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:67",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594864512,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595256224,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:68",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595256224,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596096656,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:68",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096656,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503189224,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503189224,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235864836,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235864836,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296920464,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296920464,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279229684,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279229684,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589128160,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589128160,
      "name": "xfrm_outer_mode_prep",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588853184,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588853184,
      "name": "xfrm_outer_mode_prep",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589565024,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589565024,
      "name": "xfrm_outer_mode_prep",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```

```json
{
  "name": "xfrm_outer_mode_prep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589612688,
      "name": "xfrm_outer_mode_prep",
      "external": false,
      "loc": "net/xfrm/xfrm_device.c:50",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589612688,
      "name": "xfrm_outer_mode_prep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void xfrm_outer_mode_prep(struct xfrm_state * x, struct sk_buff * skb)
```
</details>
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
