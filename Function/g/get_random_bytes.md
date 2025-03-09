# Function: <code>get_random_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584168400,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1253",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/panic.c:print_oops_end_marker",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/crypto_policy.c:ext4_process_policy",
        "fs/ext4/crypto_policy.c:ext4_inherit_context",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "lib/random32.c:__prandom_timer",
        "lib/random32.c:prandom_seed_full_state",
        "lib/rhashtable.c:bucket_table_alloc",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:proc_do_uuid",
        "drivers/char/random.c:random_int_secret_init",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/md/md.c:md_ioctl",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/core/flow.c:flow_cache_lookup",
        "net/ipv4/route.c:rt_genid_init",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/inet_fragment.c:inet_frag_worker",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:__ipv6_regen_rndid",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584168400,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512384,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1502",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/panic.c:print_oops_end_marker",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_process_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "lib/rhashtable.c:bucket_table_alloc",
        "drivers/char/random.c:random_int_secret_init",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:crng_initialize",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/md/md.c:md_ioctl",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/core/flow.c:flow_cache_lookup",
        "net/ipv4/route.c:rt_genid_init",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/inet_fragment.c:inet_frag_worker",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:__ipv6_regen_rndid",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512384,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584694448,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1502",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/panic.c:print_oops_end_marker",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "lib/rhashtable.c:bucket_table_alloc",
        "drivers/char/random.c:random_int_secret_init",
        "drivers/char/random.c:get_random_bytes_arch",
        "drivers/char/random.c:crng_initialize",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/neighbour.c:neigh_hash_alloc",
        "net/core/flow.c:flow_cache_lookup",
        "net/ipv4/route.c:rt_genid_init",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/fib_semantics.c:fib_rebalance",
        "net/ipv4/inet_fragment.c:inet_frag_worker",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694448,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584776719,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1530",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/panic.c:print_oops_end_marker",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/core/flow.c:flow_cache_lookup",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/inet_fragment.c:inet_frag_worker",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584776544,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585196815,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1529",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/panic.c:print_oops_end_marker",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/md/md.c:md_ioctl",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/ip_fragment.c:ipqhashfn",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/inet_fragment.c:inet_frag_worker",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/reassembly.c:inet6_hash_frag",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585196640,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585433336,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1634",
      "file": "drivers/char/random.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:get_random_bytes_arch"
      ],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433168,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557264,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1643",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/output_core.c:ipv6_proxy_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557264,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585777664,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1725",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_inherit_context",
        "fs/crypto/policy.c:fscrypt_ioctl_set_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777664,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585920368,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920368,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1571",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/panic.c:__warn",
        "kernel/panic.c:oops_exit",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher",
        "fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/route.c:__rt6_find_exception_spinlock",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:subflow_rebuild_header",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/token.c:mptcp_token_new_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586659358,
      "name": "get_random_bytes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586657840,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1570",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/panic.c:__warn",
        "kernel/panic.c:oops_exit",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/policy.c:set_encryption_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher",
        "fs/ecryptfs/crypto.c:ecryptfs_write_headers_virt",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "drivers/md/md.c:md_set_array_info",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/route.c:__rt6_find_exception_spinlock",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/output_core.c:ipv6_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/token.c:mptcp_token_new_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591462323,
      "name": "get_random_bytes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586768368,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1546",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/panic.c:__warn",
        "kernel/panic.c:oops_exit",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/policy.c:set_encryption_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "drivers/md/md.c:md_set_array_info",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591403860,
      "name": "get_random_bytes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586647632,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1566",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/panic.c:__warn",
        "kernel/panic.c:oops_exit",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_add_test_dummy_key",
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/policy.c:set_encryption_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "drivers/md/md.c:md_set_array_info",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592454730,
      "name": "get_random_bytes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587195264,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void get_random_bytes(void * buf, size_t len)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588499888,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:393",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/policy.c:set_encryption_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/random32.c:prandom_seed_full_state",
        "lib/uuid.c:uuid_gen",
        "lib/uuid.c:guid_gen",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "lib/vsprintf.c:__ptr_to_hashval",
        "drivers/md/md.c:md_set_array_info",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499888,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void get_random_bytes(void * buf, size_t len)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589934912,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:414",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/policy.c:set_encryption_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/random32.c:prandom_seed_full_state",
        "lib/uuid.c:uuid_gen",
        "lib/uuid.c:guid_gen",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_set_array_info",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash",
        "lib/vsprintf.c:fill_ptr_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589934912,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void get_random_bytes(void * buf, size_t len)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590244912,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:414",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/policy.c:set_encryption_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/random32.c:prandom_seed_full_state",
        "lib/uuid.c:uuid_gen",
        "lib/uuid.c:guid_gen",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/md/md.c:md_set_array_info",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash",
        "lib/vsprintf.c:fill_ptr_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590244912,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void get_random_bytes(void * buf, size_t len)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590585936,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:414",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/keyring.c:fscrypt_get_test_dummy_secret",
        "fs/crypto/keysetup.c:fscrypt_prepare_new_inode",
        "fs/crypto/policy.c:set_encryption_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/trusted-keys/trusted_core.c:kernel_get_random",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_seed_from_random",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/random32.c:prandom_seed_full_state",
        "lib/uuid.c:uuid_gen",
        "lib/uuid.c:guid_gen",
        "lib/uuid.c:generate_random_guid",
        "lib/uuid.c:generate_random_uuid",
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/md/md.c:md_set_array_info",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/ethtool/ioctl.c:netdev_rss_key_fill",
        "net/ipv4/route.c:ip_rt_init",
        "net/ipv4/route.c:fnhe_hashfun",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:__inet_hash_connect",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp_ehashfn",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/udp.c:udp6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/mptcp/subflow.c:__mptcp_subflow_connect",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/subflow.c:subflow_check_req",
        "net/mptcp/token.c:mptcp_token_new_connect",
        "net/mptcp/syncookies.c:mptcp_join_entry_hash",
        "lib/vsprintf.c:fill_ptr_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590585936,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498741512,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/arm64/kernel/process.c:arch_setup_new_exec",
        "arch/arm64/kernel/process.c:arch_setup_new_exec",
        "arch/arm64/kernel/process.c:arch_setup_new_exec",
        "arch/arm64/kernel/process.c:arch_setup_new_exec",
        "arch/arm64/kernel/process.c:arch_setup_new_exec",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "arch/arm64/kernel/pointer_auth.c:ptrauth_prctl_reset_keys",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498741512,
      "name": "get_random_bytes",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231361112,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:__ipv6_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231361112,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291896048,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291896048,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276243776,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/output_core.c:__ipv6_select_ident",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276243776,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681344,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681344,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541216,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/net/vxlan.c:vxlan_init_module",
        "drivers/net/vxlan.c:vxlan_setup",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/ip_tunnel.c:ip_tunnel_newlink",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541216,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870768,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/netfilter/nf_conntrack_core.c:nf_ct_get_id",
        "net/netfilter/nf_conntrack_core.c:hash_conntrack_raw",
        "net/netfilter/nf_conntrack_expect.c:nf_ct_expect_dst_hash",
        "net/netfilter/nf_conntrack_netlink.c:nf_expect_get_id",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870768,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void get_random_bytes(void * buf, int nbytes)
