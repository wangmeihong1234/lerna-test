#下载依赖（1112）
lerna  bootstrap
#编译(基于改动编译)(2111)
lerna run build --since
#发布(2111)
lerna publish --yes --repo-version prerelease