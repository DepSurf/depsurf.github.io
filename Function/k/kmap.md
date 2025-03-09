# Function: <code>kmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579947447,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580591163,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_follow_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580662340,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580771360,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974266,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020209,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581040283,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581195026,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318188,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373945,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581385555,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722308,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ext4/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/symlink.c:ext4_encrypted_follow_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009701,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582014632,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079235,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582657104,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016149,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583026481,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_to_iter_iovec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587343743,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584245098,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584473944,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_data_read",
        "drivers/base/firmware_class.c:firmware_data_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586188351,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586240914,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_and_csum_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586573413,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978382,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580771892,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894452,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128205,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181334,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581359074,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484628,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555020,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566425,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224097,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582228651,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294568,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582903263,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307047,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583311636,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_to_iter_iovec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587843823,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584587203,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584819294,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586403280,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609087,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586664352,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_and_csum_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016478,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580008830,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865917,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962852,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203258,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258550,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581438626,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565798,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581640111,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651053,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313601,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318155,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583003001,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426369,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583431524,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_to_iter_iovec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058685,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768771,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585012862,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586612607,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586793423,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586849510,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_and_csum_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587212342,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580016666,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913062,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009636,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250975,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308102,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581493266,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621846,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691322,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703833,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582398289,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402802,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053128,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583447374,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583462708,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588285349,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838183,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584853026,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584858548,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585097979,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586737750,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586916847,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586970485,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_and_csum_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587344463,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:56",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580063754,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012278,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105061,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SYSC_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382805,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447779,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581635282,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766534,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837171,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849699,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582549147,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553618,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583218808,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583627502,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583635626,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588850597,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585259129,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585264267,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585272555,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585277563,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585523803,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/base/firmware_class.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_class.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587222246,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409087,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587469093,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_and_csum_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587864568,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580120992,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581145910,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259399,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533163,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605660,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581793810,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934277,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016618,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582031375,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741147,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582745665,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426949,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843840,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583852668,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589229781,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585495942,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-interface.c:tpm_startup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585501211,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585509543,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585514571,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585772075,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587523354,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587712431,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587774045,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:skb_copy_and_csum_datagram"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588210018,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:57",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580168000,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225734,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342378,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619080,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691039,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581880866,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582018770,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582104570,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582119439,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844907,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582849473,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951191,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583548149,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927537,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583936525,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589472581,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585626403,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585632347,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585634235,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585638139,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905323,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586229846,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587704186,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587845743,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587909227,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588396326,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213905,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299526,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581452124,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731645,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809010,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582005794,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155393,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266604,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582281284,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583020043,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583024364,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583132441,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583737315,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584107428,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584114972,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589931497,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585843165,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:tpm_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585846680,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585855473,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585856996,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585861814,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586141892,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586144860,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586473401,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587983194,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588150159,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588214216,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588798491,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580262305,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358294,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516349,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804781,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581881602,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582083746,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232611,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582255947,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582365994,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380370,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126235,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583130572,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238741,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583847075,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230628,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584238124,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590158761,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585989240,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585998058,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585999588,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586004406,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586290372,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586293340,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586621193,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588190394,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355391,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588418916,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589022256,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580328168,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555571,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725018,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582025625,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582109351,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582319088,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582472715,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582498977,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582647404,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660386,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446427,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451506,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565255,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584235897,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636041,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584649792,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_to_iter_iovec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591176185,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587060460,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587063420,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589056452,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589215378,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589287678,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589981061,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:137",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579267633,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313640,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600534,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773178,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582074223,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155767,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582529759,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750151,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559131,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583564082,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677610,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755049,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584766163,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_to_iter_iovec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591671879,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144956,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587147948,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589213730,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589286334,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590021832,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:147",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614254941,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317128,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623382,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800536,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582099228,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582180139,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582557805,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713359,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583582571,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583586690,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698378,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584783513,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584795108,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591616519,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587032209,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587035182,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589107362,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589180230,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936101,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:142",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615175821,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470648,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581890838,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085001,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582416714,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497611,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582873981,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039999,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583940587,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583944866,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584058582,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585213918,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585230241,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592790310,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587599265,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587602318,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589825058,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589898694,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590703150,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:153",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616941436,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580664856,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_crash_segment",
        "kernel/kexec_core.c:kimage_load_normal_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582288582,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524843,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582930578,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021021,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583439969,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514650,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584521451,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526500,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584650011,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586051186,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586075472,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594689649,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588937591,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942494,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "drivers/base/firmware_loader/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/sysfs.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591347333,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591428064,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592331662,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582781251,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583024401,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584030209,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192347,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585197924,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034786,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596426401,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593103112,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593194448,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594169326,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:164",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582995072,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234080,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585421387,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585426932,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587289938,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596966529,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593653715,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583470580,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587575810,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597894672,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594429571,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem-internal.h:167",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490411728,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:__kvm_map_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491505200,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492761960,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492939548,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493270536,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493357200,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493618244,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493807912,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493828928,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493960976,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493975488,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494835920,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494840244,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494962016,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495660672,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496105588,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496126768,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498785008,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498794364,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498796180,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498801028,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499122604,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499126736,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499513032,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501546080,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501860384,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501935092,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502628744,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * kmap(struct page * page)
