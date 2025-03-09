# Function: <code>ipv6_find_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587233024,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:185",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587233024,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697568,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:185",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697568,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587911920,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:185",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911920,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588070256,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:185",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070256,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 945
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588614432,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:185",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588614432,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 945
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588980384,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:185",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980384,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 990
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204384,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:185",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204384,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 963
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589659415,
      "name": "ipv6_find_hdr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071589658480,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589882816,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882816,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590911600,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590911600,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590974816,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590974816,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590905696,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590905696,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 986
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591741312,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_local.c:input_action_end_dt46",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591741312,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 986
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593446240,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_local.c:input_action_end_dt46",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593446240,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595362640,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_local.c:input_action_end_dt46",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595362640,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595759824,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:188",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_local.c:input_action_end_dt46",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595759824,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1118
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596607984,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:188",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_local.c:input_action_end_dt46",
        "net/ipv6/seg6_local.c:decap_and_validate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596607984,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1114
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503603792,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503603792,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236248512,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236248512,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297415488,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297415488,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1252
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279556026,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279556026,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 720
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589487184,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589487184,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589212176,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589212176,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589928448,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589928448,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
int ipv6_find_hdr(const struct sk_buff * skb, unsigned int * offset, int target, short unsigned int * fragoff, int * flags)
```

```json
{
  "name": "ipv6_find_hdr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589977776,
      "name": "ipv6_find_hdr",
      "external": true,
      "loc": "net/ipv6/exthdrs_core.c:186",
      "file": "net/ipv6/exthdrs_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_adjust_srh",
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_update_srh_state",
        "net/core/filter.c:bpf_lwt_seg6_store_bytes",
        "net/ipv6/seg6_local.c:decap_and_validate",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589977776,
      "name": "ipv6_find_hdr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 897
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
