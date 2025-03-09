# Function: <code>copy_page_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583026832,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:462",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026832,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322304,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:417",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322304,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583447680,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:657",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447680,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583463984,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:714",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463984,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583644848,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:716",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644848,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583862704,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:846",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583862704,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946544,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:892",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583946544,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132573,
      "name": "copy_page_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071584123328,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 567
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584248640,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248640,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584661248,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:927",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/process_vm_access.c:process_vm_rw_single_vec",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_from_iter",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584661248,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584771552,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:934",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_from_iter",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584771552,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584807600,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:1004",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807600,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:851",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_user_iov",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592323399,
      "name": "copy_page_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071585230112,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586075360,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:903",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586075360,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587052208,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:743",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052208,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587308305,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:531",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596639706,
      "name": "copy_page_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587308256,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587596657,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:411",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/ioctl.c:fuse_do_ioctl",
        "block/blk-map.c:bio_copy_from_iter",
        "net/core/datagram.c:skb_copy_datagram_from_iter",
        "net/ipv4/tcp_output.c:tcp_send_syn_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597548234,
      "name": "copy_page_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587596608,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496126592,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496126592,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229454948,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "drivers/net/tun.c:tun_get_user",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229454948,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1188
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290385600,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290385600,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275187190,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275187190,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584217376,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584217376,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584152592,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152592,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584201136,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201136,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
size_t copy_page_from_iter(struct page * page, size_t offset, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_page_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584305648,
      "name": "copy_page_from_iter",
      "external": true,
      "loc": "lib/iov_iter.c:906",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/fuse/file.c:fuse_do_ioctl",
        "block/bio.c:bio_copy_user_iov",
        "net/core/datagram.c:skb_copy_datagram_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305648,
      "name": "copy_page_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
