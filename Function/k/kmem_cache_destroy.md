# Function: <code>kmem_cache_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580627232,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:700",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/zsmalloc.c:zs_destroy_pool",
        "fs/mbcache.c:mb_cache_destroy",
        "fs/dcookies.c:dcookie_register",
        "fs/dcookies.c:dcookie_unregister",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/crypto.c:ext4_exit_crypto",
        "fs/ext4/crypto.c:ext4_exit_crypto",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:journal_init",
        "fs/hugetlbfs/inode.c:exit_hugetlbfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "block/bio.c:bioset_free",
        "block/elevator.c:elv_register",
        "block/elevator.c:elv_unregister",
        "block/bsg.c:bsg_init",
        "block/cfq-iosched.c:cfq_exit",
        "lib/btree.c:btree_module_exit",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:free_on_init_error",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/scsi/scsi.c:scsi_setup_command_freelist",
        "drivers/scsi/scsi_lib.c:scsi_init_queue",
        "drivers/scsi/scsi_lib.c:scsi_init_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580627232,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732288,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:706",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/mbcache.c:mbcache_exit",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "block/bio.c:bioset_free",
        "block/elevator.c:elv_unregister",
        "block/elevator.c:elv_register",
        "block/bsg.c:bsg_init",
        "block/cfq-iosched.c:cfq_exit",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:free_on_init_error",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/scsi/scsi.c:scsi_setup_command_freelist",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732288,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580798064,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:735",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/mbcache.c:mbcache_exit",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "block/bio.c:bioset_free",
        "block/elevator.c:elv_unregister",
        "block/elevator.c:elv_register",
        "block/bsg.c:bsg_init",
        "block/cfq-iosched.c:cfq_exit",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:free_on_init_error",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/scsi/scsi.c:scsi_setup_command_freelist",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580798064,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580835568,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:811",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/ss/ebitmap.c:ebitmap_cache_destroy",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "block/bio.c:bioset_free",
        "block/elevator.c:elv_register",
        "block/bsg.c:bsg_init",
        "block/cfq-iosched.c:cfq_exit",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:__dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580835568,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580926256,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:820",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/selinux/ss/ebitmap.c:ebitmap_cache_destroy",
        "security/selinux/ss/hashtab.c:hashtab_cache_destroy",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "security/selinux/ss/avtab.c:avtab_cache_destroy",
        "block/bio.c:bioset_free",
        "block/elevator.c:elv_register",
        "block/bsg.c:bsg_init",
        "block/cfq-iosched.c:cfq_exit",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:__dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580926256,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063920,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:874",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "block/bsg.c:bsg_init",
        "block/cfq-iosched.c:cfq_exit",
        "block/cfq-iosched.c:cfq_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_fs_init",
        "drivers/dax/super.c:__dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063920,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141712,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:901",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches",
        "fs/jbd2/journal.c:journal_init",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:free_iommu_resources",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_fs_init",
        "drivers/dax/super.c:__dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm.c:local_init",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141712,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:926",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_exit",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214546,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581208320,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581273183,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581266816,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_slab_init",
        "mm/ksm.c:ksm_slab_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_exit",
        "fs/dcookies.c:dcookie_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "block/bio.c:bio_put_slab",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dmaengine_init_unmap_pool",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:iommu_init_mempool",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463244,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581456192,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:482",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_slab_init",
        "mm/ksm.c:ksm_slab_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_exit",
        "fs/dcookies.c:dcookie_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "block/bio.c:bio_put_slab",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dmaengine_init_unmap_pool",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:iommu_init_mempool",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591326454,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581499104,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:496",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591268504,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071581520544,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:498",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/intel/iommu.c:intel_iommu_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592195022,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071581782208,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582169568,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:494",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/amd/init.c:free_iommu_resources",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582169568,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582649680,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:480",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:exit_fat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/apparmor/lsm.c:apparmor_init",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582649680,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582859216,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:480",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:zswap_setup",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:exit_fat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/apparmor/lsm.c:apparmor_init",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/virtio_scsi.c:virtio_scsi_fini",
        "drivers/scsi/virtio_scsi.c:virtio_scsi_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582859216,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583034688,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:475",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "kernel/trace/trace_events_user.c:trace_events_user_init",
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:zswap_setup",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/page-io.c:ext4_init_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:exit_fat_fs",
        "fs/ecryptfs/main.c:ecryptfs_exit",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/ecryptfs/main.c:ecryptfs_init",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_exit",
        "fs/fuse/inode.c:fuse_init",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/apparmor/lsm.c:apparmor_init",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "block/blk-crypto-fallback.c:blk_crypto_fallback_init",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/amd/init.c:state_next",
        "drivers/dax/super.c:dax_core_exit",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/virtio_scsi.c:virtio_scsi_fini",
        "drivers/scsi/virtio_scsi.c:virtio_scsi_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034688,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492668904,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_exit",
        "virt/kvm/kvm_main.c:kvm_init",
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492668904,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226507880,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/omap-iommu.c:omap_iommu_init",
        "drivers/iommu/exynos-iommu.c:exynos_iommu_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226507880,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285995536,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285995536,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272679400,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272679400,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581242031,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581235664,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188703,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581182336,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/virtio_scsi.c:fini",
        "drivers/scsi/virtio_scsi.c:init",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_end",
        "net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_fini",
        "net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_init",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233231,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581226864,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void kmem_cache_destroy(struct kmem_cache * s)
