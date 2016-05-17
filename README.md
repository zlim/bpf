# bpf

## TODO (arm64 eBPF)
 - ~~fix JSET~~ [ZL - https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=98397fc547e3f4553553a30ea56fa34d613f0a4c]
 - implement BPF_STX | BPF_XADD | BPF_{W,DW}
 - optimize immediates
 - implement tail call
 - optimize TMP_REG [YS]
 - CI: test_bpf
 - CI: seccomp
 - CI: samples/bpf
 - CI: tc + eBPF (for tail call)

Note: We've reached out to Linaro/kernelci.org to see how we can leverage their infrastructure for CI.

## Developers
 - [DB] ```Daniel Borkmann <daniel@iogearbox.net>```
 - [YS] ```Yang Shi <yang.shi@linaro.org>```
 - [ZL] ```Zi Shen Lim <zlim.lnx@gmail.com>```

## Git
 - [mainline] https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/log/arch/arm64/net
 - [net-next] http://git.kernel.org/cgit/linux/kernel/git/davem/net-next.git/log/arch/arm64/net
 - [arm64-next] https://git.kernel.org/cgit/linux/kernel/git/arm64/linux.git/log/arch/arm64/net?h=for-next/core
