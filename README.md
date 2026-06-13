# Modified version of the original GEBCS tool

## Requires .NET 5.0
- i use Visual Studio 2019 when modifying overall code.


## Unpack/Repack (Base Game)
- Notes: `package.rdp` and `system.res` must be present inside the tool's directory
1. Unpack: GEBCS.exe -x
2. Repack: GEBCS.exe -c
3. Repack *(with compression value from 1-9)*: GEBCS.exe -c 5

# DLC Content:
- Copy the required DLC input files from `\PSP\GAME\[NPJH50352|ULES01519|ULUS10563]`

1. Unpack: GEBCS.exe -xdlc `f3594808fb6a0f2123811d0d26b0af74.EDAT` `4a92f06c65fd9bc1536e36e89a065222.EDAT`
2. Repack: GEBCS.exe -cdlc `f3594808fb6a0f2123811d0d26b0af74.EDAT` `4a92f06c65fd9bc1536e36e89a065222.EDAT`