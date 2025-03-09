# Function: <code>bpf_prog_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389232,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1136",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:put_seccomp_filter",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389232,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586828631,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1164",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__reuseport_attach_prog"
      ],
      "caller_func": [
        "kernel/seccomp.c:put_seccomp_filter",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/sock_reuseport.c:reuseport_free_rcu",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828544,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587015687,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1166",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__reuseport_attach_prog"
      ],
      "caller_func": [
        "kernel/seccomp.c:put_seccomp_filter",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/sock_reuseport.c:reuseport_free_rcu",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015600,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587143047,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1191",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__reuseport_attach_prog"
      ],
      "caller_func": [
        "kernel/seccomp.c:put_seccomp_filter",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/sock_reuseport.c:reuseport_free_rcu",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587142960,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587648503,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1212",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__reuseport_attach_prog"
      ],
      "caller_func": [
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/sock_reuseport.c:reuseport_free_rcu",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648416,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587966871,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1424",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__reuseport_attach_prog"
      ],
      "caller_func": [
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/core/sock_reuseport.c:reuseport_free_rcu",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966784,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588147284,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588118048,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588466516,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436160,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588672084,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642032,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589537341,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1415",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516880,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589546365,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1445",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523728,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589444077,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1445",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589422320,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590179021,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1446",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590148512,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591741388,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1447",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt",
        "net/packet/af_packet.c:packet_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591708608,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593530812,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1449",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593494192,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593996412,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1449",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593959920,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594780668,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1454",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_compat_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:packet_release",
        "net/packet/af_packet.c:fanout_set_data",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594742496,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502224716,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502186824,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234970644,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234934612,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295712228,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295665984,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278469346,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_get_metadata",
        "kernel/seccomp.c:seccomp_get_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_notify_release",
        "kernel/seccomp.c:seccomp_attach_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278442806,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588278820,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248768,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587991636,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961584,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588610644,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580592,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_prog_destroy(struct bpf_prog * fp)
```

```json
{
  "name": "bpf_prog_destroy",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588748324,
      "name": "bpf_prog_destroy",
      "external": true,
      "loc": "net/core/filter.c:1426",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free"
      ],
      "caller_func": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:__put_seccomp_filter",
        "drivers/net/tun.c:tun_prog_free",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_destroy_interface",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "net/packet/af_packet.c:__fanout_set_data_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588718080,
      "name": "bpf_prog_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
