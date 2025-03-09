# Function: <code>skb_copy_ubufs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211312,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:949",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_hard_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211312,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586638112,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:954",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638112,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 739
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586823648,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:954",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586823648,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586947392,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:956",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586947392,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587447040,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1173",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587447040,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1468
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587752080,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1174",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587752080,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1450
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587885472,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1183",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885472,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1465
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588190656,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588190656,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1495
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588395824,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395824,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1505
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589258496,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1341",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589258496,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1381
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589257632,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1352",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589257632,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1379
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589149648,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1394",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149648,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1341
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589869776,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1415",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589869776,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1369
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591399632,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1409",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591399632,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1697
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593164576,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1607",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593164576,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1691
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1751",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596851734,
      "name": "skb_copy_ubufs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071593617936,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2127
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1839",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/netkit.c:netkit_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:__skb_tstamp_tx",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776630,
      "name": "skb_copy_ubufs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071594393120,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2111
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501911888,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501911888,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1416
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234672780,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234672780,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1260
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295326000,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295326000,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1912
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278224764,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278224764,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002608,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002608,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1505
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715696,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715696,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1505
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588334384,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588334384,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1505
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
int skb_copy_ubufs(struct sk_buff * skb, gfp_t gfp_mask)
```

```json
{
  "name": "skb_copy_ubufs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588469872,
      "name": "skb_copy_ubufs",
      "external": true,
      "loc": "net/core/skbuff.c:1342",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_clone",
        "net/core/skbuff.c:skb_zerocopy_clone",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:dev_queue_xmit_nit",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/filter.c:__bpf_redirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588469872,
      "name": "skb_copy_ubufs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1498
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