```

```json
{
  "name": "kmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224508936,
      "name": "kmap",
      "external": true,
      "loc": "arch/arm/mm/highmem.c:34",
      "file": "arch/arm/mm/highmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment",
        "mm/memory.c:__access_remote_vm",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/exec.c:copy_strings",
        "fs/splice.c:write_pipe_buf",
        "fs/aio.c:aio_read_events",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump",
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment",
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "crypto/ahash.c:hash_walk_next",
        "lib/iov_iter.c:copy_page_to_iter_iovec",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/base/firmware_loader/main.c:fw_decompress_xz",
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/base/firmware_loader/fallback.c:firmware_data_read",
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf",
        "drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work",
        "drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work",
        "drivers/firmware/efi/capsule.c:efi_capsule_update",
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage",
        "net/core/datagram.c:__skb_datagram_iter",
        "net/ipv4/ip_output.c:ip_append_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224508936,
      "name": "kmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282717496,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "arch/powerpc/mm/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/mem.c:flush_icache_user_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284465480,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286127344,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286351512,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286795372,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286902824,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287206552,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287419312,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287448928,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287602308,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287617700,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288682844,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288688984,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288839572,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir_cached"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289797968,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290352720,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290364020,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291977576,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291989144,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291991400,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291997804,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292310644,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292315476,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292801280,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295266136,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295355752,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296226640,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272742460,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272856972,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273022992,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273079278,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273262540,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273389308,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273404112,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273488142,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274158928,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274162664,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274263094,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274812636,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275171692,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275178366,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range",
        "lib/iov_iter.c:copy_page_from_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276280632,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276295798,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276298392,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276303714,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276438406,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276440830,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276722110,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278046716,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/mmc/host/mmc_spi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278187378,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278243850,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278775936,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580231105,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327142,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485085,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773517,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850338,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582052482,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201347,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224683,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582334730,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349106,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094971,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099308,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583207477,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815811,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584199364,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584206860,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589761049,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585750216,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585759034,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585760564,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585765382,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586053620,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586056588,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586311673,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587808826,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587962175,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588025700,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588628640,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580178593,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270902,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427341,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711909,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788002,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581990034,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138995,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582162523,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582272458,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286818,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032123,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036460,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144629,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583752867,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134580,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584142076,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589485273,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585609400,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585618218,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585619748,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624566,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585899572,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585902540,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586153001,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512250,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587675279,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587738788,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588340624,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580222577,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318342,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476397,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764829,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841650,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582043762,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582191827,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215163,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582325210,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582339586,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083579,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087916,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191509,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799571,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183124,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584190620,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590204457,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585939256,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585948074,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585949604,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585954422,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586242652,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586569161,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588144922,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588293951,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588357476,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589064816,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580275376,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_load_segment",
        "kernel/kexec_core.c:kimage_load_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382211,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:__access_remote_vm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541147,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833688,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911202,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582115472,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:write_pipe_buf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268599,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582293194,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582404474,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418914,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172852,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_read_lower_page_segment",
        "fs/ecryptfs/read_write.c:ecryptfs_write_lower_page_segment"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177147,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/ecryptfs/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/crypto.c:ecryptfs_decrypt_page",
        "fs/ecryptfs/crypto.c:ecryptfs_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583285418,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583900428,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287427,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584295051,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_for_each_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590254830,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_map_iomem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586047217,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm1-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586055869,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586057383,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm2-space.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586062201,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/char/tpm/tpm-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586349349,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/main.c:fw_decompress_xz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586352290,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/base/firmware_loader/fallback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/firmware_loader/fallback.c:firmware_rw"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681301,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:kmap_udmabuf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588262367,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588429038,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/sock.c:sock_no_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588492996,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/core/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/datagram.c:__skb_datagram_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589104139,
      "name": "kmap",
      "external": false,
      "loc": "include/linux/highmem.h:81",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_append_page"
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

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * kmap(struct page * page)
```
</details>
</li>
</ul>
