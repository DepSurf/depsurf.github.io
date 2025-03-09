# Function: <code>bpf_fd_htab_map_update_elem</code>

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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534800,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1271",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534800,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598624,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1305",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598624,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580693904,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1329",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580693904,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766240,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1397",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766240,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580850160,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850160,
      "name": "bpf_fd_htab_map_update_elem",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901200,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901200,
      "name": "bpf_fd_htab_map_update_elem",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046288,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1825",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046288,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056864,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2094",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056864,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071712,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2159",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071712,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581299024,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2345",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299024,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581596496,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2408",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596496,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977344,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2439",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977344,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168880,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2494",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168880,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582317552,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:2516",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_update_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582317552,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492229784,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492229784,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226125892,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226125892,
      "name": "bpf_fd_htab_map_update_elem",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285454496,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285454496,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272376622,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272376622,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580870000,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870000,
      "name": "bpf_fd_htab_map_update_elem",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816128,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816128,
      "name": "bpf_fd_htab_map_update_elem",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861248,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861248,
      "name": "bpf_fd_htab_map_update_elem",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "bpf_fd_htab_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580919728,
      "name": "bpf_fd_htab_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/hashtab.c:1433",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580919728,
      "name": "bpf_fd_htab_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int bpf_fd_htab_map_update_elem(struct bpf_map * map, struct file * map_file, void * key, void * value, u64 map_flags)
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
