load("@rules_java//java:defs.bzl", "java_library")

java_library(
    name = "internaldep",
    srcs = ["TestClassInternalDep.java"],
    visibility = ["//querysync/javatests/com/google/idea/blaze/qsync/testdata:__subpackages__"],
    deps = ["//querysync/javatests/com/google/idea/blaze/qsync/testdata/nodeps"],
)
