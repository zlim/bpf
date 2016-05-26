# bpf

## TODO (arm64 eBPF)
 - implement tail call [ZL - target 4.8]
 - implement BPF_STX | BPF_XADD | BPF_{W,DW}
 - optimize immediates
 - ~~fix JSET~~ [ZL - https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=98397fc547e3f4553553a30ea56fa34d613f0a4c]
 - ~~optimize TMP_REG~~ [YS - https://git.kernel.org/cgit/linux/kernel/git/davem/net-next.git/commit/arch/arm64/net?id=4c1cd4fdfd14ecd417962f8c2166506132697f7c]
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
 - [net] https://git.kernel.org/cgit/linux/kernel/git/davem/net.git/log/arch/arm64/net
 - [net-next] https://git.kernel.org/cgit/linux/kernel/git/davem/net-next.git/log/arch/arm64/net
 - [arm64-next] https://git.kernel.org/cgit/linux/kernel/git/arm64/linux.git/log/arch/arm64/net?h=for-next/core
