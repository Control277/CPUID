# CPUID
Small code to get all information of your CPU

## usage:
1. gcc CPUID.c -o CPUID  
2. ./CPUID

## Sample:
### (I use my own MacBook Pro 13 2018, with Intel Core i5-8259U)
```
CPU Vendor:  GenuineIntel
CPU Name:  Intel(R) Core(TM) i5-8259U CPU @ 2.30GHz
CPU Basic Information: Family:6  Model:E  Stepping ID:A
CPU Extended Information: ExFamily:0  ExModel:8  Type:0
CPU Brand Index: 0x0
CPU CLFLUSH Line Size: 0x8
CPU Maximum Logical Processors: 16
CPU Initial APIC ID: 0x4
LAHF/SAHF:              	Yes
LZCNT:                  	No
PREFETCHW:              	Yes
SYSCALL/SYSRET:         	Yes
Execute Disable Bit:    	Yes
1-GByte pages:          	Yes
RDTSCP and IA32_TSC_AUX:	Yes
Intel 64 Architecture:  	Yes

CPU Cache Information:
------------------------------------------------------------

CPU TLB Information:
------------------------------------------------------------
Data TLB:            	2 MByte/4 MByte pages, 4-way set associative, 32 entries and a separate array with 1 GByte pages, 4-way set associative, 4 entries
Data TLB:            	4 KByte pages, 4-way set associative, 64 entries
Instruction TLB:     	2 MByte/4 MByte pages, fully associative, 8 entries
Instruction TLB:     	4 KByte pages, 8-way set associative, 64 entries
L2 Shared TLB:       	4 KByte/2 MByte pages, 6-way associative, 1536 entries. Also 1 GBbyte pages, 4-way, 16 entries.

CPU Prefetch Information:
------------------------------------------------------------
Prefetch:            	64 Byte prefetching

CPU Cache Information:
------------------------------------------------------------
L1 Data Cache:       	32 KBytes, 8-way set associative, 64 byte line size
L1 Instruction Cache:	32 KBytes, 8-way set associative, 64 byte line size
L2 Unified Cache:    	256 KBytes, 4-way set associative, 64 byte line size
L3 Unified Cache:    	6 MBytes, 12-way set associative, 64 byte line size

CPU Serial Number: 00

CPU Instruction Set Support:
------------------------------------------------------------
SSE3: 1         PCLMULQDQ: 1    DTES64: 1       MONITOR: 1
DS-CPL: 1       VMX: 1          SMX: 0          EIST: 1
TM2: 1          SSE3: 1         CNXT-ID: 0      SDBG: 1
FMA: 1          CMPXCHG16B: 1   xTPR: 1         PDCM: 1
PCID: 1         DCA: 0          SSE4.1: 1       SSE4.2: 1
x2APIC: 1       MOVBE: 1        POPCNT: 1       TSC-D: 1
AESNI: 1        XSAVE: 1        OSXSAVE: 1      AVX: 1
F16C: 1         RDRAND: 1       FPU: 1          VME: 1
DE: 1           PSE: 1          TSC: 1          MSR: 1
PAE: 1          MCE: 1          CX8: 1          APIC: 1
SEP: 1          MTRR: 1         PGE: 1          MCA: 1
CMOV: 1         PAT: 1          PSE-36: 1       PSN: 0
CLFSN: 1        DS: 1           ACPI: 1         MMX: 1
FXSR: 1         SSE: 1          SSE2: 1         SS: 1
HTT: 1          TM: 1           PBE: 1          FSGSBASE: 1
IA32_MSR: 1     SGX: 1          BMI1: 1         HLE: 0
AVX2: 1         FDP_ONLY: 0     SMEP: 1         BMI2: 1
EnhanREP: 1     INVPCID: 1      RTM: 0          RDT-M: 0
FPU CD&DS: 1    MPX: 1          RDT-A: 0        AVX512F: 0
AVX512DQ: 0     RDSEED: 1       ADX: 1          SMAP: 1
AVX512_IFMA: 0  RDPID: 0        ACLFLUSHOPT: 1  CLWB: 0
PTrace: 1       AVX512PF: 0     AVX512ER: 0     AVX512CD: 0
SHA: 0          AVX512BW: 0     AVX512VL: 0     

```