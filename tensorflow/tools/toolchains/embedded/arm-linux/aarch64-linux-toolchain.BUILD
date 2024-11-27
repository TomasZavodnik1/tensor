package(default_visibility = ["//visibility:public"])

filegroup(
    name = "gcc",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-gcc",
    ],
)

filegroup(
    name = "ar",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-ar",
    ],
)

filegroup(
    name = "ld",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-ld",
    ],
)

filegroup(
    name = "nm",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-nm",
    ],
)

filegroup(
    name = "objcopy",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-objcopy",
    ],
)

filegroup(
    name = "objdump",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-objdump",
    ],
)

filegroup(
    name = "strip",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-strip",
    ],
)

filegroup(
    name = "as",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/bin/aarch64-none-linux-gnu-as",
    ],
)

filegroup(
    name = "compiler_pieces",
    srcs = [
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/arch64-unknown-linux-gnu/**",
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/libexec/**",
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/lib/gcc/arch64-unknown-linux-gnu/**",
        "/nix/store/z926q96pcanisw6jm80jbiy515bk6gi2-aarch64-unknown-linux-gnu-gcc-13.2.0/include/**",
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
