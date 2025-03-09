# Function: <code>flow_block_cmd</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588689888,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689888,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502246640,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502246640,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234991012,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234991012,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295737840,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295737840,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278486466,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278486466,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588296624,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296624,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588009440,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588009440,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588628448,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588628448,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```

```json
{
  "name": "flow_block_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766864,
      "name": "flow_block_cmd",
      "external": false,
      "loc": "net/core/flow_offload.c:396",
      "file": "net/core/flow_offload.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_offload.c:__flow_indr_block_cb_unregister",
        "net/core/flow_offload.c:__flow_indr_block_cb_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766864,
      "name": "flow_block_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void flow_block_cmd(struct net_device * dev, flow_indr_block_bind_cb_t * cb, void * cb_priv, enum flow_block_command command)
```
</details>
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
