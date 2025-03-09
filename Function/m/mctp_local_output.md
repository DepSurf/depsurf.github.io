# Function: <code>mctp_local_output</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int mctp_local_output(struct sock * sk, struct mctp_route * rt, struct sk_buff * skb, mctp_eid_t daddr, u8 req_tag)
```

```json
{
  "name": "mctp_local_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_local_output",
      "external": true,
      "loc": "net/mctp/route.c:841",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594643012,
      "name": "mctp_local_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071593766000,
      "name": "mctp_local_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int mctp_local_output(struct sock * sk, struct mctp_route * rt, struct sk_buff * skb, mctp_eid_t daddr, u8 req_tag)
```

```json
{
  "name": "mctp_local_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_local_output",
      "external": true,
      "loc": "net/mctp/route.c:849",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596372212,
      "name": "mctp_local_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071595704912,
      "name": "mctp_local_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int mctp_local_output(struct sock * sk, struct mctp_route * rt, struct sk_buff * skb, mctp_eid_t daddr, u8 req_tag)
```

```json
{
  "name": "mctp_local_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_local_output",
      "external": true,
      "loc": "net/mctp/route.c:849",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596901539,
      "name": "mctp_local_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071596216544,
      "name": "mctp_local_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1051
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int mctp_local_output(struct sock * sk, struct mctp_route * rt, struct sk_buff * skb, mctp_eid_t daddr, u8 req_tag)
```

```json
{
  "name": "mctp_local_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mctp_local_output",
      "external": true,
      "loc": "net/mctp/route.c:859",
      "file": "net/mctp/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mctp/af_mctp.c:mctp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597826880,
      "name": "mctp_local_output.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071597094416,
      "name": "mctp_local_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1167
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int mctp_local_output(struct sock * sk, struct mctp_route * rt, struct sk_buff * skb, mctp_eid_t daddr, u8 req_tag)
```
</details>
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
