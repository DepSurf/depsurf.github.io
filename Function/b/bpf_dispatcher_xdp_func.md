# Function: <code>bpf_dispatcher_xdp_func</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, unsigned int (*)(const void *, const struct bpf_insn *) bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589492208,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:9242",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589492208,
      "name": "bpf_dispatcher_xdp_func",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, unsigned int (*)(const void *, const struct bpf_insn *) bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589493840,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:10293",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589493840,
      "name": "bpf_dispatcher_xdp_func",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, unsigned int (*)(const void *, const struct bpf_insn *) bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589392336,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:10435",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/devmap.c:dev_map_run_prog",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/core/dev.c:netif_receive_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392336,
      "name": "bpf_dispatcher_xdp_func",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, unsigned int (*)(const void *, const struct bpf_insn *) bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590122992,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:10634",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:tun_build_skb",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590122992,
      "name": "bpf_dispatcher_xdp_func",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, unsigned int (*)(const void *, const struct bpf_insn *) bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591672048,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:11166",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591672048,
      "name": "bpf_dispatcher_xdp_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, bpf_func_t bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593473776,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:11372",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593473776,
      "name": "bpf_dispatcher_xdp_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, bpf_func_t bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593940192,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:11521",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593940192,
      "name": "bpf_dispatcher_xdp_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, bpf_func_t bpf_func)
```

```json
{
  "name": "bpf_dispatcher_xdp_func",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594722960,
      "name": "bpf_dispatcher_xdp_func",
      "external": true,
      "loc": "net/core/filter.c:11612",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/devmap.c:dev_map_bpf_prog_run",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "drivers/net/virtio_net.c:virtnet_xdp_handler",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/core/dev.c:bpf_prog_run_generic_xdp",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594722960,
      "name": "bpf_dispatcher_xdp_func",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int bpf_dispatcher_xdp_func(const void * ctx, const struct bpf_insn * insnsi, unsigned int (*)(const void *, const struct bpf_insn *) bpf_func)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int (*)(const void *, const struct bpf_insn *) bpf_func</code> ➡️ <code>bpf_func_t bpf_func</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
