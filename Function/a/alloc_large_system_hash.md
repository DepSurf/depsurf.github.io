# Function: <code>alloc_large_system_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595127147,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:6312",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidhash_init",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/dcache.c:vfs_caches_init",
        "fs/inode.c:inode_init",
        "fs/inode.c:inode_init_early",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595127147,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 545
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595299184,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:6938",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidhash_init",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595299184,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595547198,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:6989",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidhash_init",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595547198,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596471924,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:7299",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidhash_init",
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596471924,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 574
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602798745,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:7315",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602798745,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 594
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602971966,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:7497",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602971966,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 601
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604771940,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:7816",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604771940,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 604
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604891038,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8022",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604891038,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 657
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604924963,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604924963,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 637
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609238990,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8075",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609238990,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 605
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612305385,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8212",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init",
        "net/mptcp/token.c:mptcp_token_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612305385,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614445603,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8419",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init",
        "net/mptcp/token.c:mptcp_token_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614445603,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 606
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615388260,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8684",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init",
        "net/mptcp/token.c:mptcp_token_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615388260,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 843
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617178173,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8871",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex/core.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init",
        "net/mptcp/token.c:mptcp_token_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617178173,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 892
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627869440,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:9045",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex/core.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "lib/stackdepot.c:stack_depot_early_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init",
        "net/mptcp/token.c:mptcp_token_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627869440,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1047
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619619232,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/mm_init.c:2450",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex/core.c:futex_init",
        "kernel/futex/core.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "lib/stackdepot.c:stack_depot_early_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init",
        "net/mptcp/token.c:mptcp_token_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619619232,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1038
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621923488,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/mm_init.c:2446",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex/core.c:futex_init",
        "kernel/futex/core.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "lib/stackdepot.c:stack_depot_early_init",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init",
        "net/mptcp/token.c:mptcp_token_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621923488,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 927
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510963744,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510963744,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243450252,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243450252,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 848
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302617048,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302617048,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 824
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270690554,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270690554,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604830423,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604830423,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 637
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604799484,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604799484,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 637
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604907607,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604907607,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 637
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
void * alloc_large_system_hash(const char * tablename, long unsigned int bucketsize, long unsigned int numentries, int scale, int flags, unsigned int * _hash_shift, unsigned int * _hash_mask, long unsigned int low_limit, long unsigned int high_limit)
```

```json
{
  "name": "alloc_large_system_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604929144,
      "name": "alloc_large_system_hash",
      "external": true,
      "loc": "mm/page_alloc.c:8052",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/qspinlock.c:__pv_init_lock_hash",
        "kernel/futex.c:futex_init",
        "fs/dcache.c:vfs_caches_init",
        "fs/dcache.c:vfs_caches_init_early",
        "fs/inode.c:inode_init_early",
        "fs/inode.c:inode_init",
        "fs/namespace.c:mnt_init",
        "fs/namespace.c:mnt_init",
        "net/ipv4/inet_hashtables.c:inet_hashinfo2_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/tcp.c:tcp_init",
        "net/ipv4/udp.c:udp_table_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604929144,
      "name": "alloc_large_system_hash",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 637
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
