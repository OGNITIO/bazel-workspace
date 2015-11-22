git_repository(
    name = "protobuf_git",
    remote = "https://github.com/google/protobuf.git",
    tag = "v3.0.0-beta-1",
)

bind(
    name = "protobuf",
    actual = "@protobuf_git//:protobuf",
)

bind(
    name = "protobuf_java",
    actual = "@protobuf_git//:protobuf_java",
)

git_repository(
    name = "tensorflow_git",
    remote = "https://github.com/tensorflow/tensorflow.git",
    tag = "0.5.0",
)

bind(
    name = "tensorflow",
    actual = "@tensorflow_git//tensorflow:tensorflow_py"
)
