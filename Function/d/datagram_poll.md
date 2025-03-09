# Function: <code>datagram_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236624,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:752",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:netlink_poll",
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236624,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
unsigned int datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665248,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:774",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665248,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
unsigned int datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586850320,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:794",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586850320,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
unsigned int datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586971936,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:822",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971936,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
unsigned int datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587470128,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:836",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587470128,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587775088,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:834",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587775088,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587907312,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:761",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907312,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216432,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216432,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421264,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421264,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589286096,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:764",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286096,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589284608,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:797",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284608,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178512,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:797",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178512,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589901072,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:797",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589901072,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591429568,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:795",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591429568,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593196992,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:797",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593196992,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593656368,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:805",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593656368,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594434320,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:878",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/xfrm/espintcp.c:espintcp_poll",
        "net/packet/af_packet.c:packet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594434320,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501937464,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501937464,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234695272,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234695272,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295354320,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295354320,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278242990,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278242990,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588028048,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028048,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587741136,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741136,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588359824,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588359824,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
__poll_t datagram_poll(struct file * file, struct socket * sock, poll_table * wait)
```

```json
{
  "name": "datagram_poll",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588495376,
      "name": "datagram_poll",
      "external": true,
      "loc": "net/core/datagram.c:760",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_poll",
        "net/packet/af_packet.c:packet_poll",
        "net/xdp/xsk.c:xsk_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588495376,
      "name": "datagram_poll",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
