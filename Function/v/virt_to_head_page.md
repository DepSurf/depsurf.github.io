# Function: <code>virt_to_head_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579396026,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:500",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580501109,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:500",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_page_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580651404,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:500",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_add",
        "mm/list_lru.c:list_lru_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580846683,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:500",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:ksize",
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585076304,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:500",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:free_unused_bufs",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586232123,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:500",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:build_skb",
        "net/core/skbuff.c:skb_gro_receive"
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
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579408397,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:553",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580579855,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:553",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_page_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580760639,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:553",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580986835,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:553",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:ksize",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132396,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:553",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585473491,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:553",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:remove_vq_common",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:try_fill_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586657164,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:553",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579428701,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:540",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580646399,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:540",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580825867,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:540",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060643,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:540",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:ksize",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free_bulk",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207452,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:540",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586842015,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:540",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579416401,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:596",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580678719,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:596",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868001,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:596",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110019,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:596",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255839,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:596",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586950515,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:596",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579444433,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:613",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580763507,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:613",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959233,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:613",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216243,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:613",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388127,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:613",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587442253,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:613",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579459246,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580901253,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093550,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370308,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538735,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587746669,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587998176,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589115188,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:655",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579492894,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580980325,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581171646,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454948,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624812,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586592374,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880779,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588157734,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589349253,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:683",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579510668,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581242736,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402997,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567174,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673397,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737169,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582179295,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586845603,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588185882,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588479129,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589809334,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:749",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579536732,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581301184,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463989,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632294,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581757150,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582257685,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586997091,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588391258,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588684537,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590033542,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579566476,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581668613,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850297,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:cache_from_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976574,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582499602,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587804587,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589252953,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589553195,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591063958,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:839",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547820,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581717989,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886667,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026462,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582557410,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862351,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589252121,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589560973,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589581467,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591127305,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:872",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579552812,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581521155,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_dump_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738357,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917323,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582052897,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586273,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587740612,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589146860,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589460109,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589478587,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591057577,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:895",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579625372,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581780391,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_dump_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015301,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582213225,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359706,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582905256,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588335860,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589866998,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590197325,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590217355,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591900244,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:898",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * virt_to_head_page(const void * x)
```

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720917,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582441413,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594107840,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "io_uring/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_mmap"
      ]
    },
    {
      "addr": 18446744071589739014,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591394206,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591760217,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591775302,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591794036,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593615300,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:844",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594107840,
      "name": "virt_to_head_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579848581,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582950149,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586749391,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_uring_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591373798,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593158910,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593552184,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593567185,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593588052,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595544593,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:955",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579898805,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583167205,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587011015,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587102934,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "io_uring/kbuf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591731603,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591771914,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_rq_free_unused_buf",
        "drivers/net/virtio_net.c:virtnet_rq_free_unused_buf",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:xdp_linearize_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593613734,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594022512,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594036141,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594061095,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1200",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk"
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
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579937509,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583350693,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587296606,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592475423,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_napi_alloc_frags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592512115,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:receive_mergeable_xdp",
        "drivers/net/virtio_net.c:mergeable_buf_free",
        "drivers/net/virtio_net.c:receive_small",
        "drivers/net/virtio_net.c:receive_small_xdp",
        "drivers/net/virtio_net.c:xdp_linearize_page",
        "drivers/net/virtio_net.c:virtnet_rq_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594388794,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:napi_build_skb",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594809122,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594823421,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "net/core/gro.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro.c:skb_gro_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594851090,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:1283",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_put_page_bulk"
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
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490680460,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492709192,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492872256,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493080804,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493210780,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493826888,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499991680,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499997488,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/ethernet/broadcom/bgmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501906628,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502240720,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503779184,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224751192,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226546040,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3226671420,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3226790360,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3226841096,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3227330272,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3232523788,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 3234667992,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234985636,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 3236399876,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283506320,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286045568,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286265280,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286525912,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286720548,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287446120,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293317484,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295318576,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295732404,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297620788,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271417374,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272708116,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272815258,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272939624,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272987446,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273402544,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277065682,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278220018,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278481774,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279689060,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579510396,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581270032,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432837,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581601030,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725886,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582226421,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586754115,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587998042,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588291273,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589637142,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579439196,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581216688,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375253,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542374,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664686,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582164261,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586621331,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587711146,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588004089,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589361670,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579510316,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581261232,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424037,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592342,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717198,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582216901,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586951651,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588329818,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588623097,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590079174,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_head_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543148,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581325147,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581488485,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:page_frag_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658102,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:__ksize",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:kmem_cache_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581784878,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:__mod_lruvec_slab_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294917,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_mmap",
        "fs/io_uring.c:io_mem_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587054105,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588465274,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_gro_receive",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:build_skb_around",
        "net/core/skbuff.c:build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588761089,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_release_frame",
        "net/core/xdp.c:__xdp_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590128646,
      "name": "virt_to_head_page",
      "external": false,
      "loc": "include/linux/mm.h:744",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_mmap"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct page * virt_to_head_page(const void * x)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct page * virt_to_head_page(const void * x)
```
</details>
</li>
</ul>