```

```json
{
  "name": "get_random_bytes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978672,
      "name": "get_random_bytes",
      "external": true,
      "loc": "drivers/char/random.c:1726",
      "file": "drivers/char/random.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/kcmp.c:kcmp_cookies_init",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/crypto/policy.c:fscrypt_new_context_from_policy",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm",
        "fs/ecryptfs/crypto.c:ecryptfs_write_metadata",
        "fs/ecryptfs/crypto.c:ecryptfs_new_file_context",
        "fs/fuse/inode.c:fuse_conn_init",
        "security/keys/key.c:key_alloc",
        "security/keys/big_key.c:big_key_preparse",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "security/keys/encrypted-keys/encrypted.c:encrypted_instantiate",
        "crypto/rng.c:crypto_rng_reset",
        "crypto/drbg.c:drbg_seed",
        "crypto/drbg.c:drbg_async_seed",
        "lib/random32.c:prandom_seed_full_state",
        "lib/random32.c:__prandom_timer",
        "lib/uuid.c:generate_random_uuid",
        "drivers/md/md.c:md_ioctl",
        "net/core/net_namespace.c:setup_net",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_ipv4_port_ephemeral",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcp_ts_off",
        "net/core/secure_seq.c:secure_ipv6_port_ephemeral",
        "net/core/secure_seq.c:secure_tcpv6_seq",
        "net/core/secure_seq.c:secure_tcpv6_ts_off",
        "net/core/flow_dissector.c:__skb_get_hash",
        "net/core/flow_dissector.c:__skb_get_hash_symmetric",
        "net/core/flow_dissector.c:flow_hash_from_keys",
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/core/ethtool.c:netdev_rss_key_fill",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:find_exception",
        "net/ipv4/route.c:update_or_create_fnhe",
        "net/ipv4/route.c:__ip_select_ident",
        "net/ipv4/inet_hashtables.c:inet_ehashfn",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once",
        "net/ipv4/udp.c:udp_flow_hashrnd",
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/syncookies.c:cookie_hash",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_addr_gen",
        "net/ipv6/addrconf.c:ipv6_regen_rndid",
        "net/ipv6/addrconf.c:ipv6_create_tempaddr",
        "net/ipv6/route.c:rt6_exception_hash",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/syncookies.c:cookie_hash",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "net/ipv6/inet6_hashtables.c:inet6_ehashfn",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978672,
      "name": "get_random_bytes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>int nbytes</code>
</li>
</ul>
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
