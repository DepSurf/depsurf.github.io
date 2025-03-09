# Function: <code>__skb_flow_dissect_gre</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586990882,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:225",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587489133,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:318",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587797148,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:320",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587932008,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:390",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588241696,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588446202,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310720,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:500",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310720,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
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
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589309696,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:517",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589309696,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 754
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
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, const void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589203728,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:524",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589203728,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, const void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589925712,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:525",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589925712,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 779
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
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, const void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591457872,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:527",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591457872,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, const void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593225920,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:551",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593225920,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, const void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593686400,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:585",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593686400,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, const void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```

```json
{
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594464112,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:629",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594464112,
      "name": "__skb_flow_dissect_gre",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501969484,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234723304,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295395032,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278268502,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588052986,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587766074,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588384762,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
  "name": "__skb_flow_dissect_gre",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588520404,
      "name": "__skb_flow_dissect_gre",
      "external": false,
      "loc": "net/core/flow_dissector.c:490",
      "file": "net/core/flow_dissector.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/flow_dissector.c:__skb_flow_dissect"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
enum flow_dissect_ret __skb_flow_dissect_gre(const struct sk_buff * skb, struct flow_dissector_key_control * key_control, struct flow_dissector * flow_dissector, void * target_container, void * data, __be16 * p_proto, int * p_nhoff, int * p_hlen, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * data</code> ➡️ <code>const void * data</code>
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
