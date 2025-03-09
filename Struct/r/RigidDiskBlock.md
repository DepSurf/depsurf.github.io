# Struct: <code>RigidDiskBlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __be32 rdb_ID;
    __be32 rdb_SummedLongs;
    __be32 rdb_ChkSum;
    __be32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __be32 rdb_Flags;
    __be32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __be32 rdb_FileSysHeaderList;
    __be32 rdb_DriveInit;
    __be32[6] rdb_Reserved1;
    __be32 rdb_Cylinders;
    __be32 rdb_Sectors;
    __be32 rdb_Heads;
    __be32 rdb_Interleave;
    __be32 rdb_Park;
    __be32[3] rdb_Reserved2;
    __be32 rdb_WritePreComp;
    __be32 rdb_ReducedWrite;
    __be32 rdb_StepRate;
    __be32[5] rdb_Reserved3;
    __be32 rdb_RDBBlocksLo;
    __be32 rdb_RDBBlocksHi;
    __be32 rdb_LoCylinder;
    __be32 rdb_HiCylinder;
    __be32 rdb_CylBlocks;
    __be32 rdb_AutoParkSeconds;
    __be32 rdb_HighRDSKBlock;
    __be32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __be32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __be32 rdb_ID;
    __be32 rdb_SummedLongs;
    __be32 rdb_ChkSum;
    __be32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __be32 rdb_Flags;
    __be32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __be32 rdb_FileSysHeaderList;
    __be32 rdb_DriveInit;
    __be32[6] rdb_Reserved1;
    __be32 rdb_Cylinders;
    __be32 rdb_Sectors;
    __be32 rdb_Heads;
    __be32 rdb_Interleave;
    __be32 rdb_Park;
    __be32[3] rdb_Reserved2;
    __be32 rdb_WritePreComp;
    __be32 rdb_ReducedWrite;
    __be32 rdb_StepRate;
    __be32[5] rdb_Reserved3;
    __be32 rdb_RDBBlocksLo;
    __be32 rdb_RDBBlocksHi;
    __be32 rdb_LoCylinder;
    __be32 rdb_HiCylinder;
    __be32 rdb_CylBlocks;
    __be32 rdb_AutoParkSeconds;
    __be32 rdb_HighRDSKBlock;
    __be32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __be32[10] rdb_Reserved5;
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
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
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
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct RigidDiskBlock {
    __u32 rdb_ID;
    __be32 rdb_SummedLongs;
    __s32 rdb_ChkSum;
    __u32 rdb_HostID;
    __be32 rdb_BlockBytes;
    __u32 rdb_Flags;
    __u32 rdb_BadBlockList;
    __be32 rdb_PartitionList;
    __u32 rdb_FileSysHeaderList;
    __u32 rdb_DriveInit;
    __u32[6] rdb_Reserved1;
    __u32 rdb_Cylinders;
    __u32 rdb_Sectors;
    __u32 rdb_Heads;
    __u32 rdb_Interleave;
    __u32 rdb_Park;
    __u32[3] rdb_Reserved2;
    __u32 rdb_WritePreComp;
    __u32 rdb_ReducedWrite;
    __u32 rdb_StepRate;
    __u32[5] rdb_Reserved3;
    __u32 rdb_RDBBlocksLo;
    __u32 rdb_RDBBlocksHi;
    __u32 rdb_LoCylinder;
    __u32 rdb_HiCylinder;
    __u32 rdb_CylBlocks;
    __u32 rdb_AutoParkSeconds;
    __u32 rdb_HighRDSKBlock;
    __u32 rdb_Reserved4;
    char[8] rdb_DiskVendor;
    char[16] rdb_DiskProduct;
    char[4] rdb_DiskRevision;
    char[8] rdb_ControllerVendor;
    char[16] rdb_ControllerProduct;
    char[4] rdb_ControllerRevision;
    __u32[10] rdb_Reserved5;
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_ID</code> ➡️ <code>__be32 rdb_ID</code>
</li>
<li>
<b>Field type changed. </b>
<code>__s32 rdb_ChkSum</code> ➡️ <code>__be32 rdb_ChkSum</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_HostID</code> ➡️ <code>__be32 rdb_HostID</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_Flags</code> ➡️ <code>__be32 rdb_Flags</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_BadBlockList</code> ➡️ <code>__be32 rdb_BadBlockList</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_FileSysHeaderList</code> ➡️ <code>__be32 rdb_FileSysHeaderList</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_DriveInit</code> ➡️ <code>__be32 rdb_DriveInit</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[6] rdb_Reserved1</code> ➡️ <code>__be32[6] rdb_Reserved1</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_Cylinders</code> ➡️ <code>__be32 rdb_Cylinders</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_Sectors</code> ➡️ <code>__be32 rdb_Sectors</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_Heads</code> ➡️ <code>__be32 rdb_Heads</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_Interleave</code> ➡️ <code>__be32 rdb_Interleave</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_Park</code> ➡️ <code>__be32 rdb_Park</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[3] rdb_Reserved2</code> ➡️ <code>__be32[3] rdb_Reserved2</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_WritePreComp</code> ➡️ <code>__be32 rdb_WritePreComp</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_ReducedWrite</code> ➡️ <code>__be32 rdb_ReducedWrite</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_StepRate</code> ➡️ <code>__be32 rdb_StepRate</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[5] rdb_Reserved3</code> ➡️ <code>__be32[5] rdb_Reserved3</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_RDBBlocksLo</code> ➡️ <code>__be32 rdb_RDBBlocksLo</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_RDBBlocksHi</code> ➡️ <code>__be32 rdb_RDBBlocksHi</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_LoCylinder</code> ➡️ <code>__be32 rdb_LoCylinder</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_HiCylinder</code> ➡️ <code>__be32 rdb_HiCylinder</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_CylBlocks</code> ➡️ <code>__be32 rdb_CylBlocks</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_AutoParkSeconds</code> ➡️ <code>__be32 rdb_AutoParkSeconds</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_HighRDSKBlock</code> ➡️ <code>__be32 rdb_HighRDSKBlock</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32 rdb_Reserved4</code> ➡️ <code>__be32 rdb_Reserved4</code>
</li>
<li>
<b>Field type changed. </b>
<code>__u32[10] rdb_Reserved5</code> ➡️ <code>__be32[10] rdb_Reserved5</code>
</li>
</ul>
</details>
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