```

```json
{
  "name": "kmem_cache_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_destroy",
      "external": true,
      "loc": "mm/slab_common.c:940",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_init",
        "mm/zswap.c:init_zswap",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:khugepaged_destroy",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_destroy_pool",
        "mm/zsmalloc.c:zs_create_pool",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/crypto/crypto.c:fscrypt_init",
        "fs/verity/open.c:fsverity_exit_info_cache",
        "fs/mbcache.c:mbcache_exit",
        "fs/configfs/mount.c:configfs_exit",
        "fs/configfs/mount.c:configfs_init",
        "fs/dcookies.c:dcookie_unregister",
        "fs/dcookies.c:dcookie_register",
        "fs/ext4/block_validity.c:ext4_exit_system_zone",
        "fs/ext4/extents_status.c:ext4_exit_pending",
        "fs/ext4/extents_status.c:ext4_exit_es",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_exit_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/mballoc.c:ext4_init_mballoc",
        "fs/ext4/page-io.c:ext4_exit_pageio",
        "fs/ext4/readpage.c:ext4_exit_post_read_processing",
        "fs/ext4/readpage.c:ext4_init_post_read_processing",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_init_fs",
        "fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache",
        "fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/jbd2/journal.c:jbd2_journal_destroy_caches",
        "fs/squashfs/super.c:exit_squashfs_fs",
        "fs/squashfs/super.c:init_squashfs_fs",
        "fs/hugetlbfs/inode.c:init_hugetlbfs_fs",
        "fs/fat/cache.c:fat_cache_destroy",
        "fs/fat/inode.c:fat_destroy_inodecache",
        "fs/ecryptfs/main.c:ecryptfs_free_kmem_caches",
        "fs/fuse/dev.c:fuse_dev_cleanup",
        "fs/fuse/dev.c:fuse_dev_init",
        "fs/fuse/inode.c:fuse_init",
        "fs/fuse/inode.c:fuse_fs_cleanup",
        "ipc/mqueue.c:init_mqueue_fs",
        "security/smack/smack_lsm.c:smack_init",
        "block/bio.c:bioset_exit",
        "block/elevator.c:elv_register",
        "lib/btree.c:btree_module_exit",
        "lib/sg_pool.c:sg_pool_exit",
        "lib/sg_pool.c:sg_pool_init",
        "drivers/acpi/osl.c:acpi_os_delete_cache",
        "drivers/dma/dmaengine.c:dma_bus_init",
        "drivers/iommu/iova.c:iova_cache_put",
        "drivers/iommu/amd_iommu_init.c:state_next",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/dax/super.c:dax_core_init",
        "drivers/dax/super.c:dax_fs_exit",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/scsi_lib.c:scsi_exit_queue",
        "drivers/scsi/sd.c:exit_sd",
        "drivers/scsi/sd.c:init_sd",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_remove",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_init",
        "drivers/md/dm-uevent.c:dm_uevent_exit",
        "drivers/md/dm-io.c:dm_io_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_exit",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_unregister",
        "net/core/sock.c:proto_register",
        "net/core/sock.c:proto_register",
        "net/ipv4/inet_fragment.c:inet_frags_fini",
        "net/ipv4/ipmr.c:ip_mr_init",
        "net/ipv6/route.c:ip6_route_cleanup",
        "net/ipv6/route.c:ip6_route_init",
        "net/ipv6/ip6_fib.c:fib6_gc_cleanup",
        "net/ipv6/ip6_fib.c:fib6_init",
        "net/ipv6/ip6mr.c:ip6_mr_cleanup",
        "net/ipv6/ip6mr.c:ip6_mr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296767,
      "name": "kmem_cache_destroy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071581288064,
      "name": "kmem_cache_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
