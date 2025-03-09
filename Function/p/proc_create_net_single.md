# Function: <code>proc_create_net_single</code>

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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154144,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:175",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154144,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248848,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:193",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248848,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413552,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413552,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512496,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512496,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816224,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:213",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816224,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582889040,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:197",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582889040,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582917504,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:197",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917504,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252112,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:197",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252112,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583751888,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:210",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583751888,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367712,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:207",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367712,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596064,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:207",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596064,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584827760,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:207",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/ipv4/proc.c:ip_proc_init_net",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late",
        "net/ipv6/proc.c:ipv6_proc_init_net",
        "net/ipv6/proc.c:ipv6_proc_init_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827760,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494140632,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494140632,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227587612,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227587612,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287816976,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287816976,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273619526,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273619526,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582481232,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481232,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582418464,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582418464,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471712,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471712,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
```

```json
{
  "name": "proc_create_net_single",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582552256,
      "name": "proc_create_net_single",
      "external": true,
      "loc": "fs/proc/proc_net.c:194",
      "file": "fs/proc/proc_net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_trie.c:fib_proc_init",
        "net/xfrm/xfrm_proc.c:xfrm_proc_init",
        "net/ipv6/route.c:ip6_route_net_init_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582552256,
      "name": "proc_create_net_single",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct proc_dir_entry * proc_create_net_single(const char * name, umode_t mode, struct proc_dir_entry * parent, int (*)(struct seq_file *, void *) show, void * data)
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
