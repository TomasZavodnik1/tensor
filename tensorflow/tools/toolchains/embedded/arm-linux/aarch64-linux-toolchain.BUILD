package(default_visibility = ["//visibility:public"])

filegroup(
    name = "gcc",
    srcs = [
        "aarch64-unknown-linux-gnu-gcc",
    ],
)

filegroup(
    name = "ar",
    srcs = [
        "aarch64-unknown-linux-gnu-ar",
    ],
)

filegroup(
    name = "ld",
    srcs = [
        "aarch64-unknown-linux-gnu-ld",
    ],
)

filegroup(
    name = "nm",
    srcs = [
        "aarch64-unknown-linux-gnu-nm",
    ],
)

filegroup(
    name = "objcopy",
    srcs = [
        "aarch64-unknown-linux-gnu-objcopy",
    ],
)

filegroup(
    name = "objdump",
    srcs = [
        "aarch64-unknown-linux-gnu-objdump",
    ],
)

filegroup(
    name = "strip",
    srcs = [
        "aarch64-unknown-linux-gnu-strip",
    ],
)

filegroup(
    name = "as",
    srcs = [
        "aarch64-unknown-linux-gnu-as",
    ],
)

filegroup(
    name = "compiler_pieces",
    srcs = [
        "arch64-unknown-linux-gnu/**",
        "libexec/**",
        "lib/gcc/arch64-unknown-linux-gnu/**",
        "include/**",
    ],
)

filegroup(
    name = "compiler_components",
    srcs = [
        ":ar",
        ":as",
        ":gcc",
        ":ld",
        ":nm",
        ":objcopy",
        ":objdump",
        ":strip",
    ],
)
