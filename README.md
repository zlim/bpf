> Please submit your pull requests to update this README :)

# bpf

## TODO (arm64 eBPF)
 - implement tail call [ZL - https://patchwork.ozlabs.org/patch/630313/]
 - implement BPF_STX | BPF_XADD | BPF_{W,DW} [YS?]
 - optimize immediates
 - ~~fix JSET~~ [ZL - https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=98397fc547e3f4553553a30ea56fa34d613f0a4c]
 - ~~optimize TMP_REG~~ [YS - https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/arch/arm64/net?id=4c1cd4fdfd14ecd417962f8c2166506132697f7c]
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

## Useful References (BPF)
 - [bpf] http://man7.org/linux/man-pages/man2/bpf.2.html
 - [tc-bpf] http://man7.org/linux/man-pages/man8/tc-bpf.8.html
 - [Daniel's talks] http://borkmann.ch/talks/
 - [iovisor/bpf-docs] https://github.com/iovisor/bpf-docs
 - [iproute2/examples/bpf] https://git.kernel.org/cgit/linux/kernel/git/shemminger/iproute2.git/tree/examples/bpf
 
## Useful References (ARM)
  - [ARMv8-A Reference Manual] http://infocenter.arm.com/help/index.jsp?topic=/com.arm.doc.ddi0487a.i/index.html
  - [AAPCS64] http://infocenter.arm.com/help/index.jsp?topic=/com.arm.doc.ihi0055b/index.html
