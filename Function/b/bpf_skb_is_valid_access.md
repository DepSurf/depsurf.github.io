# Function: <code>bpf_skb_is_valid_access</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool bpf_skb_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587134352,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:3088",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134352,
      "name": "bpf_skb_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
bool bpf_skb_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637968,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:3576",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637968,
      "name": "bpf_skb_is_valid_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587965056,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:5075",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587965056,
      "name": "bpf_skb_is_valid_access.isra.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588116000,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:5719",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:flow_dissector_is_valid_access",
        "net/core/filter.c:flow_dissector_is_valid_access",
        "net/core/filter.c:flow_dissector_is_valid_access",
        "net/core/filter.c:flow_dissector_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116000,
      "name": "bpf_skb_is_valid_access.isra.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588434224,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6388",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434224,
      "name": "bpf_skb_is_valid_access.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588640096,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588640096,
      "name": "bpf_skb_is_valid_access.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589514708,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6688",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507968,
      "name": "bpf_skb_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589520260,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7493",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589511440,
      "name": "bpf_skb_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589419270,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7615",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589410336,
      "name": "bpf_skb_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590144886,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:7745",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590137504,
      "name": "bpf_skb_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591692720,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8129",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:cg_skb_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591692720,
      "name": "bpf_skb_is_valid_access.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593484448,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8268",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:cg_skb_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593484448,
      "name": "bpf_skb_is_valid_access.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593951280,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8420",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:cg_skb_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593951280,
      "name": "bpf_skb_is_valid_access.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594734080,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:8511",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:cg_skb_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594734080,
      "name": "bpf_skb_is_valid_access.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
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
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502184632,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502184632,
      "name": "bpf_skb_is_valid_access.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234932440,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234932440,
      "name": "bpf_skb_is_valid_access.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295663072,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access",
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295663072,
      "name": "bpf_skb_is_valid_access.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278440366,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:tc_cls_act_is_valid_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278440366,
      "name": "bpf_skb_is_valid_access.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588246832,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246832,
      "name": "bpf_skb_is_valid_access.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587959648,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587959648,
      "name": "bpf_skb_is_valid_access.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588578656,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578656,
      "name": "bpf_skb_is_valid_access.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bpf_skb_is_valid_access",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588716144,
      "name": "bpf_skb_is_valid_access",
      "external": false,
      "loc": "net/core/filter.c:6475",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588716144,
      "name": "bpf_skb_is_valid_access.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool bpf_skb_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
bool bpf_skb_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux * info)
```
</details>
</li>
</ul>
