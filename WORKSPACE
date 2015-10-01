new_http_archive(
    name = "sqlite3-src",
    url = "https://www.sqlite.org/2015/sqlite-src-3081101.zip",
    strip_prefix = "sqlite-src-3081101",
    sha256 = "261ad454663f66fda6101b278bb7b3931cf01884deefbf4ea6b152f83a624662",
    build_file = "BUILD.sqlite3",
)

bind(
    name = "sqlite3",
    actual = "@sqlite3-src//:sqlite3",
)
