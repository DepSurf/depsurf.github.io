# Function: <code>__xdp_return</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587997744,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:310",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997744,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 866
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588157280,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:324",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588157280,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588479312,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:393",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479312,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1087
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588684720,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588684720,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589551456,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:342",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589551456,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, struct xdp_buff * xdp)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589559376,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:341",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589559376,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, struct xdp_buff * xdp)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589457376,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:341",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457376,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, struct xdp_buff * xdp)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590194816,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:342",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590194816,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, struct xdp_buff * xdp)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591761824,
      "name": "__xdp_return",
      "external": true,
      "loc": "net/core/xdp.c:375",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_adjust_tail",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591761824,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, struct xdp_buff * xdp)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593553008,
      "name": "__xdp_return",
      "external": true,
      "loc": "net/core/xdp.c:375",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_adjust_tail",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593553008,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, struct xdp_buff * xdp)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594022320,
      "name": "__xdp_return",
      "external": true,
      "loc": "net/core/xdp.c:377",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_adjust_tail",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594022320,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, struct xdp_buff * xdp)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594808896,
      "name": "__xdp_return",
      "external": true,
      "loc": "net/core/xdp.c:377",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_frags_shrink_tail",
        "net/core/filter.c:bpf_xdp_frags_shrink_tail",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_buff",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594808896,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502242520,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502242520,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234988040,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234988040,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295734800,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295734800,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1108
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278483252,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278483252,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588291456,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291456,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588004272,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588004272,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588623280,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588623280,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```

```json
{
  "name": "__xdp_return",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588761280,
      "name": "__xdp_return",
      "external": false,
      "loc": "net/core/xdp.c:367",
      "file": "net/core/xdp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/xdp.c:xdp_convert_zc_to_xdp_frame",
        "net/core/xdp.c:xdp_return_frame_rx_napi",
        "net/core/xdp.c:xdp_return_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588761280,
      "name": "__xdp_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 847
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __xdp_return(void * data, struct xdp_mem_info * mem, bool napi_direct, long unsigned int handle)
```
</details>
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
<b>Param removed. </b>
<code>long unsigned int handle</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_buff * xdp</code>
</li>
</ul>
</details>
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
