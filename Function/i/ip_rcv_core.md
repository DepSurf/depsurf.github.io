# Function: <code>ip_rcv_core</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588368608,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:421",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368608,
      "name": "ip_rcv_core.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588771312,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588771312,
      "name": "ip_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588994944,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994944,
      "name": "ip_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589953056,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:435",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953056,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589993856,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:435",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589993856,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 733
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589907632,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:436",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589907632,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590673888,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:436",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590673888,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592300624,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:451",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300624,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594136864,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:456",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594136864,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594523936,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:456",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594523936,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595326640,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:456",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595326640,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502599592,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502599592,
      "name": "ip_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235305580,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235305580,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296191424,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296191424,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```

```json
{
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278752086,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278752086,
      "name": "ip_rcv_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
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
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588601328,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588601328,
      "name": "ip_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588313312,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313312,
      "name": "ip_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589037504,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037504,
      "name": "ip_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
  "name": "ip_rcv_core",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589076512,
      "name": "ip_rcv_core",
      "external": false,
      "loc": "net/ipv4/ip_input.c:420",
      "file": "net/ipv4/ip_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_input.c:ip_list_rcv",
        "net/ipv4/ip_input.c:ip_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589076512,
      "name": "ip_rcv_core.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct sk_buff * ip_rcv_core(struct sk_buff * skb, struct net * net)
```
</details>
</li>
</ul>
