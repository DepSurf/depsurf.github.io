# Function: <code>seg6_validate_srh</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587863904,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:32",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_iptunnel.c:seg6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587863904,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588020032,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:32",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_iptunnel.c:seg6_build_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588020032,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588556816,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:32",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556816,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588920864,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:32",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_lwt_seg6_action",
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:input_action_end_bpf",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588920864,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589144432,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:33",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589144432,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598624,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598624,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589823008,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589823008,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590847840,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590847840,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590908624,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590908624,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590837984,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590837984,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591657801,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591656000,
      "name": "seg6_validate_srh.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071591657520,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593352557,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593350640,
      "name": "seg6_validate_srh.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071593352256,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595259245,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595257200,
      "name": "seg6_validate_srh.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071595258928,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595654605,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595652576,
      "name": "seg6_validate_srh.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071595654288,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len, bool reduced)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596502253,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6.c:seg6_get_srh"
      ],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/ipv6_sockglue.c:ipv6_set_opt_hdr",
        "net/ipv6/seg6.c:seg6_get_srh",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596500080,
      "name": "seg6_validate_srh.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596501936,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503531432,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503531432,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236184508,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236184508,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297327968,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297327968,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279498326,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279498326,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589427376,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427376,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152368,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152368,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589864240,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589864240,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```

```json
{
  "name": "seg6_validate_srh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589915712,
      "name": "seg6_validate_srh",
      "external": true,
      "loc": "net/ipv6/seg6.c:28",
      "file": "net/ipv6/seg6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_push_seg6_encap",
        "net/ipv6/seg6_iptunnel.c:seg6_build_state",
        "net/ipv6/seg6_local.c:parse_nla_srh",
        "net/ipv6/seg6_local.c:seg6_bpf_has_valid_srh",
        "net/ipv6/seg6_local.c:get_srh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589915712,
      "name": "seg6_validate_srh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool seg6_validate_srh(struct ipv6_sr_hdr * srh, int len)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reduced</code>
</li>
</ul>
</details>
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
