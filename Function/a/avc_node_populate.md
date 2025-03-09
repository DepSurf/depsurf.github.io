# Function: <code>avc_node_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582255242,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:567",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_update_node"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582474040,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:567",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_update_node"
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
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582566504,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:567",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_update_node"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655488,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:567",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_update_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655488,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582810624,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:563",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_update_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582810624,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583004800,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:587",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_update_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004800,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583118128,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:587",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av",
        "security/selinux/avc.c:avc_update_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583118128,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305168,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305168,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583409888,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583409888,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583751098,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583872570,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:518",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583898730,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:519",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584262698,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:519",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584871376,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:519",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871376,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585578768,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:519",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578768,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585810048,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585810048,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586058464,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586058464,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495163304,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495163304,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228551644,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228551644,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289100896,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289100896,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274409430,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_compute_av"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583378624,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583378624,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583315712,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583315712,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583362400,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583362400,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```

```json
{
  "name": "avc_node_populate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583457616,
      "name": "avc_node_populate",
      "external": false,
      "loc": "security/selinux/avc.c:515",
      "file": "security/selinux/avc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457616,
      "name": "avc_node_populate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void avc_node_populate(struct avc_node * node, u32 ssid, u32 tsid, u16 tclass, struct av_decision * avd)
```
</details>
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
