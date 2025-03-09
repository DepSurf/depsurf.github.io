# Function: <code>parent_mem_cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * parent_mem_cgroup(struct mem_cgroup * memcg)
```

```json
{
  "name": "parent_mem_cgroup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915280,
      "name": "parent_mem_cgroup",
      "external": true,
      "loc": "mm/memcontrol.c:4213",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:page_cgroup_ino",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_low"
      ],
      "caller_func": [
        "net/core/sock.c:__sk_mem_schedule",
        "net/core/sock.c:__sk_mem_schedule",
        "net/core/sock.c:sk_clone_lock",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_memcontrol.c:tcp_init_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915280,
      "name": "parent_mem_cgroup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581093006,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:386",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093413,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:386",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586611616,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:386",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587059927,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:386",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587085820,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:386",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128139,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:386",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131317,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:386",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581168254,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:388",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168661,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:388",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586795925,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:388",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256577,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:388",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587282642,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:388",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587326571,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:388",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587329787,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:388",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581216062,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581216513,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586920657,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587388740,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587397650,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587458473,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587461843,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581346702,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347153,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413239,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587905024,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587919149,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587980230,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587983951,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:382",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581494590,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:415",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581495500,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:415",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587715158,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:415",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256635,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:415",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588283363,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:415",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588330502,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:415",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588334726,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:415",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581580366,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:450",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581340,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:450",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848588,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:450",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588444843,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:450",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588456435,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:450",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588519635,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:450",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588523925,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:450",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581057292,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128609,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548659,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691440,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692339,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588152984,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850036,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588862562,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588929930,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934294,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:456",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581112990,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186435,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613539,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764864,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765763,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588358242,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589073208,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589086740,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589153876,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589158472,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581296859,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334660,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370930,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493759,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833417,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983544,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:mem_cgroup_update_tree",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984480,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589223261,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590037601,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590064973,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_prune_queue",
        "net/ipv4/tcp_input.c:tcp_prune_queue",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590123021,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590128899,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:467",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581340785,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377110,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581414559,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535311,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034025,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:get_obj_cgroup_from_current",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "mm/memcontrol.c:mem_cgroup_update_tree",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034464,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589221933,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590068656,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590109859,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_prune_queue",
        "net/ipv4/tcp_input.c:tcp_prune_queue",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_data_ready",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170749,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590176659,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591160708,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:787",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:__mptcp_wmem_reserve"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581359277,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581397881,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435839,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557423,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060228,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_flush_lruvec_page_state",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__mod_memcg_lruvec_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060672,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589115709,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589983008,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590024067,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_data_ready",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590085197,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590091059,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591099204,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:866",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_clean_una"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581607127,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648079,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689110,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821500,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582368168,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582368624,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589834180,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590752464,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590793840,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_data_ready",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590859831,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590866281,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591941812,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:862",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_clean_una"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581967399,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017069,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582062999,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582210774,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:memcg_list_lru_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212460,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866510,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:__get_obj_cgroup_from_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867329,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591357651,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592385325,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592424919,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_data_ready",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592496294,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592502818,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593652796,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:863",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:__mptcp_clean_una"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582403479,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582451430,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535618,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582697622,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:memcg_list_lru_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700524,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413813,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:__get_obj_cgroup_from_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583414689,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593124898,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_reduce_allocated",
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594234855,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594277882,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_data_ready",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594351862,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:854",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582609495,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582656662,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739234,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582911542,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:memcg_list_lru_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582914524,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583634085,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__get_obj_cgroup_from_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583634976,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593576360,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594621686,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594662442,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_data_ready",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594739782,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:872",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window",
        "net/ipv4/tcp_output.c:__tcp_select_window"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582780875,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582827798,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906850,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582927765,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/shrinker.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shrinker.c:reparent_shrinker_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085830,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/list_lru.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/list_lru.c:memcg_list_lru_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088412,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829013,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_rstat_flush",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_css_offline",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:get_obj_cgroup_from_folio",
        "mm/memcontrol.c:current_objcg_update",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:reclaim_high",
        "mm/memcontrol.c:reclaim_high",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583830013,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595424683,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595468458,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_data_ready",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595545310,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596955466,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_poll",
        "net/mptcp/protocol.c:mptcp_data_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597064908,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:891",
      "file": "net/mptcp/sockopt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/sockopt.c:mptcp_set_rcvlowat"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492480664,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492567460,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493062968,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493218764,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493221180,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501874360,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502689884,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502702136,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502769816,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502775200,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226354924,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226429472,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 3226769604,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226849908,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 3226850864,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3234630256,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 3235391212,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3235403200,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space",
        "net/ipv4/tcp_input.c:tcp_grow_window"
      ],
      "caller_func": []
    },
    {
      "addr": 3235474528,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 3235479380,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285765780,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285875640,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286497776,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286732948,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286735524,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295270212,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296299064,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:sk_stream_alloc_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296316152,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296402536,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296409320,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272546686,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272610682,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272925446,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272994712,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272995554,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278189970,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278820412,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278831750,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278891606,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278896216,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581081838,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155283,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582275,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733600,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734499,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587965026,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588679592,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588693124,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588760260,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588764856,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581029022,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102147,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523828,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672240,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673139,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587678130,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588391576,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588405108,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588472196,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588476792,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581073038,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146483,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573587,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724912,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725811,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588296802,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589115768,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589129300,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196436,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589201032,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
  "name": "parent_mem_cgroup",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581134707,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209043,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638624,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581793120,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_full",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_id_get_online",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:memory_max_write",
        "mm/memcontrol.c:mem_cgroup_css_released",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:memcg_stat_show",
        "mm/memcontrol.c:memcg_flush_percpu_vmevents",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:memcg_flush_percpu_vmstats",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state",
        "mm/memcontrol.c:page_cgroup_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794004,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmpressure.c:vmpressure_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588431958,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:__sk_mem_raise_allocated"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589155592,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589169124,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_check_space"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589236532,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_select_window"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589241160,
      "name": "parent_mem_cgroup",
      "external": false,
      "loc": "include/linux/memcontrol.h:490",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct mem_cgroup * parent_mem_cgroup(struct mem_cgroup * memcg)
```
</details>
</li>
</ul>
