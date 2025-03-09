# Function: <code>test_bit_le</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581528374,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554288,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558062,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782349,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:mb_find_order_for_block",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:ext4_group_add_blocks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585782199,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_copy_from_slot"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581714019,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740235,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743820,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582011665,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586188297,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581801651,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581827771,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581831548,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582101729,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586392432,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581872986,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951563,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581989010,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582065939,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586494254,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:52",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582022986,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100603,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138434,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215449,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962058,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582211198,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582288898,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321242,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405327,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256972,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582306046,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582387634,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424810,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582504591,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586179780,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587437711,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582472400,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582555834,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593836,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675496,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417531,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587709992,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582571321,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582656730,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694387,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582777528,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586564219,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914296,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582879433,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968094,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583006512,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089106,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587348664,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766394,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582952153,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043712,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_mark_inode_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079454,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583168005,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587410184,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786858,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582978042,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069634,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_mark_inode_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104475,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194950,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587292133,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672711,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583313765,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583407714,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_mark_inode_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583444649,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583537974,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858933,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589350934,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:83",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int test_bit_le(int nr, const void * addr)
```

```json
{
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583821215,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922964,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_mark_inode_used"
      ],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ]
    },
    {
      "addr": 18446744071583967901,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070562,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589210346,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590824717,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909984,
      "name": "test_bit_le",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584443535,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584549002,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_mark_inode_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595687,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584703362,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590765795,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592512541,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584672335,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584777850,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_mark_inode_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584821991,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927061,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591107221,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592942992,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584905055,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585010730,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_mark_inode_used"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054967,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585142046,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_buddy_mark_free",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591452549,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593692771,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:19",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494218076,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494309140,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494351420,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494443756,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499453820,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501145932,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227648808,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227744588,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 3227785320,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 3227880836,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287913976,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055288028524,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288081080,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288197044,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292714200,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273674842,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273750246,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273781118,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273856266,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276676566,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582540057,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582625466,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663123,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582746264,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586254699,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545272,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582477225,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582562634,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600291,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582683432,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073067,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313368,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582530537,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582615322,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652979,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736120,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586512187,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587870440,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
  "name": "test_bit_le",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582611211,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582698298,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737999,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_get_inode_loc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582821352,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_scan_aligned",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_mark_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:mb_find_order_for_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586623931,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/nvdimm/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/label.c:nd_label_data_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587985535,
      "name": "test_bit_le",
      "external": false,
      "loc": "include/asm-generic/bitops/le.h:53",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int test_bit_le(int nr, const void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int test_bit_le(int nr, const void * addr)
```
</details>
</li>
</ul>
