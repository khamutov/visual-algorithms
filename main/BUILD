load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
    name = "app",
    srcs = ["main.cc"],
    deps = [
    	"@raylib//:raylib",
    ],
    linkopts = [
    	"-framework CoreVideo -framework IOKit -framework Cocoa -framework GLUT -framework OpenGL"
    ],
)
