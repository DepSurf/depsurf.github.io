# Function: <code>__nf_hook_entries_try_shrink</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587806576,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:196",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_unregister_net_hooks",
        "net/netfilter/core.c:nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806576,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588149712,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:221",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588149712,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332896,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:221",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332896,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588733280,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588733280,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588957088,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588957088,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589911184,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589911184,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589952096,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589952096,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589866928,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589866928,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590627840,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590627840,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592252512,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592252512,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594086448,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594086448,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594471456,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:234",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594471456,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595273776,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:234",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595273776,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502558688,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502558688,
      "name": "__nf_hook_entries_try_shrink",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235265844,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235265844,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296138096,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296138096,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278718338,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278718338,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563472,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563472,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588275456,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275456,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895648,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895648,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * old, struct nf_hook_entries * * pp)
```

```json
{
  "name": "__nf_hook_entries_try_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589037952,
      "name": "__nf_hook_entries_try_shrink",
      "external": false,
      "loc": "net/netfilter/core.c:222",
      "file": "net/netfilter/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/core.c:nf_hook_entries_delete_raw",
        "net/netfilter/core.c:__nf_unregister_net_hook"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589037952,
      "name": "__nf_hook_entries_try_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void * __nf_hook_entries_try_shrink(struct nf_hook_entries * * pp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nf_hook_entries * old</code>
</li>
<li>
<b>Param reordered. </b>
<code>pp</code> ➡️ <code>old, pp</code>
</li>
</ul>
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
