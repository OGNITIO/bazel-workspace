git_repository(
    name = "protobuf",
    remote = "https://github.com/google/protobuf.git"
    tag = "v3.0.0-beta-1"
)

bind(
    name = "protobuf",
    actual = "@protobuf//:protobuf"
)

bind(
    name = "protobuf_java",
    actual = "@protobuf//:protobuf_java"
)

git_repository(
    name = "tensorflow",
    remote = "https://github.com/tensorflow/tensorflow.git",
    tag = "0.5.0",
)

bind(
    name = "tensorflow",
    actual = "@tensorflow//tensorflow:tensorflow_py"
)
