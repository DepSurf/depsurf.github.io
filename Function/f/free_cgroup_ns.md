# Function: <code>free_cgroup_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579979168,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup.c:5976",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/cgroup.c:cgroupns_put",
        "kernel/cgroup.c:cgroupns_install",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979168,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005824,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup.c:6343",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup.c:cgroupns_put",
        "kernel/cgroup.c:cgroupns_install",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005824,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039424,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup.c:6382",
      "file": "kernel/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup.c:cgroupns_put",
        "kernel/cgroup.c:cgroupns_install",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039424,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580060848,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:39",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580060848,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113088,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113088,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172752,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172752,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220640,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/cgroup.c:cgroup_mount",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220640,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269536,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269536,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317696,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317696,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389520,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389520,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376480,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376480,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580379424,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580379424,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580541344,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_file_release",
        "kernel/cgroup/cgroup.c:cgroup_file_open",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541344,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738896,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_file_release",
        "kernel/cgroup/cgroup.c:cgroup_file_open",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738896,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581015440,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_file_release",
        "kernel/cgroup/cgroup.c:cgroup_file_open",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581015440,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103856,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_file_release",
        "kernel/cgroup/cgroup.c:cgroup_file_open",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103856,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581201664,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_file_release",
        "kernel/cgroup/cgroup.c:cgroup_file_open",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201664,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491573304,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491573304,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225536864,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225536864,
      "name": "free_cgroup_ns",
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284552176,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284552176,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271984532,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271984532,
      "name": "free_cgroup_ns",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286496,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286496,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233872,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233872,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277744,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277744,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void free_cgroup_ns(struct cgroup_namespace * ns)
```

```json
{
  "name": "free_cgroup_ns",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331600,
      "name": "free_cgroup_ns",
      "external": true,
      "loc": "kernel/cgroup/namespace.c:40",
      "file": "kernel/cgroup/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/nsproxy.c:free_nsproxy",
        "kernel/nsproxy.c:create_new_namespaces",
        "kernel/cgroup/cgroup.c:cgroup_fs_context_free",
        "kernel/cgroup/namespace.c:cgroupns_put",
        "kernel/cgroup/namespace.c:cgroupns_install"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331600,
      "name": "free_cgroup_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
