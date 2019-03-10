load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "bazel_toolchains",
    sha256 = "4b1468b254a572dbe134cc1fd7c6eab1618a72acd339749ea343bd8f55c3b7eb",
    strip_prefix = "bazel-toolchains-d665ccfa3e9c90fa789671bf4ef5f7c19c5715c4",
    urls = [
        "https://mirror.bazel.build/github.com/bazelbuild/bazel-toolchains/archive/d665ccfa3e9c90fa789671bf4ef5f7c19c5715c4.tar.gz",
        "https://github.com/bazelbuild/bazel-toolchains/archive/d665ccfa3e9c90fa789671bf4ef5f7c19c5715c4.tar.gz",
    ],
)

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "com_github_edschouten_rules_elm",
    commit = "fe553486b0c5792ba4128e7d50e8e249a7f6ca4b",
    remote = "https://github.com/EdSchouten/rules_elm.git",
)

load("@com_github_edschouten_rules_elm//elm:deps.bzl", "elm_register_toolchains")

elm_register_toolchains()

load("@com_github_edschouten_rules_elm//repository:def.bzl", "elm_repository")

elm_repository(
    name = "elm_package_elm_browser",
    sha256 = "c4c3cb453bfe2dfc3a31f1760688d96e82d0bf091e00c99faadb8ed495dff5aa",
    strip_prefix = "browser-1.0.0",
    urls = ["https://github.com/elm/browser/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_core",
    sha256 = "9cfa20b6468b8bfb4f02c6652f43de1dd1c58b328060830ab804964da0417982",
    strip_prefix = "core-1.0.0",
    urls = ["https://github.com/elm/core/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_explorations_markdown",
    sha256 = "dee4da750f4cdb7c48f021775c4ccad727a8f853f4b639f7709c13d52308614c",
    strip_prefix = "markdown-1.0.0",
    urls = ["https://github.com/elm-explorations/markdown/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_html",
    sha256 = "73b885e0a3d2f9781b1c9bbcc1ee9ac032f503f5ef46a27da3ba617cebbf6fd8",
    strip_prefix = "html-1.0.0",
    urls = ["https://github.com/elm/html/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_http",
    sha256 = "88ea7bdeaefc56631aeb0e024ae4133d60aafa7caa23195694f9531513aaf5c5",
    strip_prefix = "http-1.0.0",
    urls = ["https://github.com/elm/http/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_json",
    sha256 = "cbba2f0ea00fc83f5781207a7de1d49f5a1ad6ed3ce578f218060b87a75310bc",
    strip_prefix = "json-1.0.0",
    urls = ["https://github.com/elm/json/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_parser",
    sha256 = "8c1fd91229a45edddcf981ac2a06d2c9f19a21a07a2ffe37e66a670a06a69f4c",
    strip_prefix = "parser-1.0.0",
    urls = ["https://github.com/elm/parser/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_time",
    sha256 = "e18bca487adec67bfe4043a33b975d81527a7732377050d0421dd86d503c906d",
    strip_prefix = "time-1.0.0",
    urls = ["https://github.com/elm/time/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_url",
    sha256 = "840e9d45d8a9bd64a7f76421a1de2518e02c7cbea7ed42efd380b4e875e9682b",
    strip_prefix = "url-1.0.0",
    urls = ["https://github.com/elm/url/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_elm_virtual_dom",
    sha256 = "5899564798629e91ef95238f8ba7f4d40260d18496b622469d69fc03457aa842",
    strip_prefix = "virtual-dom-1.0.0",
    urls = ["https://github.com/elm/virtual-dom/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_noredink_elm_json_decode_pipeline",
    sha256 = "d4c272a21626a02f8e782929e74def3ee04e1e0431741f1eed0287ee81ed4578",
    strip_prefix = "elm-json-decode-pipeline-1.0.0",
    urls = ["https://github.com/NoRedInk/elm-json-decode-pipeline/archive/1.0.0.tar.gz"],
)

elm_repository(
    name = "elm_package_rtfeldman_elm_iso8601_date_strings",
    sha256 = "3e78b642298e483584f6c4938e00649fbe550680126e9717f58a281d125bc5fb",
    strip_prefix = "elm-iso8601-date-strings-1.1.0",
    urls = ["https://github.com/rtfeldman/elm-iso8601-date-strings/archive/1.1.0.tar.gz"],
)