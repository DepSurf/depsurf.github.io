# Function: <code>prefetchw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void prefetchw(const void * x)
```

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284439,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978329,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_bootmem",
        "mm/page_alloc.c:__free_pages_bootmem"
      ]
    },
    {
      "addr": 18446744071580559172,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581110330,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263705,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871870,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586212295,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586631974,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:685",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_ack"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978329,
      "name": "prefetchw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void prefetchw(const void * x)
```

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579283947,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579694339,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133192,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_bootmem",
        "mm/page_alloc.c:__free_pages_bootmem"
      ]
    },
    {
      "addr": 18446744071580650358,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581275962,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429461,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068189,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586659092,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587093043,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:696",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133192,
      "name": "prefetchw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void prefetchw(const void * x)
```

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579299323,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579721459,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208276,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_bootmem",
        "mm/page_alloc.c:__free_pages_bootmem"
      ]
    },
    {
      "addr": 18446744071580717478,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581354042,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510552,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158221,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586843969,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587290081,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:771",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208276,
      "name": "prefetchw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void prefetchw(const void * x)
```

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579297131,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717307,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702056,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_bootmem",
        "mm/page_alloc.c:__free_pages_bootmem"
      ]
    },
    {
      "addr": 18446744071580753138,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581409389,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563353,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116058,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962753,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587422527,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:784",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702056,
      "name": "prefetchw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void prefetchw(const void * x)
```

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579317786,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579749496,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580787480,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_bootmem",
        "mm/page_alloc.c:__free_pages_bootmem"
      ]
    },
    {
      "addr": 18446744071580840338,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581550989,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707361,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265089,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459985,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:806",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787480,
      "name": "prefetchw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void prefetchw(const void * x)
```

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579328362,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579783855,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920849,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__free_pages_bootmem",
        "mm/page_alloc.c:__free_pages_bootmem"
      ]
    },
    {
      "addr": 18446744071580976872,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581706885,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874141,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453080,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587764305,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:820",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920849,
      "name": "prefetchw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void prefetchw(const void * x)
```

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579353583,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579830425,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996693,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memblock_free_pages",
        "mm/page_alloc.c:memblock_free_pages"
      ]
    },
    {
      "addr": 18446744071581053816,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581793733,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959300,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552573,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587898225,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:815",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996693,
      "name": "prefetchw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369279,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865276,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892266,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118477,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402305,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912341,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091958,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725084,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588204609,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579373519,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913886,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944906,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175517,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463297,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984933,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169334,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582827948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588409697,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591163398,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579958543,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107394,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366803,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668852,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582211813,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406010,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583139702,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589274311,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:826",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591658645,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579946703,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135483,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410355,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709300,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582259317,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458954,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220409,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589274311,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080883,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:746",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591602309,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579954236,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155731,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431648,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730148,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582285061,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483754,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583248304,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589134485,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589552467,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589995372,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:728",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592775285,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083327,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392584,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683983,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004077,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603541,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797322,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583590661,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589857013,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297064,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590764689,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594672627,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219024,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715732,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045638,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429403,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689490,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137349,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349852,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129283,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591382586,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591880583,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592397403,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:741",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596407267,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596501344,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122356,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582484557,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_folios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938075,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583215004,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583708693,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933050,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584763179,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593149092,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593682103,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594248540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:618",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596938979,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597038948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318566,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699067,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_folios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583155441,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583433425,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584145850,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584986804,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593602836,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594162775,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594634812,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:615",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597864547,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597970916,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath",
        "kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582479391,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582868584,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_folios"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338385,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413839,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmalloc_node_trace",
        "mm/slub.c:kmalloc_trace",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_lru",
        "mm/slub.c:kmem_cache_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361623,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585218433,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594377428,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594959287,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:net_test_get_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595437814,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:637",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491117468,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm64/include/asm/processor.h:270",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492286220,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm64/include/asm/processor.h:270",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492555600,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm64/include/asm/processor.h:270",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492871252,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm64/include/asm/processor.h:270",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493723312,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm64/include/asm/processor.h:270",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494500328,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm64/include/asm/processor.h:270",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501926708,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm64/include/asm/processor.h:270",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243251872,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "init/do_mounts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/do_mounts.c:mount_block_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3224433432,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/traps.c:die",
        "arch/arm/kernel/traps.c:die"
      ],
      "caller_func": []
    },
    {
      "addr": 3224447684,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/smp.c:secondary_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 3224457508,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/kernel/machine_kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core"
      ],
      "caller_func": []
    },
    {
      "addr": 3243277972,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/mm/fault-armv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/fault-armv.c:check_writebuffer_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 3224500680,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/mm/pgd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/pgd.c:pgd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3224511236,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/mm/context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/context.c:check_and_switch_context",
        "arch/arm/mm/context.c:check_and_switch_context",
        "arch/arm/mm/context.c:check_and_switch_context",
        "arch/arm/mm/context.c:check_and_switch_context",
        "arch/arm/mm/context.c:check_and_switch_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3224521072,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/mm/cache-l2x0-pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_configure",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read",
        "arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_event_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3224527104,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/common/mcpm_entry.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/mcpm_entry.c:mcpm_cpu_powered_up",
        "arch/arm/common/mcpm_entry.c:mcpm_cpu_suspend",
        "arch/arm/common/mcpm_entry.c:mcpm_cpu_power_down",
        "arch/arm/common/mcpm_entry.c:mcpm_cpu_power_up"
      ],
      "caller_func": []
    },
    {
      "addr": 3224581976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "arch/arm/mach-imx/mmdc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_add",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_start",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_update",
        "arch/arm/mach-imx/mmdc.c:mmdc_pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3224715184,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:ksys_unshare",
        "kernel/fork.c:walk_process_tree",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:get_task_mm",
        "kernel/fork.c:get_mm_exe_file",
        "kernel/fork.c:mmput_async_fn",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mmput",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mm_init",
        "kernel/fork.c:mmdrop_async",
        "kernel/fork.c:__mmdrop",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3224717784,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic",
        "kernel/panic.c:nmi_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 3224732608,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224738484,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned",
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3224756844,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3224762972,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_cad_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 3224773716,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 3224802908,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:__sigqueue_alloc",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3224809348,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/sys.c:__se_sys_umask",
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__se_sys_getpriority",
        "kernel/sys.c:__se_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 3224826720,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/umh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/umh.c:call_usermodehelper_exec",
        "kernel/umh.c:call_usermodehelper_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 3224832080,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:flush_workqueue_prep_pwqs",
        "kernel/workqueue.c:flush_workqueue_prep_pwqs",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:process_one_work",
        "kernel/workqueue.c:pwq_dec_nr_in_flight",
        "kernel/workqueue.c:wq_worker_sleeping",
        "kernel/workqueue.c:wq_worker_running"
      ],
      "caller_func": []
    },
    {
      "addr": 3224862220,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_run",
        "kernel/task_work.c:task_work_cancel",
        "kernel/task_work.c:task_work_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3224874340,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_associate_blkcg",
        "kernel/kthread.c:kthread_associate_blkcg",
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3224878156,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/nsproxy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/nsproxy.c:switch_task_namespaces",
        "kernel/nsproxy.c:copy_namespaces"
      ],
      "caller_func": []
    },
    {
      "addr": 3224884556,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:revert_creds",
        "kernel/cred.c:override_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:commit_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:copy_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:exit_creds",
        "kernel/cred.c:put_cred_rcu",
        "kernel/cred.c:put_cred_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3224888832,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/async.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/async.c:async_schedule_node_domain",
        "kernel/async.c:async_run_entry_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3224893416,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:cpu_report_death",
        "kernel/smpboot.c:cpu_wait_death",
        "kernel/smpboot.c:cpu_set_state_online"
      ],
      "caller_func": []
    },
    {
      "addr": 3224894736,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/ucount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:dec_ucount",
        "kernel/ucount.c:inc_ucount",
        "kernel/ucount.c:inc_ucount"
      ],
      "caller_func": []
    },
    {
      "addr": 3224895492,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module",
        "kernel/kmod.c:__request_module",
        "kernel/kmod.c:__request_module",
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 3224897424,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/groups.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/groups.c:__se_sys_setgroups",
        "kernel/groups.c:set_groups",
        "kernel/groups.c:set_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 3224951536,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:finish_task_switch",
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:scheduler_ipi",
        "kernel/sched/core.c:sched_ttwu_pending",
        "kernel/sched/core.c:wake_q_add_safe",
        "kernel/sched/core.c:wake_q_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3224955760,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load_tick",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_global_load",
        "kernel/sched/loadavg.c:calc_load_nohz_fold"
      ],
      "caller_func": []
    },
    {
      "addr": 3243372836,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/clock.c:sched_clock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3224956660,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/cputime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cputime.c:account_system_index_time",
        "kernel/sched/cputime.c:account_guest_time",
        "kernel/sched/cputime.c:account_user_time"
      ],
      "caller_func": []
    },
    {
      "addr": 3224976156,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:attach_entity_cfs_rq",
        "kernel/sched/fair.c:detach_entity_cfs_rq",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:run_rebalance_domains",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:nohz_balance_enter_idle",
        "kernel/sched/fair.c:kick_ilb",
        "kernel/sched/fair.c:update_blocked_averages",
        "kernel/sched/fair.c:update_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 3225022300,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/sched/rt.c:tg_set_rt_bandwidth",
        "kernel/sched/rt.c:rq_offline_rt",
        "kernel/sched/rt.c:rq_online_rt",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:update_curr_rt"
      ],
      "caller_func": []
    },
    {
      "addr": 3225025644,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:rq_offline_dl",
        "kernel/sched/deadline.c:update_curr_dl"
      ],
      "caller_func": []
    },
    {
      "addr": 3225054504,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/cpupri.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/cpupri.c:cpupri_set",
        "kernel/sched/cpupri.c:cpupri_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3225065128,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:partition_sched_domains_locked",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:build_overlap_sched_groups",
        "kernel/sched/topology.c:destroy_sched_domain",
        "kernel/sched/topology.c:sched_put_rd",
        "kernel/sched/topology.c:sched_get_rd",
        "kernel/sched/topology.c:rq_attach_root",
        "kernel/sched/topology.c:rq_attach_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3225067212,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/stop_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3225074092,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 3225102436,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:__se_sys_membarrier",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited",
        "kernel/sched/membarrier.c:membarrier_register_private_expedited"
      ],
      "caller_func": []
    },
    {
      "addr": 3225105700,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3236544536,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/mutex.c:ww_mutex_lock_interruptible",
        "kernel/locking/mutex.c:ww_mutex_lock",
        "kernel/locking/mutex.c:mutex_lock_killable",
        "kernel/locking/mutex.c:mutex_lock_interruptible",
        "kernel/locking/mutex.c:mutex_unlock",
        "kernel/locking/mutex.c:mutex_lock",
        "kernel/locking/mutex.c:__mutex_add_waiter",
        "kernel/locking/mutex.c:mutex_trylock_recursive"
      ],
      "caller_func": []
    },
    {
      "addr": 3225114116,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/locking/rwsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem.c:downgrade_write",
        "kernel/locking/rwsem.c:up_write",
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:up_read",
        "kernel/locking/rwsem.c:down_write_trylock",
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write",
        "kernel/locking/rwsem.c:down_read_trylock",
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read",
        "kernel/locking/rwsem.c:down_read",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_write_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_down_read_slowpath",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_optimistic_spin",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake",
        "kernel/locking/rwsem.c:rwsem_mark_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 3236557796,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_write_trylock",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_write_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_write_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_write_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_write_lock",
        "kernel/locking/spinlock.c:_raw_read_lock",
        "kernel/locking/spinlock.c:_raw_spin_trylock_bh",
        "kernel/locking/spinlock.c:_raw_spin_trylock",
        "kernel/locking/spinlock.c:_raw_spin_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_spin_lock_irq",
        "kernel/locking/spinlock.c:_raw_spin_lock_bh",
        "kernel/locking/spinlock.c:_raw_spin_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225118660,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/locking/osq_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_lock",
        "kernel/locking/osq_lock.c:osq_lock",
        "kernel/locking/osq_lock.c:osq_lock",
        "kernel/locking/osq_lock.c:osq_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3236550368,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/locking/rtmutex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_unlock",
        "kernel/locking/rtmutex.c:rt_mutex_trylock",
        "kernel/locking/rtmutex.c:rt_mutex_timed_lock",
        "kernel/locking/rtmutex.c:rt_mutex_lock_interruptible",
        "kernel/locking/rtmutex.c:rt_mutex_lock",
        "kernel/locking/rtmutex.c:rt_mutex_slowunlock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225135632,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:freeze_processes",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 3225145136,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": []
    },
    {
      "addr": 3225160856,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/power/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/swap.c:hib_submit_io",
        "kernel/power/swap.c:hib_end_io",
        "kernel/power/swap.c:hib_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3225171136,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_release",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:snapshot_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3225192952,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_log_store",
        "kernel/printk/printk_safe.c:printk_safe_log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3225198100,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/irq/handle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225203084,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/irq/manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/manage.c:irq_forced_thread_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3225213752,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 3225223552,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3225235840,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3225254164,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_end_inkernel_boot",
        "kernel/rcu/update.c:rcu_expedite_gp"
      ],
      "caller_func": []
    },
    {
      "addr": 3225259128,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 3225267976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcutree_prepare_cpu",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_eqs_special_set",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225300508,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/kcmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kcmp.c:__se_sys_kcmp"
      ],
      "caller_func": []
    },
    {
      "addr": 3225303148,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/profile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/profile.c:read_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 3225389128,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample_group",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample_group",
        "kernel/time/posix-cpu-timers.c:cpu_clock_sample_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3225435388,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:__unqueue_futex",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3225442492,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:flush_smp_call_function_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3225445608,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/uid16.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/uid16.c:__se_sys_setgroups16"
      ],
      "caller_func": []
    },
    {
      "addr": 3225469156,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:do_free_init",
        "kernel/module.c:try_module_get",
        "kernel/module.c:__se_sys_delete_module",
        "kernel/module.c:__se_sys_delete_module"
      ],
      "caller_func": []
    },
    {
      "addr": 3225481888,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:acct_pin_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 3225487868,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 3225489588,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load"
      ],
      "caller_func": []
    },
    {
      "addr": 3225533684,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_tryget_online_from_dir",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_create",
        "kernel/cgroup/cgroup.c:online_css",
        "kernel/cgroup/cgroup.c:online_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists",
        "kernel/cgroup/cgroup.c:cgroup_kn_lock_live",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 3225537592,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cgroup/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/namespace.c:copy_cgroup_ns",
        "kernel/cgroup/namespace.c:free_cgroup_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3225545964,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree",
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3225551540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_css_offline",
        "kernel/cgroup/legacy_freezer.c:freezer_css_online"
      ],
      "caller_func": []
    },
    {
      "addr": 3225551948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cgroup/pids.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/pids.c:pids_max_write",
        "kernel/cgroup/pids.c:pids_can_fork",
        "kernel/cgroup/pids.c:pids_can_fork",
        "kernel/cgroup/pids.c:pids_css_alloc",
        "kernel/cgroup/pids.c:pids_css_alloc",
        "kernel/cgroup/pids.c:pids_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225556268,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_try_charge",
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573628,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_offline",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:cpuset_css_online",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 3225574052,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/utsname.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/utsname.c:free_uts_ns",
        "kernel/utsname.c:copy_utsname"
      ],
      "caller_func": []
    },
    {
      "addr": 3225575552,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/user_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:ns_get_owner",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_install",
        "kernel/user_namespace.c:userns_put",
        "kernel/user_namespace.c:userns_get",
        "kernel/user_namespace.c:free_user_ns",
        "kernel/user_namespace.c:unshare_userns"
      ],
      "caller_func": []
    },
    {
      "addr": 3225582200,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:zap_pid_ns_processes",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:delayed_free_pidns"
      ],
      "caller_func": []
    },
    {
      "addr": 3225585416,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/stop_machine.c:cpu_stop_signal_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3225599988,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 3225638796,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/audit_tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit_tree.c:audit_tree_lookup",
        "kernel/audit_tree.c:audit_put_chunk"
      ],
      "caller_func": []
    },
    {
      "addr": 3225656076,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/debug/debug_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/debug_core.c:kgdb_breakpoint",
        "kernel/debug/debug_core.c:kgdb_breakpoint",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225669112,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf"
      ],
      "caller_func": []
    },
    {
      "addr": 3225679500,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 3225705296,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 3225722044,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3225737500,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_register_prio"
      ],
      "caller_func": []
    },
    {
      "addr": 3225737976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_clock.c:trace_clock_counter",
        "kernel/trace/trace_clock.c:trace_clock_global"
      ],
      "caller_func": []
    },
    {
      "addr": 3225744792,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:profile_graph_entry",
        "kernel/trace/ftrace.c:profile_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3225791348,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_free_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_swap_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_swap_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_swap_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_swap_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_reset_cpu",
        "kernel/trace/ring_buffer.c:ring_buffer_read_finish",
        "kernel/trace/ring_buffer.c:ring_buffer_read_finish",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare",
        "kernel/trace/ring_buffer.c:ring_buffer_read_prepare",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_iter_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_advance_iter",
        "kernel/trace/ring_buffer.c:rb_advance_reader",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/ring_buffer.c:ring_buffer_record_on",
        "kernel/trace/ring_buffer.c:ring_buffer_record_off",
        "kernel/trace/ring_buffer.c:ring_buffer_record_enable",
        "kernel/trace/ring_buffer.c:ring_buffer_record_disable",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_discard_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:ring_buffer_lock_reserve",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:__rb_reserve_next",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_commit",
        "kernel/trace/ring_buffer.c:rb_start_commit",
        "kernel/trace/ring_buffer.c:rb_start_commit",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_move_tail",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_check_pages",
        "kernel/trace/ring_buffer.c:rb_check_list",
        "kernel/trace/ring_buffer.c:rb_check_list",
        "kernel/trace/ring_buffer.c:rb_set_head_page",
        "kernel/trace/ring_buffer.c:rb_set_head_page",
        "kernel/trace/ring_buffer.c:rb_set_head_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3225838780,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_snapshot_write",
        "kernel/trace/trace.c:tracing_set_tracer",
        "kernel/trace/trace.c:tracing_saved_cmdlines_size_read",
        "kernel/trace/trace.c:saved_cmdlines_start",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:tracing_cpumask_write",
        "kernel/trace/trace.c:s_stop",
        "kernel/trace/trace.c:s_start",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:__trace_array_vprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_vbprintk",
        "kernel/trace/trace.c:trace_find_cmdline",
        "kernel/trace/trace.c:tracing_stop",
        "kernel/trace/trace.c:tracing_snapshot_cond_disable",
        "kernel/trace/trace.c:tracing_snapshot_cond_enable",
        "kernel/trace/trace.c:tracing_cond_snapshot_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3225859800,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 3225863964,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:wakeup_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_return",
        "kernel/trace/trace_sched_wakeup.c:wakeup_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3225871420,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_stack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_stack.c:t_start",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 3225874788,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3225887896,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:__blk_trace_setup",
        "kernel/trace/blktrace.c:__blk_trace_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3225895772,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:start_graph_tracing",
        "kernel/trace/fgraph.c:ftrace_suspend_notifier_call",
        "kernel/trace/fgraph.c:ftrace_suspend_notifier_call",
        "kernel/trace/fgraph.c:function_graph_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225901604,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3225934532,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225977440,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_kdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kdb.c:kdb_ftdump",
        "kernel/trace/trace_kdb.c:kdb_ftdump"
      ],
      "caller_func": []
    },
    {
      "addr": 3225991084,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3226001840,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq_work.c:irq_work_claim"
      ],
      "caller_func": []
    },
    {
      "addr": 3226017720,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:bpf_jit_binary_free",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc",
        "kernel/bpf/core.c:bpf_jit_binary_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226024380,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero",
        "kernel/bpf/syscall.c:bpf_prog_uncharge_memlock",
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:__bpf_prog_charge",
        "kernel/bpf/syscall.c:bpf_map_put_uref",
        "kernel/bpf/syscall.c:bpf_map_uncharge_memlock",
        "kernel/bpf/syscall.c:bpf_map_charge_finish",
        "kernel/bpf/syscall.c:bpf_charge_memlock",
        "kernel/bpf/syscall.c:bpf_charge_memlock"
      ],
      "caller_func": []
    },
    {
      "addr": 3226111964,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 3226117200,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226129232,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr",
        "kernel/bpf/arraymap.c:fd_array_map_delete_elem",
        "kernel/bpf/arraymap.c:bpf_fd_array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226141252,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226170016,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_notification",
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/devmap.c:dev_map_delete_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226172992,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "kernel/bpf/cpumap.c:__cpu_map_entry_replace",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 3226177044,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226179828,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register",
        "kernel/bpf/offload.c:bpf_offload_dev_netdev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3226185916,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 3226203616,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 3226264352,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_exit_task_context",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:account_event",
        "kernel/events/core.c:task_clock_event_start",
        "kernel/events/core.c:task_clock_event_update",
        "kernel/events/core.c:task_clock_event_update",
        "kernel/events/core.c:cpu_clock_event_start",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:perf_swevent_init",
        "kernel/events/core.c:sw_perf_event_destroy",
        "kernel/events/core.c:perf_swevent_event",
        "kernel/events/core.c:perf_swevent_event",
        "kernel/events/core.c:perf_swevent_set_period",
        "kernel/events/core.c:__perf_event_overflow",
        "kernel/events/core.c:perf_prepare_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_close",
        "kernel/events/core.c:perf_mmap_open",
        "kernel/events/core.c:perf_mmap_open",
        "kernel/events/core.c:perf_mmap_open",
        "kernel/events/core.c:perf_mmap_fault",
        "kernel/events/core.c:__perf_event_period",
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:perf_poll",
        "kernel/events/core.c:put_event",
        "kernel/events/core.c:free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:_free_event",
        "kernel/events/core.c:exclusive_event_destroy",
        "kernel/events/core.c:exclusive_event_destroy",
        "kernel/events/core.c:perf_sched_delayed",
        "kernel/events/core.c:perf_adjust_period",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:_perf_event_refresh"
      ],
      "caller_func": []
    },
    {
      "addr": 3226280652,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 3226283504,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers",
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 3226301648,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:xol_free_insn_slot",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226306152,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_replace",
        "kernel/padata.c:padata_do_serial",
        "kernel/padata.c:padata_serial_worker",
        "kernel/padata.c:padata_find_next",
        "kernel/padata.c:padata_do_parallel",
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 3226329404,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:unlock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:unaccount_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226355824,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:exit_oom_victim",
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:mark_oom_victim",
        "mm/oom_kill.c:mark_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 3226365224,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:wb_update_write_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 3226382056,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226389212,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:deactivate_file_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages",
        "mm/swap.c:put_pages_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226396876,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226429360,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:reclaim_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:isolate_lru_page",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:do_shrink_slab",
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 3226458952,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_fault",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3226478096,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:drain_zonestat",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:cpu_vm_stats_fold",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:fold_diff",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_node_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__dec_zone_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_node_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__inc_zone_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_node_page_state",
        "mm/vmstat.c:__mod_zone_page_state",
        "mm/vmstat.c:__mod_zone_page_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3226480896,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:clear_wb_congested",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226486952,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm",
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226515852,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 3226549132,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 3226549296,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/prfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/prfile.c:vma_do_get_file",
        "mm/prfile.c:vma_do_get_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3226556020,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226583196,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 3226584084,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226588024,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 3226591708,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:__vma_link_file",
        "mm/mmap.c:__vma_link_file",
        "mm/mmap.c:__remove_shared_vm_struct",
        "mm/mmap.c:__remove_shared_vm_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 3226612012,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/mmu_gather.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_gather_mmu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226612220,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226618768,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__se_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 3226627032,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:__put_anon_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:__anon_vma_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3226642284,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vunmap",
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3226653312,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226682788,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_highmem_page",
        "mm/page_alloc.c:free_highmem_page",
        "mm/page_alloc.c:free_highmem_page",
        "mm/page_alloc.c:page_frag_free",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:page_frag_alloc",
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:set_pfnblock_flags_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3243453876,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/memblock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_free_all",
        "mm/memblock.c:__memblock_free_late"
      ],
      "caller_func": []
    },
    {
      "addr": 3226699232,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226702788,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage",
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226708568,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:lookup_swap_cache",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:delete_from_swap_cache",
        "mm/swap_state.c:add_to_swap_cache",
        "mm/swap_state.c:add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3226726152,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:__do_sys_swapoff",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:get_swap_page_of_type",
        "mm/swapfile.c:get_swap_page_of_type",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:get_swap_pages",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226734700,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/frontswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frontswap.c:__frontswap_invalidate_page",
        "mm/frontswap.c:__frontswap_load",
        "mm/frontswap.c:__frontswap_store",
        "mm/frontswap.c:__frontswap_store",
        "mm/frontswap.c:frontswap_register_ops",
        "mm/frontswap.c:frontswap_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 3226740384,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_pool_create",
        "mm/zswap.c:zswap_free_entry",
        "mm/zswap.c:zswap_free_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226744976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/mmu_notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_notifier.c:mmu_notifier_free_rcu",
        "mm/mmu_notifier.c:mmu_notifier_unregister",
        "mm/mmu_notifier.c:__mmu_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3226754760,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:run_store",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:__ksm_enter",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:__stable_node_chain",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/ksm.c:break_ksm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226785112,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:kmem_cache_open",
        "mm/slub.c:__slab_free",
        "mm/slub.c:unfreeze_partials",
        "mm/slub.c:deactivate_slab",
        "mm/slub.c:deactivate_slab",
        "mm/slub.c:discard_slab",
        "mm/slub.c:discard_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:allocate_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:free_debug_processing"
      ],
      "caller_func": []
    },
    {
      "addr": 3226806424,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226809404,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_set_max",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_try_charge",
        "mm/page_counter.c:page_counter_charge",
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226819632,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_write",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:__invalidate_reclaim_iterators",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3226854624,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/cleancache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/cleancache.c:cleancache_register_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 3226857980,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/zpool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zpool.c:zpool_put_driver",
        "mm/zpool.c:zpool_get_driver"
      ],
      "caller_func": []
    },
    {
      "addr": 3226867496,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:__free_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226875028,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 3226876300,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3226880536,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page",
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226881944,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:put_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 3226885264,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3226889908,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 3226891916,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:do_dentry_open",
        "fs/open.c:do_dentry_open",
        "fs/open.c:do_dentry_open",
        "fs/open.c:do_faccessat",
        "fs/open.c:vfs_truncate",
        "fs/open.c:vfs_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 3226907964,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:vfs_dedupe_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226921000,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:delayed_fput",
        "fs/file_table.c:__fput",
        "fs/file_table.c:__fput",
        "fs/file_table.c:alloc_file",
        "fs/file_table.c:__alloc_file",
        "fs/file_table.c:file_free_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3226924352,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:freeze_super",
        "fs/super.c:super_setup_bdi",
        "fs/super.c:grab_super",
        "fs/super.c:deactivate_locked_super",
        "fs/super.c:alloc_super"
      ],
      "caller_func": []
    },
    {
      "addr": 3226952248,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:set_dumpable",
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:free_bprm",
        "fs/exec.c:would_dump",
        "fs/exec.c:would_dump",
        "fs/exec.c:de_thread",
        "fs/exec.c:kernel_read_file",
        "fs/exec.c:kernel_read_file",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:copy_strings",
        "fs/exec.c:copy_strings",
        "fs/exec.c:acct_arg_size",
        "fs/exec.c:__se_sys_uselib",
        "fs/exec.c:__se_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 3226960232,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:free_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:generic_pipe_buf_get",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/pipe.c:anon_pipe_buf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3226968692,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/namei.c:do_last",
        "fs/namei.c:do_last"
      ],
      "caller_func": []
    },
    {
      "addr": 3227003048,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 3227011948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/select.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/select.c:__pollwait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227034124,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_add",
        "fs/dcache.c:__d_lookup_done",
        "fs/dcache.c:d_alloc_parallel",
        "fs/dcache.c:__d_rehash",
        "fs/dcache.c:__d_instantiate_anon",
        "fs/dcache.c:___d_drop",
        "fs/dcache.c:dentry_free",
        "fs/dcache.c:release_dentry_name_snapshot",
        "fs/dcache.c:take_dentry_name_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 3227048928,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_set_flags",
        "fs/inode.c:generic_update_time",
        "fs/inode.c:insert_inode_locked",
        "fs/inode.c:new_inode",
        "fs/inode.c:get_next_ino",
        "fs/inode.c:find_inode_fast",
        "fs/inode.c:find_inode",
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:inc_nlink",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:inode_init_always"
      ],
      "caller_func": []
    },
    {
      "addr": 3227065536,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file.c:f_dupfd",
        "fs/file.c:do_dup2",
        "fs/file.c:__fget",
        "fs/file.c:__close_fd_get_file",
        "fs/file.c:get_files_struct",
        "fs/file.c:dup_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 3227066232,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/filesystems.c:__se_sys_sysfs",
        "fs/filesystems.c:__se_sys_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 3227093824,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:mntns_install",
        "fs/namespace.c:mntns_get",
        "fs/namespace.c:mount_subtree",
        "fs/namespace.c:copy_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:alloc_mnt_ns",
        "fs/namespace.c:free_mnt_ns",
        "fs/namespace.c:mark_mounts_for_expiry",
        "fs/namespace.c:do_umount",
        "fs/namespace.c:delayed_mntput",
        "fs/namespace.c:clone_mnt",
        "fs/namespace.c:vfs_create_mount",
        "fs/namespace.c:mnt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3227115388,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 3227152604,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:wb_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3227163600,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 3227178316,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 3227182508,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/nsfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/nsfs.c:__ns_get_path"
      ],
      "caller_func": []
    },
    {
      "addr": 3227185168,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fs_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_context.c:put_fs_context",
        "fs/fs_context.c:put_fs_context",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:vfs_dup_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fs_context.c:alloc_fs_context",
        "fs/fs_context.c:alloc_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227210284,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:ll_rw_block",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:__block_write_full_page",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:block_invalidatepage",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:alloc_page_buffers",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:fsync_buffers_list",
        "fs/buffer.c:write_boundary_block",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_write_sync",
        "fs/buffer.c:end_buffer_read_sync",
        "fs/buffer.c:unlock_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3227228636,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode",
        "fs/block_dev.c:blkdev_write_end",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:__blkdev_direct_IO",
        "fs/block_dev.c:blkdev_bio_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3227242272,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:sb_init_dio_done_wq",
        "fs/direct-io.c:dio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 3227249608,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages",
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 3227252088,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc_namespace.c:mounts_open_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3227254884,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 3227256448,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3227261288,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/notify/mark.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "fs/notify/mark.c:fsnotify_add_mark_list",
        "fs/notify/mark.c:fsnotify_detach_mark",
        "fs/notify/mark.c:fsnotify_prepare_user_wait",
        "fs/notify/mark.c:fsnotify_drop_object",
        "fs/notify/mark.c:fsnotify_detach_connector_from_object"
      ],
      "caller_func": []
    },
    {
      "addr": 3227269976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_free_group_priv"
      ],
      "caller_func": []
    },
    {
      "addr": 3227277100,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3227284764,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3227311312,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/userfaultfd.c:__se_sys_userfaultfd",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:dup_userfaultfd"
      ],
      "caller_func": []
    },
    {
      "addr": 3227319384,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:lookup_ioctx",
        "fs/aio.c:__get_reqs_available",
        "fs/aio.c:put_reqs_available",
        "fs/aio.c:exit_aio",
        "fs/aio.c:kill_ioctx",
        "fs/aio.c:free_ioctx_users",
        "fs/aio.c:free_ioctx_reqs",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 3227351856,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_register",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_mem_free",
        "fs/io_uring.c:io_account_mem",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:__io_queue_sqe",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_timeout_fn",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3227359772,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/crypto/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/hooks.c:fscrypt_get_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 3227368592,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/crypto/keysetup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/keysetup.c:fscrypt_get_encryption_info",
        "fs/crypto/keysetup.c:setup_per_mode_key",
        "fs/crypto/keysetup.c:derive_essiv_salt"
      ],
      "caller_func": []
    },
    {
      "addr": 3227377944,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3227378324,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/verity/hash_algs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_get_hash_alg"
      ],
      "caller_func": []
    },
    {
      "addr": 3227382356,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/verity/open.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227383540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227396040,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/locks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_get_lock_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227410376,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/binfmt_script.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_script.c:load_script"
      ],
      "caller_func": []
    },
    {
      "addr": 3227423224,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 3227427624,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/binfmt_elf_fdpic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump",
        "fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary",
        "fs/binfmt_elf_fdpic.c:load_elf_fdpic_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 3227440380,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/binfmt_flat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_flat.c:load_flat_shared_library"
      ],
      "caller_func": []
    },
    {
      "addr": 3227442368,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_delete",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:mb_cache_entry_get",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3227447904,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:__forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 3227456308,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 3227464164,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_dirty_actor",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_readpages",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpages_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/iomap/buffered-io.c:iomap_page_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3227476804,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_zero",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io",
        "fs/iomap/direct-io.c:iomap_dio_complete",
        "fs/iomap/direct-io.c:iomap_dio_submit_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 3227479328,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3227493056,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/quota/dquot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active"
      ],
      "caller_func": []
    },
    {
      "addr": 3227513232,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 3227520588,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_release",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:smaps_rollup_release",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:smaps_pte_entry",
        "fs/proc/task_mmu.c:proc_map_release",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3227524324,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_get_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 3227527540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/root.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:pid_ns_prepare_proc",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/root.c:proc_init_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227532848,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_setgroups_release",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_setgroups_open",
        "fs/proc/base.c:proc_id_map_release",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:proc_id_map_open",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:environ_read",
        "fs/proc/base.c:mem_release",
        "fs/proc/base.c:mem_rw",
        "fs/proc/base.c:proc_mem_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3227551484,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3227557896,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid",
        "fs/proc/array.c:task_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3227566004,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/fd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/fd.c:seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3227580672,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table",
        "fs/proc/proc_sysctl.c:proc_sys_poll_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 3227609104,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_remove_self",
        "fs/kernfs/dir.c:kernfs_activate",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "fs/kernfs/dir.c:kernfs_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3227610344,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/kernfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/file.c:kernfs_notify",
        "fs/kernfs/file.c:kernfs_drain_open_files",
        "fs/kernfs/file.c:kernfs_fop_open",
        "fs/kernfs/file.c:kernfs_put_open_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3227621360,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/sysfs/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/sysfs/mount.c:sysfs_init_fs_context",
        "fs/sysfs/mount.c:sysfs_init_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3227626040,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/configfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/inode.c:configfs_hash_and_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3227632540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/configfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/dir.c:detach_attrs",
        "fs/configfs/dir.c:configfs_remove_dirent",
        "fs/configfs/dir.c:configfs_make_dirent",
        "fs/configfs/dir.c:configfs_new_dirent",
        "fs/configfs/dir.c:put_fragment",
        "fs/configfs/dir.c:configfs_d_iput"
      ],
      "caller_func": []
    },
    {
      "addr": 3227641144,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/configfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:configfs_unlink",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link",
        "fs/configfs/symlink.c:create_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3227645456,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_kill_index",
        "fs/devpts/inode.c:devpts_new_index",
        "fs/devpts/inode.c:devpts_new_index",
        "fs/devpts/inode.c:devpts_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 3227654256,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227661312,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 3227668440,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/extents.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_search_right",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3227720076,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3227746044,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_end_bitmap_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227747824,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/indirect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch"
      ],
      "caller_func": []
    },
    {
      "addr": 3227767824,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_dir",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inline.c:ext4_add_dirent_to_inline",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_destroy_inline_data_nolock",
        "fs/ext4/inline.c:ext4_update_inline_data",
        "fs/ext4/inline.c:ext4_create_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3227826708,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_mark_iloc_dirty",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_end_io_dio",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_bread",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_dio_get_block_unwritten_async",
        "fs/ext4/inode.c:ext4_update_bh_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3227830868,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 3227882628,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_mballoc_query_range",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_release_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_release_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_group_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_new_inode_pa",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_release",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator",
        "fs/ext4/mballoc.c:ext4_mb_simple_scan_group",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_find_by_goal",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_try_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_unload_buddy",
        "fs/ext4/mballoc.c:ext4_mb_unload_buddy",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache",
        "fs/ext4/mballoc.c:ext4_mb_init_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3227886236,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3227889688,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/mmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block",
        "fs/ext4/mmp.c:write_mmp_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3227894064,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227920372,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_generic_delete_entry",
        "fs/ext4/namei.c:add_dirent_to_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 3227934440,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_put_io_end",
        "fs/ext4/page-io.c:ext4_end_io_rsv_work",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "fs/ext4/page-io.c:ext4_finish_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 3227936180,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 3227951632,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/resize.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_resize_end",
        "fs/ext4/resize.c:ext4_resize_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3228031144,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_quota_write",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_commit_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_alloc_inode",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:ext4_sb_bread"
      ],
      "caller_func": []
    },
    {
      "addr": 3228060628,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228061032,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/sysfs.c:ext4_attr_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3228076832,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_inode_update_ref",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_block_csum_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 3228089748,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3228107948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_refile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_file_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_invalidatepage",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:journal_unmap_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_unfile_buffer",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_forget",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_dirty_metadata",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_undo_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:jbd2_journal_get_create_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:sub_reserved_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3228110324,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:journal_end_buffer_io_sync"
      ],
      "caller_func": []
    },
    {
      "addr": 3228120208,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 3228122944,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/jbd2/checkpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint",
        "fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint"
      ],
      "caller_func": []
    },
    {
      "addr": 3228150988,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_put_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_grab_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_add_journal_head",
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_log_tail",
        "fs/jbd2/journal.c:jbd2_write_superblock",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3228152956,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3228160956,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3228171636,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3228175500,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/lz4_wrapper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/lz4_wrapper.c:lz4_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 3228176144,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/lzo_wrapper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/lzo_wrapper.c:lzo_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 3228176912,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/xz_wrapper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress",
        "fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 3228177784,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/zlib_wrapper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/zlib_wrapper.c:zlib_uncompress",
        "fs/squashfs/zlib_wrapper.c:zlib_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 3228178548,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/squashfs/zstd_wrapper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/zstd_wrapper.c:zstd_uncompress",
        "fs/squashfs/zstd_wrapper.c:zstd_uncompress"
      ],
      "caller_func": []
    },
    {
      "addr": 3228188836,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fat/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/dir.c:fat_remove_entries"
      ],
      "caller_func": []
    },
    {
      "addr": 3228197592,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_collect_bhs",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ],
      "caller_func": []
    },
    {
      "addr": 3228218484,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fat/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_build_inode",
        "fs/fat/inode.c:fat_fill_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3228223928,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fat/misc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228234920,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fat/namei_vfat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_rename",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_mkdir",
        "fs/fat/namei_vfat.c:vfat_unlink",
        "fs/fat/namei_vfat.c:vfat_rmdir",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_create",
        "fs/fat/namei_vfat.c:vfat_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3228248632,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 3228253160,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3228254364,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228282592,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/ecryptfs/miscdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_release",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3228296760,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_dev_ioctl",
        "fs/fuse/dev.c:fuse_dev_release",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3228322356,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_reverse_inval_entry",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_create_open",
        "fs/fuse/dir.c:fuse_invalidate_attr_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3228330072,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_write_update_size",
        "fs/fuse/file.c:fuse_readpages_fill",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_aio_complete",
        "fs/fuse/file.c:fuse_release_user_pages",
        "fs/fuse/file.c:fuse_finish_open",
        "fs/fuse/file.c:fuse_file_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3228352680,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fuse/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/inode.c:fuse_conn_init",
        "fs/fuse/inode.c:fuse_change_attributes_common"
      ],
      "caller_func": []
    },
    {
      "addr": 3228369412,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 3228380632,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "fs/debugfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/debugfs/file.c:debugfs_file_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3228407944,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 3228416912,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "ipc/msg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque"
      ],
      "caller_func": []
    },
    {
      "addr": 3228441564,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:ksys_shmctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3228451844,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_notify",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mq_create_mount",
        "ipc/mqueue.c:mqueue_init_fs_context",
        "ipc/mqueue.c:mqueue_init_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3228456468,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:copy_ipcs",
        "ipc/namespace.c:copy_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 3228457392,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/keys/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228461572,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/keys/key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/key.c:key_reject_and_link",
        "security/keys/key.c:__key_instantiate_and_link",
        "security/keys/key.c:key_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3228470808,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 3228480408,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/keys/keyctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key",
        "security/keys/keyctl.c:keyctl_chown_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228485836,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/keys/process_keys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:key_change_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228488068,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:call_sbin_request_key",
        "security/keys/request_key.c:call_sbin_request_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3228490584,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/keys/request_key_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key_auth.c:request_key_auth_new",
        "security/keys/request_key_auth.c:request_key_auth_new"
      ],
      "caller_func": []
    },
    {
      "addr": 3228550796,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_node_replace",
        "security/selinux/avc.c:avc_node_kill",
        "security/selinux/avc.c:avc_node_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 3228557376,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_secmark_refcount_dec",
        "security/selinux/hooks.c:selinux_secmark_refcount_inc",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 3228610896,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3228682948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 3228693788,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/selinux/xfrm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire",
        "security/selinux/xfrm.c:selinux_xfrm_policy_clone",
        "security/selinux/xfrm.c:selinux_xfrm_alloc_user"
      ],
      "caller_func": []
    },
    {
      "addr": 3228761656,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_close_control",
        "security/tomoyo/common.c:tomoyo_open_control",
        "security/tomoyo/common.c:tomoyo_update_stat",
        "security/tomoyo/common.c:tomoyo_write_task",
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 3228764780,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/condition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition"
      ],
      "caller_func": []
    },
    {
      "addr": 3228772252,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_update_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 3228774888,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/environ.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/environ.c:tomoyo_write_misc"
      ],
      "caller_func": []
    },
    {
      "addr": 3228780140,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_write_file",
        "security/tomoyo/file.c:tomoyo_put_name_union",
        "security/tomoyo/file.c:tomoyo_put_name_union"
      ],
      "caller_func": []
    },
    {
      "addr": 3228782044,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/gc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_try_to_gc",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_condition",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl",
        "security/tomoyo/gc.c:tomoyo_del_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 3228784660,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3228785896,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/memory.c:tomoyo_get_name",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_get_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3228791028,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_write_inet_network"
      ],
      "caller_func": []
    },
    {
      "addr": 3228795160,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 3243523576,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_init",
        "security/tomoyo/tomoyo.c:tomoyo_task_free",
        "security/tomoyo/tomoyo.c:tomoyo_task_free",
        "security/tomoyo/tomoyo.c:tomoyo_task_alloc",
        "security/tomoyo/tomoyo.c:tomoyo_bprm_committed_creds",
        "security/tomoyo/tomoyo.c:tomoyo_cred_prepare",
        "security/tomoyo/tomoyo.c:tomoyo_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 3228851244,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/apparmor/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_hat"
      ],
      "caller_func": []
    },
    {
      "addr": 3228859628,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 3228867540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/apparmor/policy_unpack.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3228885988,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 3228942644,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 3228947428,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/integrity/ima/ima_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_queue.c:ima_add_digest_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3228958932,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation"
      ],
      "caller_func": []
    },
    {
      "addr": 3228994732,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "crypto/algapi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_generate",
        "crypto/algapi.c:crypto_stats_rng_seed",
        "crypto/algapi.c:crypto_stats_kpp_compute_shared_secret",
        "crypto/algapi.c:crypto_stats_kpp_generate_public_key",
        "crypto/algapi.c:crypto_stats_kpp_set_secret",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_final",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_ahash_update",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_decompress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_compress",
        "crypto/algapi.c:crypto_stats_akcipher_verify",
        "crypto/algapi.c:crypto_stats_akcipher_sign",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_decrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_akcipher_encrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_decrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_aead_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_decrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt",
        "crypto/algapi.c:crypto_stats_ablkcipher_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 3229123568,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_associate_blkg",
        "block/bio.c:__bio_associate_blkg",
        "block/bio.c:bio_endio",
        "block/bio.c:update_io_ticks",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3229161048,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:blk_queue_enter",
        "block/blk-core.c:blk_set_pm_only"
      ],
      "caller_func": []
    },
    {
      "addr": 3229170744,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3229176672,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-ioc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-ioc.c:exit_io_context"
      ],
      "caller_func": []
    },
    {
      "addr": 3229178664,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-map.c:blk_rq_map_user_iov"
      ],
      "caller_func": []
    },
    {
      "addr": 3229188252,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229206108,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq.c:blk_mq_get_driver_tag",
        "block/blk-mq.c:blk_mq_timeout_work",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_mq_get_request",
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3229222416,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 3229231440,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 3229244740,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:part_dec_in_flight",
        "block/genhd.c:part_dec_in_flight",
        "block/genhd.c:part_inc_in_flight",
        "block/genhd.c:part_inc_in_flight"
      ],
      "caller_func": []
    },
    {
      "addr": 3229251852,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:read_dev_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 3229263848,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/amiga.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229266888,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/atari.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229267952,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/aix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229271220,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/mac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229279932,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ],
      "caller_func": []
    },
    {
      "addr": 3229285416,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/msdos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86"
      ],
      "caller_func": []
    },
    {
      "addr": 3229287424,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/osf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229287904,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/sgi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229288684,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/sun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229289284,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/ultrix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229290028,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/efi.c:read_lba"
      ],
      "caller_func": []
    },
    {
      "addr": 3229294484,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/karma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229295452,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/partitions/sysv68.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 3229295764,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-rq-qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-rq-qos.c:rq_wait_inc_below"
      ],
      "caller_func": []
    },
    {
      "addr": 3229324228,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_add_delay",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_scale_delay",
        "block/blk-cgroup.c:blkcg_scale_delay",
        "block/blk-cgroup.c:blkcg_scale_delay",
        "block/blk-cgroup.c:blkcg_reset_stats",
        "block/blk-cgroup.c:blkcg_reset_stats",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_destroy",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3229336740,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued",
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 3229357100,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:ioc_pd_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:ioc_rqos_done_bio",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_wake_fn",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:ioc_refresh_params"
      ],
      "caller_func": []
    },
    {
      "addr": 3229386832,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3229419820,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/lockref.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/lockref.c:lockref_get_not_dead",
        "lib/lockref.c:lockref_put_or_lock",
        "lib/lockref.c:lockref_put_return",
        "lib/lockref.c:lockref_get_or_lock",
        "lib/lockref.c:lockref_put_not_zero",
        "lib/lockref.c:lockref_get_not_zero",
        "lib/lockref.c:lockref_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3229422232,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/debug_locks.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229437712,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3229457532,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/llist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/llist.c:llist_del_first",
        "lib/llist.c:llist_add_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 3229463840,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3229468812,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/rhashtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_insert_slow",
        "lib/rhashtable.c:rhashtable_rehash_alloc",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "lib/rhashtable.c:rhashtable_rehash_table",
        "lib/rhashtable.c:rhashtable_rehash_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3229471788,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/refcount.c:refcount_dec_if_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3229473536,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/errseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/errseq.c:errseq_check_and_advance",
        "lib/errseq.c:errseq_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3229474408,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/generic-radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free",
        "lib/generic-radix-tree.c:__genradix_ptr_alloc",
        "lib/generic-radix-tree.c:__genradix_ptr_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3243544540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/crc-t10dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crc-t10dif.c:crc_t10dif_mod_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3229527104,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/genalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/genalloc.c:gen_pool_free_owner",
        "lib/genalloc.c:gen_pool_alloc_algo_owner",
        "lib/genalloc.c:clear_bits_ll",
        "lib/genalloc.c:set_bits_ll"
      ],
      "caller_func": []
    },
    {
      "addr": 3229680160,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/irq_poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/irq_poll.c:__irq_poll_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 3229687316,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_finish_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_del_wait_queue",
        "lib/sbitmap.c:__sbq_wake_up",
        "lib/sbitmap.c:__sbq_wake_up",
        "lib/sbitmap.c:__sbq_wake_up",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:__sbitmap_get_word",
        "lib/sbitmap.c:sbitmap_resize",
        "lib/sbitmap.c:sbitmap_resize"
      ],
      "caller_func": []
    },
    {
      "addr": 3229740824,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/irqchip/irq-renesas-intc-irqpin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake",
        "drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_set_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 3229743808,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/irqchip/irq-renesas-irqc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake",
        "drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 3229783076,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/bus/ti-sysc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/bus/ti-sysc.c:sysc_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3229791624,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3229950280,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/pinctrl/samsung/pinctrl-exynos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_disable",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3230160696,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_bus_find_domain_nr",
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 3230169196,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3230239976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/pci/pcie/portdrv_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3230271376,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/pci/ats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": []
    },
    {
      "addr": 3230404048,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_unregister_mport"
      ],
      "caller_func": []
    },
    {
      "addr": 3230433284,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer",
        "drivers/video/fbdev/core/fbmem.c:register_framebuffer"
      ],
      "caller_func": []
    },
    {
      "addr": 3230461072,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 3230555844,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe",
        "drivers/amba/bus.c:amba_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3230564744,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/clk/clk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk.c:clk_core_is_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 3230788000,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:chan_dev_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3230793884,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma/of-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230826780,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma/ipu/ipu_idmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all",
        "drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all"
      ],
      "caller_func": []
    },
    {
      "addr": 3230954760,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ],
      "caller_func": []
    },
    {
      "addr": 3230976084,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_summary_show",
        "drivers/regulator/core.c:regulator_register",
        "drivers/regulator/core.c:regulator_lock_dependent"
      ],
      "caller_func": []
    },
    {
      "addr": 3231026564,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231044800,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_release",
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3231076436,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:__tty_buffer_request_room",
        "drivers/tty/tty_buffer.c:tty_buffer_flush",
        "drivers/tty/tty_buffer.c:tty_buffer_flush",
        "drivers/tty/tty_buffer.c:tty_buffer_free",
        "drivers/tty/tty_buffer.c:tty_buffer_free_all",
        "drivers/tty/tty_buffer.c:tty_buffer_free_all",
        "drivers/tty/tty_buffer.c:tty_buffer_lock_exclusive"
      ],
      "caller_func": []
    },
    {
      "addr": 3231083368,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldsem.c:ldsem_up_write",
        "drivers/tty/tty_ldsem.c:ldsem_up_read",
        "drivers/tty/tty_ldsem.c:ldsem_down_write_trylock",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read_trylock",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:ldsem_down_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3231087312,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 3231093968,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/tty_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_audit.c:tty_audit_add_data",
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 3231096364,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 3243851492,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/keyboard.c:kbd_init",
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_start",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate",
        "drivers/tty/vt/keyboard.c:kbd_led_trigger_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 3231149548,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231174280,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3231183444,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3231210804,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231243612,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3231298436,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_serial_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231337528,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/serial/kgdb_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_close"
      ],
      "caller_func": []
    },
    {
      "addr": 3231339592,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/serial/kgdboc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler",
        "drivers/tty/serial/kgdboc.c:kgdboc_pre_exp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3231343812,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3231361664,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:credit_entropy_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 3231379796,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 3231448696,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/iommu/io-pgtable-arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgtable-arm.c:arm_lpae_install_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3231467620,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/iommu/omap-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/omap-iommu.c:omap_iommu_attach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3231490280,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/iommu/exynos-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3231500048,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/connector/cn_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/connector/cn_queue.c:cn_queue_add_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 3231502392,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/connector/cn_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231537552,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_shutdown",
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3231549676,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/dd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dd.c:really_probe",
        "drivers/base/dd.c:really_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3231590564,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/devtmpfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devtmpfs.c:public_dev_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 3231616000,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:pm_runtime_allow",
        "drivers/base/power/runtime.c:pm_runtime_forbid",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:__pm_runtime_resume",
        "drivers/base/power/runtime.c:__pm_runtime_suspend",
        "drivers/base/power/runtime.c:__pm_runtime_idle",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_resume",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 3231633584,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 3231641272,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_system_cancel_wakeup",
        "drivers/base/power/wakeup.c:pm_system_wakeup",
        "drivers/base/power/wakeup.c:wakeup_source_report_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3231645700,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/power/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/domain.c:genpd_add_subdomain",
        "drivers/base/power/domain.c:genpd_sd_counter_dec"
      ],
      "caller_func": []
    },
    {
      "addr": 3231729144,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 3231743320,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq",
        "drivers/block/loop.c:lo_release",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:lo_rw_aio_complete",
        "drivers/block/loop.c:lo_rw_aio_do_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 3231868944,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake",
        "drivers/mfd/twl6030-irq.c:twl6030_irq_set_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 3231880824,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_disable",
        "drivers/mfd/mfd-core.c:mfd_cell_disable",
        "drivers/mfd/mfd-core.c:mfd_cell_enable",
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231955964,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma-buf/dma-buf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-buf.c:dma_buf_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3231960704,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence.c:dma_fence_context_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3231966208,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3231967596,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231981856,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:release_udmabuf",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3231992896,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma",
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 3231995884,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/scsi/scsicam.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsi_bios_ptable"
      ],
      "caller_func": []
    },
    {
      "addr": 3232015076,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:sdev_enable_disk_events",
        "drivers/scsi/scsi_lib.c:sdev_disable_disk_events",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_softirq_done",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_end_request",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy",
        "drivers/scsi/scsi_lib.c:scsi_dec_host_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 3232077420,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3232114576,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device",
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3232166772,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3232186292,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232444452,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 3232464756,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3232466056,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3232525104,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb",
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3232535692,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3232564408,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/net/ethernet/ti/davinci_mdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3232580464,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/net/ethernet/ti/cpsw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw.c:cpsw_remove",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3232608032,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/net/ethernet/ti/cpsw_ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3232612852,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_register_net_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 3232662668,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232701840,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_new_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3232710256,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:__usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_submit_urb",
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume",
        "drivers/usb/core/hcd.c:usb_hcd_start_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3232723092,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/urb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/urb.c:usb_anchor_suspend_wakeups",
        "drivers/usb/core/urb.c:usb_unpoison_anchored_urbs",
        "drivers/usb/core/urb.c:usb_block_urb",
        "drivers/usb/core/urb.c:usb_anchor_urb"
      ],
      "caller_func": []
    },
    {
      "addr": 3232741300,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume",
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3232777892,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_bulk",
        "drivers/usb/core/devio.c:proc_control",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:usbdev_open",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_mmap",
        "drivers/usb/core/devio.c:dec_usb_memory_use_count",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage",
        "drivers/usb/core/devio.c:usbfs_increase_memory_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 3232793852,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/devices.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devices.c:usbfs_conn_disc_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3232797916,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/port.c:usb_hub_create_port_device",
        "drivers/usb/core/port.c:usb_port_runtime_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 3232799276,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove",
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233166200,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233179836,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/musb/musb_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_core.c:musb_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3233216808,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/usb/musb/musb_gadget.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/musb/musb_gadget.c:musb_gadget_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3233242432,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 3233252556,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 3233323760,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/rtc/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rtc/dev.c:rtc_dev_release",
        "drivers/rtc/dev.c:rtc_dev_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3233360472,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_unreg",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_trace_reg"
      ],
      "caller_func": []
    },
    {
      "addr": 3233388540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233390352,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233399720,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/i2c/busses/i2c-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_remove",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233453056,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/power/avs/smartreflex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/avs/smartreflex.c:omap_sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233460664,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/power/reset/vexpress-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler",
        "drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3233466060,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_phandle",
        "drivers/power/supply/power_supply_core.c:power_supply_put",
        "drivers/power/supply/power_supply_core.c:power_supply_get_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 3233499936,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3244036440,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_exit",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_notify_reboot",
        "drivers/md/md.c:rdev_set_badblocks",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_check_recovery",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:md_write_end",
        "drivers/md/md.c:md_seq_next",
        "drivers/md/md.c:md_seq_start",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_attr_store",
        "drivers/md/md.c:md_attr_show",
        "drivers/md/md.c:rdev_size_store",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:super_written",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:mddev_find",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md.c:md_new_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3233658780,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_endwrite",
        "drivers/md/md-bitmap.c:md_bitmap_startwrite",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:read_page",
        "drivers/md/md-bitmap.c:end_bitmap_write",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page",
        "drivers/md/md-bitmap.c:write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3233679816,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq",
        "drivers/md/dm.c:event_callback",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:__map_bio",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:dm_blk_close",
        "drivers/md/dm.c:dm_blk_close",
        "drivers/md/dm.c:dm_blk_open",
        "drivers/md/dm.c:__dm_get_module_param",
        "drivers/md/dm.c:dm_issue_global_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3233696144,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/md/dm-stripe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stripe.c:stripe_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3233711944,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/md/dm-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dispatch_io",
        "drivers/md/dm-io.c:dec_count"
      ],
      "caller_func": []
    },
    {
      "addr": 3233713664,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/md/dm-kcopyd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-kcopyd.c:dm_kcopyd_prepare_callback",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_copy",
        "drivers/md/dm-kcopyd.c:segment_complete",
        "drivers/md/dm-kcopyd.c:dispatch_job",
        "drivers/md/dm-kcopyd.c:run_complete_job"
      ],
      "caller_func": []
    },
    {
      "addr": 3233726420,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/md/dm-stats.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/md/dm-stats.c:dm_stats_account_io"
      ],
      "caller_func": []
    },
    {
      "addr": 3233739012,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 3233747388,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 3233750696,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_handle_npe",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_handle_pe",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 3233807176,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3233809540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/cpufreq/omap-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/omap-cpufreq.c:omap_cpu_exit",
        "drivers/cpufreq/omap-cpufreq.c:omap_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3233829976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/cpuidle/coupled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled",
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled",
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled",
        "drivers/cpuidle/coupled.c:cpuidle_enter_state_coupled",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_set_done",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_set_done",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier",
        "drivers/cpuidle/coupled.c:cpuidle_coupled_parallel_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 3233894724,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio"
      ],
      "caller_func": []
    },
    {
      "addr": 3233897708,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3233924424,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3233963136,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/mmc/host/sdhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci.c:sdhci_set_power_noreg",
        "drivers/mmc/host/sdhci.c:sdhci_set_power_noreg",
        "drivers/mmc/host/sdhci.c:sdhci_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 3233997772,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/mmc/host/sdhci-esdhc-imx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3234020332,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 3234022580,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/leds/trigger/ledtrig-cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3234040904,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/firmware/arm_scmi/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3236533004,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 3243941956,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/firmware/efi/arm-runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services"
      ],
      "caller_func": []
    },
    {
      "addr": 3234101280,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/clocksource/timer-ti-dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234211424,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3234220012,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_shutdown",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot",
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 3234236356,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234242712,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234257828,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3234313512,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_event_init",
        "drivers/perf/arm-cci.c:cci_pmu_event_init",
        "drivers/perf/arm-cci.c:cci_pmu_start",
        "drivers/perf/arm-cci.c:pmu_handle_irq",
        "drivers/perf/arm-cci.c:pmu_event_update",
        "drivers/perf/arm-cci.c:pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3234320748,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_start",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update",
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3234324316,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm_pmu.c:armpmu_event_init",
        "drivers/perf/arm_pmu.c:armpmu_event_update",
        "drivers/perf/arm_pmu.c:armpmu_event_update",
        "drivers/perf/arm_pmu.c:armpmu_event_update",
        "drivers/perf/arm_pmu.c:armpmu_event_set_period",
        "drivers/perf/arm_pmu.c:armpmu_event_set_period",
        "drivers/perf/arm_pmu.c:armpmu_event_set_period"
      ],
      "caller_func": []
    },
    {
      "addr": 3234334004,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "drivers/ras/debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ras/debugfs.c:trace_release",
        "drivers/ras/debugfs.c:trace_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3234356744,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "sound/core/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/control.c:snd_ctl_dev_disconnect",
        "sound/core/control.c:snd_ctl_get_preferred_subdevice"
      ],
      "caller_func": []
    },
    {
      "addr": 3234411056,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "sound/core/pcm_native.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/pcm_native.c:snd_pcm_mmap_data",
        "sound/core/pcm_native.c:snd_pcm_mmap_data_fault",
        "sound/core/pcm_native.c:snd_pcm_mmap_data_close",
        "sound/core/pcm_native.c:snd_pcm_mmap_data_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3234618584,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:do_recvmmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3234629304,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/sock.c:sock_kzfree_s",
        "net/core/sock.c:sock_kfree_s",
        "net/core/sock.c:sock_kmalloc",
        "net/core/sock.c:sock_kmalloc",
        "net/core/sock.c:sock_omalloc",
        "net/core/sock.c:sock_ofree",
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_setup_caps",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_getsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setbindtodevice_locked",
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/sock.c:sk_set_memalloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234679172,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:sock_rmem_free",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:sock_zerocopy_put_abort",
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:mm_unaccount_pinned_pages",
        "net/core/skbuff.c:__skb_clone",
        "net/core/skbuff.c:__copy_skb_header",
        "net/core/skbuff.c:__copy_skb_header",
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_release_head_state",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:skb_release_data",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3234692568,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__sk_queue_drop_skb",
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/core/datagram.c:__skb_wait_for_more_packets"
      ],
      "caller_func": []
    },
    {
      "addr": 3234697948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/stream.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/stream.c:sk_stream_error",
        "net/core/stream.c:sk_stream_wait_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 3234702108,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/scm.c:scm_fp_dup",
        "net/core/scm.c:scm_detach_fds"
      ],
      "caller_func": []
    },
    {
      "addr": 3234706712,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/gen_estimator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gen_estimator.c:gen_kill_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 3234709448,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:cleanup_net",
        "net/core/net_namespace.c:copy_net_ns",
        "net/core/net_namespace.c:copy_net_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3234730168,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/sysctl_net_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3234790272,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:napi_schedule_prep",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:__netif_receive_skb_core",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:__netif_set_xps_queue",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:clean_xps_maps",
        "net/core/dev.c:__dev_forward_skb",
        "net/core/dev.c:net_disable_timestamp",
        "net/core/dev.c:net_enable_timestamp",
        "net/core/dev.c:net_dec_egress_queue",
        "net/core/dev.c:net_inc_egress_queue",
        "net/core/dev.c:net_dec_ingress_queue",
        "net/core/dev.c:net_inc_ingress_queue",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 3234837096,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:__dst_destroy_metrics_generic",
        "net/core/dst.c:dst_cow_metrics_generic",
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release",
        "net/core/dst.c:dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3234844820,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_update",
        "net/core/neighbour.c:__neigh_event_send",
        "net/core/neighbour.c:neigh_probe",
        "net/core/neighbour.c:neigh_destroy",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:___neigh_create",
        "net/core/neighbour.c:neigh_mark_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 3234942428,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_get_skb_set_tunnel_proto",
        "net/core/filter.c:bpf_skb_set_tunnel_key",
        "net/core/filter.c:bpf_clear_redirect_map",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_push_data",
        "net/core/filter.c:bpf_msg_pull_data",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__sk_filter_charge",
        "net/core/filter.c:sk_filter_uncharge"
      ],
      "caller_func": []
    },
    {
      "addr": 3234975712,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/sock_diag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_diag.c:sock_gen_cookie",
        "net/core/sock_diag.c:sock_gen_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 3234988160,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/xdp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:__xdp_return",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_id_disconnect",
        "net/core/xdp.c:mem_xa_remove",
        "net/core/xdp.c:mem_xa_remove",
        "net/core/xdp.c:mem_xa_remove",
        "net/core/xdp.c:mem_xa_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3234993968,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/flow_offload.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/core/flow_offload.c:__flow_indr_block_cb_register",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3235002404,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:store_rps_map",
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3235008956,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:page_pool_release",
        "net/core/page_pool.c:__page_pool_clean_page",
        "net/core/page_pool.c:__page_pool_alloc_pages_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 3235019604,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235026052,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3235077688,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/lwtunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/lwtunnel.c:lwtunnel_encap_del_ops",
        "net/core/lwtunnel.c:lwtunnel_encap_add_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 3235090756,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_free_elem",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_free",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link",
        "net/core/sock_map.c:sock_map_link"
      ],
      "caller_func": []
    },
    {
      "addr": 3235091488,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4",
        "net/core/dst_cache.c:dst_cache_per_cpu_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3235150428,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/gro_cells.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gro_cells.c:gro_cells_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 3235155500,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc",
        "net/core/bpf_sk_storage.c:sk_storage_update",
        "net/core/bpf_sk_storage.c:__selem_unlink_sk",
        "net/core/bpf_sk_storage.c:__selem_unlink_sk",
        "net/core/bpf_sk_storage.c:selem_alloc",
        "net/core/bpf_sk_storage.c:omem_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 3235162708,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/sched/sch_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235178464,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 3235189832,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tc_cls_offload_cnt_update",
        "net/sched/cls_api.c:tcf_block_offload_dec",
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 3235217680,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_set_action_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 3235228936,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235236940,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/netlink/af_netlink.c:netlink_remove",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:__netlink_insert",
        "net/netlink/af_netlink.c:netlink_skb_set_owner_r",
        "net/netlink/af_netlink.c:netlink_skb_destructor",
        "net/netlink/af_netlink.c:netlink_overrun"
      ],
      "caller_func": []
    },
    {
      "addr": 3235271588,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_buf_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3235272700,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235276656,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ipv4_sysctl_rtcache_flush",
        "net/ipv4/route.c:ip_rt_multicast_event",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/route.c:rt_dst_clone",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/route.c:ip_idents_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 3235304052,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/protocol.c:inet_del_offload",
        "net/ipv4/protocol.c:inet_del_protocol",
        "net/ipv4/protocol.c:inet_add_offload",
        "net/ipv4/protocol.c:inet_add_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 3235307972,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ip_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_input.c:ip_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235309816,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue",
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3235317908,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 3235329280,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_copy_metadata",
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3235341172,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235359148,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_alloc",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 3235363204,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/inet_connection_sock.c:inet_csk_clone_lock",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_hash_add",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3235375224,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_alloc_md5sig_pool",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3235413796,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_syn_flood_action",
        "net/ipv4/tcp_input.c:inet_reqsk_alloc",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_queue_rcv",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:clean_acked_data_disable",
        "net/ipv4/tcp_input.c:clean_acked_data_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 3235473904,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:sk_forced_mem_schedule",
        "net/ipv4/tcp_output.c:__pskb_trim_head",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_release_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235487036,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_md5_do_del",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 3235506740,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3235511956,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 3235522816,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 3235529944,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 3235534260,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_bind",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 3235553560,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:udp_queue_rcv_one_skb",
        "net/ipv4/udp.c:__udp_disconnect",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__first_packet_length",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb",
        "net/ipv4/udp.c:udp_rmem_release",
        "net/ipv4/udp.c:udp_sendmsg",
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235571376,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3235584208,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_rcv",
        "net/ipv4/icmp.c:icmp_out_count"
      ],
      "caller_func": []
    },
    {
      "addr": 3235610664,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/ipv4/af_inet.c:__inet_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 3235637228,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:ip_mc_drop_socket",
        "net/ipv4/igmp.c:ip_mc_msfilter",
        "net/ipv4/igmp.c:ip_mc_source",
        "net/ipv4/igmp.c:ip_mc_leave_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3235648268,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/fib_frontend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_frontend.c:fib_netdev_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event",
        "net/ipv4/fib_frontend.c:fib_inetaddr_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3235651708,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/fib_semantics.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/fib_semantics.c:fib_nh_common_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3235685132,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frag_pull_head",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_finish",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_reasm_prepare",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/inet_fragment.c:inet_frag_create",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/inet_fragment.c:inet_frag_kill",
        "net/ipv4/inet_fragment.c:inet_frag_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 3235697148,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_bind",
        "net/ipv4/ping.c:ping_init_sock",
        "net/ipv4/ping.c:ping_init_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3235700788,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ip_tunnel_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_unneed_metadata",
        "net/ipv4/ip_tunnel_core.c:ip_tunnel_need_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 3235736888,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_queue_xmit",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:mroute_clean_tables",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_add",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:ipmr_mfc_delete",
        "net/ipv4/ipmr.c:ipmr_cache_unresolved",
        "net/ipv4/ipmr.c:ipmr_cache_report",
        "net/ipv4/ipmr.c:ipmr_destroy_unres",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 3235754536,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235765564,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235774824,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 3235816100,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_policy_insert",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin",
        "net/xfrm/xfrm_policy.c:xfrm_policy_kill",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 3235827732,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel",
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 3235851940,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input",
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 3235857160,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_resume",
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3235865836,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": []
    },
    {
      "addr": 3235882528,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/unix/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_seqpacket_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:unix_create1",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:unix_sock_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 3235886324,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/unix/garbage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/garbage.c:inc_inflight",
        "net/unix/garbage.c:dec_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 3235889012,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/unix/scm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/unix/scm.c:unix_notinflight",
        "net/unix/scm.c:unix_inflight"
      ],
      "caller_func": []
    },
    {
      "addr": 3235892896,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 3235920868,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:__ip6_append_data",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_output.c:ip6_copy_metadata",
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 3235926208,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ip6_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3235941460,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:__ipv6_ifa_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 3236017084,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_init",
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_rt_copy_init",
        "net/ipv6/route.c:rt6_score_route",
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/route.c:ip6_dst_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3236040728,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_new_sernum"
      ],
      "caller_func": []
    },
    {
      "addr": 3236046000,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 3236057656,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ndisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb",
        "net/ipv6/ndisc.c:ndisc_send_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3236071488,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udpv6_destroy_sock",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:udpv6_sendmsg",
        "net/ipv6/udp.c:__udp6_lib_mcast_deliver",
        "net/ipv6/udp.c:udpv6_queue_rcv_one_skb",
        "net/ipv6/udp.c:__udp6_lib_err",
        "net/ipv6/udp.c:udpv6_encap_enable",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236094484,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_sendmsg",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:rawv6_rcv",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 3236104720,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_rcv",
        "net/ipv6/icmp.c:icmpv6_notify",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ],
      "caller_func": []
    },
    {
      "addr": 3236116820,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:igmp6_send",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:mld_sendpack",
        "net/ipv6/mcast.c:inet6_mc_check",
        "net/ipv6/mcast.c:__ipv6_sock_mc_close",
        "net/ipv6/mcast.c:ipv6_sock_mc_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 3236132484,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/reassembly.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/reassembly.c:ip6_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 3236151832,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_err",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3236153976,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ping.c:ping_v6_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3236170100,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu",
        "net/ipv6/datagram.c:ip6_datagram_dst_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3236175948,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ip6_flowlabel_net_exit",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:fl_create",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:ip6_fl_gc",
        "net/ipv6/ip6_flowlabel.c:fl_release",
        "net/ipv6/ip6_flowlabel.c:fl_free",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3236207356,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:mroute_clean_tables",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_add",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_mfc_delete",
        "net/ipv6/ip6mr.c:ip6mr_cache_unresolved",
        "net/ipv6/ip6mr.c:ip6mr_cache_report",
        "net/ipv6/ip6mr.c:ip6mr_destroy_unres",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3236208400,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/xfrm6_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 3236218100,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3236231620,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_req_delattr",
        "net/ipv6/calipso.c:calipso_req_delattr",
        "net/ipv6/calipso.c:calipso_req_setattr",
        "net/ipv6/calipso.c:calipso_req_setattr",
        "net/ipv6/calipso.c:calipso_opt_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3236239768,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 3236245396,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/seg6_hmac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_del",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add",
        "net/ipv6/seg6_hmac.c:seg6_hmac_info_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3236250576,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_icmp.c:inet6_unregister_icmp_sender",
        "net/ipv6/ip6_icmp.c:inet6_register_icmp_sender"
      ],
      "caller_func": []
    },
    {
      "addr": 3236252180,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/ipv6/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/protocol.c:inet6_del_offload",
        "net/ipv6/protocol.c:inet6_add_offload",
        "net/ipv6/protocol.c:inet6_del_protocol",
        "net/ipv6/protocol.c:inet6_add_protocol"
      ],
      "caller_func": []
    },
    {
      "addr": 3236267652,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_mmap",
        "net/packet/af_packet.c:packet_mm_close",
        "net/packet/af_packet.c:packet_mm_open",
        "net/packet/af_packet.c:packet_getsockopt",
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv",
        "net/packet/af_packet.c:packet_rcv_spkt",
        "net/packet/af_packet.c:packet_rcv_fanout",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ],
      "caller_func": []
    },
    {
      "addr": 3236328856,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/netlabel/netlabel_unlabeled.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_remove",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add"
      ],
      "caller_func": []
    },
    {
      "addr": 3236332540,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/netlabel/netlabel_cipso_v4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236335988,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_ops_register",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3236338852,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3236363744,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/dns_resolver/dns_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/dns_resolver/dns_key.c:put_cred"
      ],
      "caller_func": []
    },
    {
      "addr": 3236411744,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_unaccount_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3236428776,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/dec_and_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236429408,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/dump_stack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dump_stack.c:dump_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 3236459872,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/arm/include/asm/processor.h:130",
      "file": "lib/nmi_backtrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282892392,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "arch/powerpc/lib/sstep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/lib/sstep.c:emulate_step"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285520272,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285859652,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286264256,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287059120,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287329684,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288265416,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295345016,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/powerpc/include/asm/processor.h:385",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369423,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885998,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913706,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144365,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432145,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953669,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138070,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796684,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588016481,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579299151,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820974,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859770,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091309,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374561,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891237,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075510,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582733836,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587729569,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369343,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579874158,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904954,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135565,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423345,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944981,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128550,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582785564,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588348257,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
  "name": "prefetchw",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579377791,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919678,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/locking/qspinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963031,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cpumap.c:cpu_map_kthread_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198045,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487793,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__free_pages_core",
        "mm/page_alloc.c:__free_pages_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015013,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:new_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201606,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871964,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588483777,
      "name": "prefetchw",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:805",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__kfree_skb_defer",
        "net/core/skbuff.c:__alloc_skb",
        "net/core/skbuff.c:__alloc_skb"
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void prefetchw(const void * x)
```
</details>
</li>
</ul>
