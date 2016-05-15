# bpf

## TODO (arm64 eBPF)
 - ~~fix JSET~~ [z - https://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/commit/?id=98397fc547e3f4553553a30ea56fa34d613f0a4c]
 - implement BPF_STX | BPF_XADD | BPF_{W,DW}
 - optimize immediates
 - implement tail call
 - optimize TMP_REG
 - CI: test_bpf
 - CI: seccomp
 - CI: samples/bpf
 - CI: tc + eBPF (for tail call)
