load("@rules_java//java:defs.bzl", "java_binary")

java_binary(
    name = "runner",
    test = "sample",
    srcs = ["Runner.java"],
    main_class = "com.example.cmdline.Runner",
    deps = ["//:greeter"],
)
