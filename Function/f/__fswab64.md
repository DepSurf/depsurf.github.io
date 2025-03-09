# Function: <code>__fswab64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__fswab64",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595059188,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "arch/x86/kernel/pci-calgary_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks",
        "arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271537,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "arch/x86/kernel/tce_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tce_64.c:tce_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580265712,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:get_pdu_int",
        "kernel/trace/blktrace.c:blk_log_remap",
        "kernel/trace/blktrace.c:blk_add_trace_unplug",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580362918,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/core.c:__bpf_prog_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595151710,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "mm/memtest.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memtest.c:reserve_bad_mem",
        "mm/memtest.c:early_memtest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581899517,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581909086,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916430,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008585,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582017365,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_i_size_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582656441,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "crypto/eseqiv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/eseqiv.c:eseqiv_givencrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582669079,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582677626,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "crypto/sha256_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha256_generic.c:crypto_sha256_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582680790,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:sha512_transform",
        "crypto/sha512_generic.c:crypto_sha512_finup",
        "crypto/sha512_generic.c:crypto_sha512_finup",
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844417,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143753,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584369224,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "drivers/lightnvm/sysblk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/sysblk.c:nvm_sysblk_to_cpu",
        "drivers/lightnvm/sysblk.c:nvm_cpu_to_sysblk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "drivers/block/virtio_blk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584814576,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584864081,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:read_capacity_16",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_pr_command",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_discard_cmnd",
        "drivers/scsi/sd.c:sd_setup_discard_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586388801,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_get_tunnel_key",
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587017464,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:check_cleanup_prefix_route",
        "net/ipv6/addrconf.c:check_cleanup_prefix_route",
        "net/ipv6/addrconf.c:ipv6_chk_custom_prefix",
        "net/ipv6/addrconf.c:ipv6_chk_custom_prefix",
        "net/ipv6/addrconf.c:ipv6_chk_prefix",
        "net/ipv6/addrconf.c:ipv6_chk_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587047328,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrlabel.c:__ipv6_addr_label",
        "net/ipv6/addrlabel.c:__ipv6_addr_label"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587080457,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_1",
        "net/ipv6/ip6_fib.c:fib6_add_1",
        "net/ipv6/ip6_fib.c:fib6_add_1",
        "net/ipv6/ip6_fib.c:fib6_locate_1",
        "net/ipv6/ip6_fib.c:fib6_locate_1",
        "net/ipv6/ip6_fib.c:fib6_lookup_1",
        "net/ipv6/ip6_fib.c:fib6_lookup_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226979,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:68",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_action"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
__u64 __fswab64(__u64 val)
```

```json
{
  "name": "__fswab64",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "arch/arm64/kernel/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "arch/arm64/kernel/machine_kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "virt/kvm/arm/mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/firmware/efi/libstub/fdt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/fdt_rw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/fdt_sw.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491956732,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "kernel/bpf/lpm_trie.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493098616,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "mm/memtest.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:reserve_bad_mem"
      ]
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495690596,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:crypto_sha1_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/gf128mul.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495712428,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "block/partitions/ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "block/sed-opal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496174080,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:__sha256_final"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/mpi/mpicoder.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/soc/fsl/qbman/bman.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/soc/fsl/qbman/qman.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/char/tpm/eventlog/of.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/scsi/scsi_error.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/scsi/scsi_trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/scsi/scsi_common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/net/ethernet/freescale/fman/fman_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/of/property.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502219252,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "net/ipv6/addrlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493098616,
      "name": "__fswab64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
__u64 __fswab64(__u64 val)
```

```json
{
  "name": "__fswab64",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272230862,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:blk_log_remap",
        "kernel/trace/blktrace.c:get_pdu_int",
        "kernel/trace/blktrace.c:blk_add_trace_rq_remap",
        "kernel/trace/blktrace.c:blk_add_trace_bio_remap",
        "kernel/trace/blktrace.c:blk_add_trace_split",
        "kernel/trace/blktrace.c:blk_add_trace_unplug"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "kernel/bpf/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272949052,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "mm/memtest.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:reserve_bad_mem"
      ]
    },
    {
      "addr": 18446743936274028196,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274036244,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/jbd2/recovery.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/recovery.c:do_one_pass"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274045202,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "fs/jbd2/revoke.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/revoke.c:jbd2_journal_write_revoke_records"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274489404,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "security/selinux/ss/policydb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274838482,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/sha1_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha1_generic.c:sha1_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274841926,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/sha512_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/sha512_generic.c:crypto_sha512_finup",
        "crypto/sha512_generic.c:crypto_sha512_finup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274844122,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/gf128mul.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/gf128mul.c:gf128mul_init_4k_bbe",
        "crypto/gf128mul.c:gf128mul_init_4k_bbe",
        "crypto/gf128mul.c:gf128mul_init_4k_bbe",
        "crypto/gf128mul.c:gf128mul_init_4k_bbe",
        "crypto/gf128mul.c:gf128mul_init_4k_lle",
        "crypto/gf128mul.c:gf128mul_init_4k_lle",
        "crypto/gf128mul.c:gf128mul_init_4k_lle",
        "crypto/gf128mul.c:gf128mul_init_4k_lle",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_init_64k_bbe",
        "crypto/gf128mul.c:gf128mul_bbe",
        "crypto/gf128mul.c:gf128mul_bbe",
        "crypto/gf128mul.c:gf128mul_bbe",
        "crypto/gf128mul.c:gf128mul_bbe",
        "crypto/gf128mul.c:gf128mul_lle",
        "crypto/gf128mul.c:gf128mul_lle",
        "crypto/gf128mul.c:gf128mul_lle",
        "crypto/gf128mul.c:gf128mul_lle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274859864,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/gcm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274888626,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "crypto/drbg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/drbg.c:drbg_hash_generate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275159440,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "block/sed-opal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:opal_discovery0_end",
        "block/sed-opal.c:opal_discovery0_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275230982,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/crypto/sha256.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/crypto/sha256.c:__sha256_final"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275380468,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/mpi/mpicoder.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/mpi/mpicoder.c:mpi_write_to_sgl",
        "lib/mpi/mpicoder.c:mpi_read_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275392678,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/digsig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/digsig.c:digsig_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/virtio/virtio_ring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276307800,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/char/tpm/eventlog/of.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/eventlog/of.c:tpm_read_log_of"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276450410,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_parse_64_be_inplace",
        "drivers/base/regmap/regmap.c:regmap_parse_64_be",
        "drivers/base/regmap/regmap.c:regmap_format_64_be"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278081110,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "drivers/of/property.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/of/property.c:of_property_read_u64_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278459018,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_set_tunnel_key",
        "net/core/filter.c:bpf_skb_get_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279713244,
      "name": "__fswab64",
      "external": false,
      "loc": "include/uapi/linux/swab.h:65",
      "file": "lib/fdt_rw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/fdt_rw.c:fdt_add_mem_rsv",
        "lib/fdt_rw.c:fdt_add_mem_rsv"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272949052,
      "name": "__fswab64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
__u64 __fswab64(__u64 val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
__u64 __fswab64(__u64 val)
```
</details>
</li>
</ul>
