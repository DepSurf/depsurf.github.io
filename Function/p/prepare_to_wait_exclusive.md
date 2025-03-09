# Function: <code>prepare_to_wait_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void prepare_to_wait_exclusive(wait_queue_head_t * q, wait_queue_t * wait, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579645088,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:186",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait.c:__wait_on_bit_lock",
        "block/blk-core.c:get_request",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645088,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void prepare_to_wait_exclusive(wait_queue_head_t * q, wait_queue_t * wait, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579659808,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:186",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait.c:__wait_on_bit_lock",
        "fs/dax.c:get_unlocked_mapping_entry",
        "block/blk-core.c:get_request",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579659808,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void prepare_to_wait_exclusive(wait_queue_head_t * q, wait_queue_t * wait, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684352,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:186",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait.c:__wait_on_bit_lock",
        "fs/dax.c:get_unlocked_mapping_entry",
        "block/blk-core.c:get_request",
        "block/blk-wbt.c:wbt_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684352,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670224,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:188",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/dax.c:get_unlocked_mapping_entry",
        "block/blk-core.c:get_request",
        "block/blk-wbt.c:wbt_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670224,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701008,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:243",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/dax.c:get_unlocked_mapping_entry",
        "block/blk-core.c:get_request",
        "block/blk-wbt.c:wbt_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701008,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579735232,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:237",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/dax.c:__get_unlocked_mapping_entry",
        "block/blk-core.c:get_request",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-wbt.c:wbt_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735232,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774912,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:239",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774912,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802464,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802464,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850032,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850032,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888752,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:253",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888752,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882864,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:268",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882864,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892016,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:269",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892016,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
bool prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006944,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:277",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006944,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594715841,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:276",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138944,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
bool prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596463121,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:280",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "fs/dax.c:get_unlocked_entry",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "block/blk-rq-qos.c:rq_qos_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580313792,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597004945,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:280",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "fs/dax.c:get_unlocked_entry",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "block/blk-rq-qos.c:rq_qos_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380464,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597934289,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:245",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__wait_on_bit_lock"
      ],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "fs/dax.c:get_unlocked_entry",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:wait_transaction_locked",
        "block/blk-rq-qos.c:rq_qos_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580437744,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491043640,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491043640,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225050136,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225050136,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283920000,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283920000,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271641380,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271641380,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822384,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822384,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756992,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756992,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579810400,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579810400,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void prepare_to_wait_exclusive(struct wait_queue_head * wq_head, struct wait_queue_entry * wq_entry, int state)
```

```json
{
  "name": "prepare_to_wait_exclusive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855552,
      "name": "prepare_to_wait_exclusive",
      "external": true,
      "loc": "kernel/sched/wait.c:236",
      "file": "kernel/sched/wait.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/sched/wait_bit.c:__wait_on_bit_lock",
        "fs/io_uring.c:io_cqring_wait",
        "fs/dax.c:get_unlocked_entry",
        "block/blk-rq-qos.c:rq_qos_wait",
        "lib/sbitmap.c:sbitmap_prepare_to_wait",
        "net/core/sock.c:__lock_sock",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855552,
      "name": "prepare_to_wait_exclusive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head * wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry * wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t * q</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t * wait</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
